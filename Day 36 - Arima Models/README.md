## Day 36 - Time Series Analysis

- ARIMA models are defined by their order parameters: p, d, and q. "p" represents the order of autoregressive terms, "d" indicates the degree of differencing needed to make the time series stationary, and "q" signifies the order of moving average terms. Choosing the right values for these parameters is crucial for model effectiveness.

- ARIMA models require the time series data to be stationary, which means that its statistical properties like mean and variance do not change over time. If your data is not stationary, you may need to apply differencing (d) to make it so before fitting an ARIMA model.

- For time series data with seasonality, the seasonal ARIMA (SARIMA) model extends the basic ARIMA framework by introducing seasonal components represented by additional order parameters (P, D, Q, and s). "P" and "Q" are the seasonal autoregressive and moving average orders, while "D" is the degree of seasonal differencing, and "s" represents the length of the seasonal cycle.
