# Stock Price Time Series Forecasting

1. Overview
    This project focuses on using time series analysis techniques to forecast the stock prices of Apple Inc. (AAPL). By utilizing historical stock price data, models such as ARIMA and SARIMA are developed to predict future stock prices. The project includes data preprocessing, stationarity checks, model building, and evaluation using various metrics.

2. Objectives
    1. To preprocess and clean stock price data for time series analysis.
    2. To explore the trends and patterns in stock price data through visualization.
    3. To apply stationarity tests and transform the data as needed.
    4. To build and evaluate ARIMA and SARIMA models for forecasting stock prices.
    5. To assess model accuracy using evaluation metrics like MSE, MAE, and R².

3. Time Series Forecasting
    1. AutoRegressive (AR): Using past values to predict future values.
    2. Integrated (I): Differencing the data to make it stationary.
    3. Moving Average (MA): Using past forecast errors in prediction.
    We also explore SARIMA (Seasonal ARIMA), which extends ARIMA to account for seasonal patterns in the data.

4. Dataset
    The dataset contains historical stock prices for Apple Inc. (AAPL) and includes the following fields:
    1. Open: Stock price at market opening.
    2. High: Highest price during the trading day.
    3. Low: Lowest price during the trading day.
    4. Close: Stock price at market close.
    5. Volume: The number of shares traded during the day.
