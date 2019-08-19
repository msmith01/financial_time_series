# time_series_detection
A script to detect which financial time series is real verses which financial time series is fake or from a synthetic data class. (stock price data)

Analyses time series data and uses the tsfeatures package to generate a series of time series variables, which are then applied to an Extreme Gradient Boosted (XGBoost) model to make a classification.
