# Time-series-Prediction-Analysis

This project aims to predict the stock prices of a 50 companies using time series analysis. The data used in this project is the stock market data for 21 years. We have used the following machine learning algorithms to predict the stock prices:

* ARIMA
* FBProphet
* RNN
* LSTM

## Preprocessing

Before applying the algorithms, we preprocessed the data to remove any null or missing values, outliers, and irrelevant features. We also performed feature scaling to normalize the data.

## Algorithms

### ARIMA

We used the Autoregressive Integrated Moving Average (ARIMA) model to predict the stock prices. ARIMA is a widely used statistical method for time series forecasting.

### FBProphet

We also used FBProphet, a forecasting library released by Facebook, to predict the stock prices. It is an additive regression model that models the seasonality and trends.

### RNN

Recurrent Neural Network (RNN) is a deep learning algorithm used for sequence data. We used RNN to predict the stock prices as it is good at handling sequential data.

### LSTM

Long Short-Term Memory (LSTM) is a type of RNN that is capable of learning long-term dependencies. We used LSTM to predict the stock prices as it is good at capturing long-term trends in the data.

## Evaluation

To evaluate the accuracy of the prediction models, various metrics such as mean squared error, root mean squared error, and mean absolute error were used. The results of each model were compared and analyzed to determine the best performing model.

## Conclusion

In conclusion, we were able to predict the stock prices using time series analysis and machine learning algorithms.By observing plots of actual vs prediction,we have come to conclusion that RNN model peforms better than the rest for most of the stocks. This project can be extended to other companies' stock data to predict their future stock prices.

