# LSTM-Forecasting

Predicting Stock Prices with LSTM
This project demonstrates the use of Long Short-Term Memory (LSTM) neural networks to forecast stock prices using historical data retrieved from Yahoo Finance. The provided code will guide you through fetching stock price data, preprocessing it, training an LSTM model, and evaluating its performance.

Requirements
Ensure you have Python installed and the following libraries:

numpy
pandas
yfinance
scikit-learn
keras
tensorflow
matplotlib

Open the Python script predict_stock_price.py and update the following parameters:

ticker: Replace with the stock ticker symbol you want to analyze (e.g., 'AAPL' for Apple Inc.).
start_date and end_date: Set these to your desired date range for historical data.
After making the necessary changes, run the script.

The script performs the following steps:

Retrieves historical stock price data from Yahoo Finance.
Preprocesses the data by scaling and reshaping it for the LSTM model.
Builds and trains an LSTM model on the training dataset.
Makes predictions on the test dataset and evaluates the model using Mean Squared Error (MSE).
Plots the actual versus predicted stock prices.
