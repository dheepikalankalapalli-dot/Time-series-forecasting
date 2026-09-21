# Time-Series Forecasting with ARIMA and Prophet

## Project Description

This project focuses on time-series forecasting using historical monthly sales data. ARIMA and Prophet models are used to analyze trends, identify seasonal patterns, generate future forecasts, and evaluate model performance.

## Objectives

- Analyze historical time-series data.
- Identify trends and seasonal patterns.
- Implement the ARIMA forecasting model.
- Implement the Prophet forecasting model.
- Forecast future sales values.
- Compare model performance using MAE, RMSE, and MAPE.
- Visualize actual and predicted values.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Prophet
- Jupyter Notebook

## Dataset

The project uses monthly sales data from 2017 to 2024.

The dataset contains:

- Date
- Sales

The last 12 months are used as test data for evaluating the forecasting models.

## Methodology

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Train-Test Split
5. ARIMA Model Development
6. Prophet Model Development
7. Forecast Generation
8. Model Evaluation
9. Model Comparison
10. Future Forecasting

## Models

### ARIMA

ARIMA is used to model time-series data by considering autoregression, differencing, and moving average components.

Model used:

`ARIMA(2,1,2)`

### Prophet

Prophet is used to model trend and yearly seasonality in the monthly sales data.

## Evaluation Metrics

The models are evaluated using:

- MAE – Mean Absolute Error
- RMSE – Root Mean Squared Error
- MAPE – Mean Absolute Percentage Error

## Project Files

```text
Time-Series-Forecasting/
│
├── time_series_forecasting.py
├── monthly_sales_dataset.csv
├── model_comparison.csv
├── future_arima_forecast.csv
├── future_prophet_forecast.csv
├── sales_time_series.png
├── forecast_comparison.png
├── prophet_forecast.png
├── requirements.txt
└── README.md
