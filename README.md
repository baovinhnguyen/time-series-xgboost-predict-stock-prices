# xgboost-predict-stock-prices
- I built a stock price predictor that gives an estimation of 7-day 2019 stock prices for the S&P 500 Index (SPY) using XGBoost. The dependent variable is the adjusted close prices.

- I applied three data augmentation methods, which are creating time-series related features, adding lag features, and normalizing the features. The XGBoost algorithm shows better performance in terms of RMSE compared with the benchmarking model, which is a simple moving average model. 
