# TATA Stock Price Prediction using LSTM

This project implements a time series prediction model using LSTM

##  Features

- Preprocesses data using MinMaxScaler
- Builds and trains ths LSTM model with TensorFlow/Keras
- Predicts stock prices and visualizes results

##  Model Architecture

- Model with four LSTM layers (50 units for each and Dropout)
- `Dense` output layer
- Optimizer: `rmsprop`
- Loss: `mean_squared_error`

##  Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
