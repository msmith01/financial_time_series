# Note: I discuss this post here: https://lf0.com/post/synth-real-time-series/financial-time-series/
# time_series_detection
A script to detect which financial time series are real verses which financial time series are false/synthetic. (stock price data)

Analyses time series data and uses the tsfeatures package to generate a series of time series variables, which are then applied to an Extreme Gradient Boosted (XGBoost) model to make a classification.

If you cannot view the notebook, try here: https://nbviewer.jupyter.org/github/msmith01/time_series_detection/blob/master/Time_Series_Classification_Financial_Markets.ipynb

# Naive_BTCUSD_prediction

A simple logistic regression strategy which tries to predict the direction of the market one time period ahead. Uses quantstrat to backtest the strategy and plot the performance over the testing period.

Note: I built this a while ago in order to get to know better the quantstrat backtesting package in R and not for live trading.
