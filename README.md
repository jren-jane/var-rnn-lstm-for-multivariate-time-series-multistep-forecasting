# var-rnn-lstm-for-multivariate-time-series-multistep-forecasting
In this repository, I prepare one time series with multiple macroeconomic variables for an VAR estimation and for neural network models. It specifically includes my method to prepare the 3-dimensional data as input and target for the keras API, and to slice the one long series into multiple windows of equal lengths. Besides this, it also includes the following:
- Visualize features
- Test and estimate a VAR model for prediction
- Generate subsequences from a sequence of historical data to be converted into as supervised learning problem
- Tune hyperparameters for the RNN and LSTM models
- Train and predict using RNN and LSTM models
- Plot and compare the forecast and error distribution for various features
