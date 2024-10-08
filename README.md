# Enhancing Financial Forecast

In this project, the aim to forecast the NSE Stock prices using various statistical tools like ARIMA, GRU, LSTM, RNN, etc. 

## Data Description
I have fetched the data from Yahoo Finance using yfinance library. The data consists of the daily stock prices for the stock NSE from 01/01/2020 to 18/06/2024.


## Techniques

### 1. ARIMA

I first applied Dickey Fuller Test to find out whether the time series data is stationary. The non-stationarity of the data was eleminated by first order differencingl. 

Using autocorrelation plot and partial autocorrelation plot, I identified the parameters for the ARIMA model. I used ARIMA(1,1,1) model to forecast the data and got R Squared error as ___.

### 2.Deep Learning Methods

I took the closing prices of the stock and split it into train and test set. Then I scaled the data according to the requirement.

I have used Tensorflow to apply the various models over the data. Here are the results:

#### RNN:-
R Squared:

#### LSTM:-
R Squared:

#### GRU 
R Squared:

## Conclusion

We can see that the best method is LSTM with R Squared as ___. 

So, we have successfully created a model to forecast indian stocks. We can use it on other stocks as well and gain massive profits.

My work can be reproduced using the code provided in the ___.ipynb file.