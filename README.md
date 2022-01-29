# TimeSeries

Many time series tools that i have learned in tested to predict future movements in the value of the Canadian dollar versus the Japanese yen

1. Time series forecasting
2. Linear regression modelling
### Files

[Time-Series Starter Notebook](time_series_analysis.ipynb)

[Linear Regression Starter Notebook](regression_analysis.ipynb)

[CAD/JPY Data CSV File](cad_jpy.csv)

##Time-Series Forecasting

1. Plotted the Settle price to check for long or short-term pattern
2. Decomposition using a Hodrick-Prescott filter (decomposed the settle price into trend and noise).
3. Forecasted returns using an ARMA model.
4. Forecasted the exchange rate price using an ARIMA model.
5. Forecasted volatility with GARCH.

##Linear Regression Forecasting

1. Prepared Data  (created returns and lagged returns, and split the data into training and testing data)
2. Fit a linear regression model.
3. Made predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

