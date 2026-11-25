# Smartphone Screen Time Prediction (Linear Regression)

A machine learning project that estimates daily smartphone 
screen time using behavioral data and Linear Regression.

## Dataset

[Kaggle Playground Series S6E8](https://www.kaggle.com/competitions/playground-series-s6e8/data)

## Methodology

- Exploratory Data Analysis (EDA)
- Missing value and outlier handling
- Feature selection
- Train-test split (80/20)
- Linear Regression and baseline comparison

## Results

| Model | R² | MAE (hours) | RMSE (hours) |
|---|---:|---:|---:|
| Mean Baseline | 0.0000 | 2.3193 | 2.7159 |
| Linear Regression | 0.6539 | 1.2531 | 1.5978 |

Linear Regression reduced MAE by 46% compared to the baseline.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run

Open the notebook in Google Colab and run all cells.

## Limitations

The model estimates screen time from existing usage data,
rather than forecasting future behavior.
