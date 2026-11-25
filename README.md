# Smartphone Screen Time Prediction (Linear Regression)

A machine learning project that estimates how smartphone usage habits relate to daily screen time. I used Linear Regression to estimate screen time based on behavioral features.
## Dataset

[Kaggle Playground Series S6E8](https://www.kaggle.com/competitions/playground-series-s6e8/data)

## Methodology

- Exploratory Data Analysis (EDA)
- Missing value and outlier handling
- Feature selection
- Train-test split (80/20)
- Linear Regression and baseline comparison
- 
## Project Workflow
- Exploratory Data Analysis (EDA)
- Train-test split (80/20)
- Missing value handling using median imputation
- Outlier handling using the IQR method
- Feature correlation analysis
- Linear Regression model training
- Model evaluation and visualization
  
## Results

| Model | R² | MAE (hours) | RMSE (hours) |
|---|---:|---:|---:|
| Mean Baseline | 0.0000 | 2.3193 | 2.7159 |
| Linear Regression | 0.6539 | 1.2531 | 1.5978 |

Linear Regression explained 65.39% of the variance in test-set screen time and reduced MAE by approximately 46% compared with the baseline. The average absolute prediction error was 1.25 hours

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run

Open the notebook in Google Colab and run all cells.

## Limitations

The model estimates screen time from existing usage data,
rather than forecasting future behavior.
