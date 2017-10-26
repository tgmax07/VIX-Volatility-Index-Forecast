# VIX Term Structure Forecast Project
In this project, multiple Time-series forecasting methods were used to forecast the term structure of VIX Volatility Index (https://en.wikipedia.org/wiki/VIX). First, parameters for the yield curve of VIX were estimated through Nelson Siegel Svesson Model (http://comisef.eu/files/wps031.pdf). Second, ARIMA model, Vector Autoregressive Model, and Exponential Smoothing model were applied to forecast the parameters of the yield curve on a 30-day rolling window and a 90-day rolling window individually. A k-fold cross validation was performed and RMSE was calcualted for prediction accuracy. 


