# Stock-Market-Prices-Prediction-Using-Machine-Learning-and-Deep-Learning

# Introduction
Predicting stock market performance is a challenging task due to the volatile nature of share prices influenced by various factors, including both rational and irrational behavior. This project demonstrates how machine learning and deep learning techniques can be applied to historical stock price data to forecast future prices.

# Models Implemented
Moving Average <br>
Linear Regression <br>
k-Nearest Neighbours <br>
Auto ARIMA <br>
Prophet <br>
Long Short Term Memory (LSTM) <br>

# Dataset
The dataset includes the following columns: <br>
Date,Open,High,Low <br>
Last,Close,Total Trade Quantity,Turnover <br> 
The closing price is used as the target variable for predictions. <br>

# Techniques Used
Moving Average
The moving average technique predicts the closing price for each day based on the average of a set of previously observed values. This section demonstrates how to implement moving averages in Python.

<h3>Linear Regression</h3>
Linear regression analyzes the relationship between date features and closing prices. It involves feature engineering to extract relevant date components and uses them to build the model.

<h3>k-Nearest Neighbours</h3>
kNN predicts the closing prices by finding the average of the k closest historical points. This section provides a walkthrough of the implementation and evaluation of the kNN model.

<h3>Auto ARIMA</h3>
ARIMA is a powerful statistical method for time series forecasting. This section utilizes auto ARIMA to automatically select the best parameters for the ARIMA model to forecast stock prices.

<h3>Prophet</h3>
Prophet is a time series forecasting tool developed by Facebook, which simplifies the forecasting process without extensive data preprocessing. This section outlines how to implement the Prophet model on stock data.

<h3>Long Short Term Memory (LSTM)</h3>
LSTMs are advanced recurrent neural networks suitable for sequence prediction tasks. This section describes how to implement LSTM to predict stock prices and evaluates its performance.

# Conclusion
The project illustrates various techniques for predicting stock prices using machine learning and deep learning approaches. Despite achieving varying levels of accuracy, it emphasizes that stock price movements are influenced by unpredictable external factors, making forecasting inherently challenging.
