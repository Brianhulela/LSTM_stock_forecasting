# Stock Market Forecasting with LSTM and Python

Welcome to the repository for Stock Market Forecasting using Long Short-Term Memory (LSTM) networks in Python. This project demonstrates how to use LSTM to predict stock prices, leveraging historical stock data and powerful machine learning techniques.

![Cover Image](https://github.com/Brianhulela/LSTM_stock_forecasting/blob/master/TSLA_forecast.png)

## Overview
This repository contains a comprehensive implementation of stock market forecasting using Long Short-Term Memory (LSTM) networks. LSTM is a type of Recurrent Neural Network (RNN) that is especially well-suited for time series forecasting, such as predicting stock prices. The model takes in historical data and learns patterns over time to make future predictions.

The project includes the following key steps:
- **Data Collection**: Stock data is sourced from Yahoo Finance using the `yfinance` library. The data is cleaned, preprocessed, and ready for modeling.
- **Data Normalization**: To prepare the data for the LSTM, it is normalized using `MinMaxScaler`, which scales the data between 0 and 1 to improve model performance.
- **Model Building**: An LSTM model is constructed using Keras. The architecture includes multiple LSTM layers with dropout regularization to prevent overfitting.
- **Model Training**: The model is trained using the training dataset, with validation during training to ensure it generalizes well.
- **Forecasting**: The trained model makes predictions on the test set and forecasts future stock prices.
- **Visualization**: The code visualizes historical stock data, predicted prices, and future forecasts to evaluate the model's performance.

The code in this repository allows you to easily experiment with different configurations, modify the model, or apply it to different stock tickers. You can test the entire implementation on your own stock data to see how LSTM models perform in forecasting future stock prices.

For a more detailed explanation of the implementation, check out the full article: [Medium Article](https://hulela.co.za/stock-market-forecasting-with-lstm-38ff6b43e116).
