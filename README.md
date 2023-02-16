# Regression-Stock-Price-Prediction
Deep Learning Model: Recurrent Neural Network, BERT

the dataset is the daily historical data of Apple Inc., which is from 
Yahoo Finance. We will use this to build a regression model. The features are Date, 
Open, High, Low, Close, Adj Close, and Volume, which are common attributes for 
investors. We want to predict the ’Close’ value of the next day based on historical 
data. RNN is usually used to process time series data because it can capture 
relationships between sequences


1.- Regression: Stock Price Prediction
2.- Data Standardization or data preprocessing
  $$\eqalign{ 
  z_i = \frac{x_i - \min{x} }{\max{x} - \min{x}} 
  }$$
3.- loss function 
  $$\eqalign{ 
  MSE = \frac{1}{n} \sum{y_i - \tilde{y}_i}^2 
  }$$
