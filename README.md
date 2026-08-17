# Smartphone Screen Time Prediction (Linear Regression)

A Linear Regression model that predicts a user's daily screen time (`daily_screen_time_hours`) using the Kaggle Playground Series (S6E8) dataset (~690K rows).

## Project Steps
- Filled missing values using median (numeric) and mode (categorical)
- Detected and cleaned outliers using the IQR method
- Explored correlations between features and the target
- Compared different feature combinations to find the best model
- Evaluated with train/test split and MAE, RMSE, R² metrics

## Result
Using `social_media_hours`, `gaming_hours`, `app_opens_per_day`, `notifications_per_day`, and `weekend_screen_time` as features:
- **R² = 0.58**
- **MAE = 1.26 hours**
- **RMSE = 1.61 hours**

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
