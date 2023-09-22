# Time Series Forecasting with Linear Regression

## Overview

This project focuses on time series analysis and forecasting using linear regression with trend and seasonality. The primary goal is to model and predict time series data that exhibits a definite upward trend and substantial seasonality. Linear regression is employed as it successfully captures these observable trends and seasonal changes, making it an appropriate choice.

## Key Findings

### Model Performance

- The model's predictions exhibit significant inaccuracies, as indicated by the following performance metrics:
  - Mean Squared Error (MSE): 2,204,908,010,075.72
  - Root Mean Squared Error (RMSE): 1,484,893.27
- An issue of overfitting is detected, as the R-squared (Coefficient of Determination) value is above 1. This suggests that the model is fitting noise rather than capturing the underlying patterns.

### Additional Metrics

- While the Mean Absolute Percentage Error (MAPE) of 2.55% may seem reasonable, it's essential to consider other metrics. The MAPE can conceal situations where the model's predictions significantly deviate from the observed data.

## Recommendations

The Linear Regression Model with Trend and Seasonality is identified as the best forecasting technique for this specific dataset and problem statement. Here's a summary of the approach:

- Seasonality is calculated to account for periodic recurring patterns in the data.
- A linear regression model is employed to capture both the trend and seasonality.
- Various indicators are used to evaluate the model's performance.

## Visualizing Model Accuracy

In the provided code and data, each blue dot's position relative to the regression line reflects the prediction error for the corresponding observation. Points farther from the line indicate larger prediction errors, while points close to the line represent accurate forecasts.

## Conclusion

This project demonstrates the use of linear regression with trend and seasonality to analyze and forecast time series data. While the model captures certain patterns, it has room for improvement, especially in reducing prediction errors and addressing overfitting.

Your feedback and contributions to enhance the model's performance are welcome.

