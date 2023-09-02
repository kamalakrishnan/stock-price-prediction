# Stock Price Prediction using LSTM
This repository contains Python code for predicting stock prices using Long Short-Term Memory (LSTM) neural networks. The code imports financial data, preprocesses it, builds an LSTM model, and makes predictions on the stock's closing prices.

# Table of Contents
Prerequisites
Usage
Concepts and Techniques

## Prerequisites
Before running the code, make sure you have the following prerequisites installed:

Python 3.x
Libraries:
yfinance
pandas
numpy
matplotlib
scikit-learn
keras

## Concepts and Techniques
This code demonstrates the following concepts and techniques:

### Data Download: 
Using the yfinance library to download historical stock price data for a specified company within a given date range.

### Data Preprocessing: 
Cleaning the data by resetting the index, handling missing values, and calculating daily returns.

### Exploratory Data Analysis (EDA): 
Visualizing the stock price, moving averages, volume, and daily returns using Matplotlib.

### Feature Scaling: 
Normalizing the stock price data using Min-Max scaling to make it suitable for training the LSTM model.

### LSTM Model: 
Building a Sequential Keras model with LSTM layers for time-series prediction. The architecture includes two LSTM layers with dropout and two dense layers.

### Training and Validation: Splitting the data into training and validation sets, training the LSTM model, and making predictions.

### Model Evaluation: Calculating the Root Mean Squared Error (RMSE) to assess the model's performance.

### Visualization: Plotting the actual stock prices, model predictions, and cumulative returns.
