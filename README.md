# Website_traffic_forecasting
Predicting website traffic using time series analysis 

In this project, I have performed the task of predicting the traffic of a website using machine learning model SARIMA ( Seasonal Autoregression Integrated moving average) to rpedict the traffic values.


The time series grapgh is first decomposed to understand the seasonality of the data then SARIMA is used to predict the traffic. ARIMA is an algorithm used for forecasting Time Series Data. ARIMA models have three parameters like ARIMA(p, d, q). Here p, d, and q are defined as:

p is the number of lagged values that need to be added or subtracted from the values (label column). It captures the autoregressive part of ARIMA.
d represents the number of times the data needs to differentiate to produce a stationary signal. If it’s stationary data, the value of d should be 0, and if it’s seasonal data, the value of d should be 1. d captures the integrated part of ARIMA.
q is the number of lagged values for the error term added or subtracted from the values (label column). It captures the moving average part of ARIMA.


Using this method, traffic for 50 days starting 26th June 2022 is predicted. 

It gave me a good exposure to the different topics of time series analysis like decompostion of time series data  along with its different parameters of additive and multiplicative and also the ARIMA model and its features. 

Inspried by article: https://thecleverprogrammer.com/2022/06/28/website-traffic-forecasting-using-python/
