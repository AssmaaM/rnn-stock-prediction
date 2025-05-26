# AAPL Stock Price Prediction using RNN

This project implements a time series prediction model using Recurrent Neural Networks (RNN) to forecast Apple Inc. (AAPL) stock prices based on historical data fetched from Yahoo Finance.

##  Features

- Downloads AAPL stock price data from Yahoo Finance
- Preprocesses data using MinMaxScaler
- Creates sequences for RNN model training
- Builds and trains a Simple RNN using TensorFlow/Keras
- Predicts stock prices and visualizes results
- Evaluates model performance using MSE, RMSE, MAE, and R²

##  Model Architecture

- `SimpleRNN` layer with 50 units and `tanh` activation
- `Dense` output layer
- Optimizer: `adam`
- Loss: `mean_squared_error`

##  Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
