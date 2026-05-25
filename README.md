# Linear_Regression

A multiple linear regression model built on a Cars dataset using scikit-learn and statsmodels, covering assumption testing, model training, evaluation, and pickle-based deployment.

## Overview

This notebook predicts **Miles Per Gallon (MPG)** from car features — Horsepower (HP), Volume (VOL), Speed (SP), and Weight (WT).

## What's Covered

- Exploratory data analysis and data understanding
- Regression assumption testing:
  - Linearity, Normality, Multicollinearity (heatmap)
  - Autocorrelation, Homoscedasticity, Zero Residual Mean
- Model building & training with `sklearn.linear_model.LinearRegression`
- Model evaluation — MAE, MSE, RMSE, R², Adjusted R² (via `statsmodels` OLS)
- Feature subset comparison using Adjusted R²
- Model serialization and deployment using `pickle`

## Libraries Used

`pandas` · `matplotlib` · `seaborn` · `scikit-learn` · `statsmodels`
