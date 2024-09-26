# Predicting the price of the EUR-USD

Price trends analysis and forecasting using Prophet time series and Simple Moving Averages (SMA) for periods of 20, 50, 100, and 200 days

## Problem :
Need different,complementary ways of predicting the price of a stock or currency let's say, the EURO-USD
Predict from now to the end of the year (3 months) and 12 mnths from now
Decide if keep, buy, sell, don't do anything (wait and see)
Do it using time series in Python or similar
Steps to Prediction

Predicting the price of a stock or the EUR-USD exchange rate involves using time series forecasting methods. Two common approaches for time series forecasting in Python are using:Prophet and ARIMA.

**Modeling the Data:**

- Facebook's Prophet A popular time series forecasting library developed by Facebook.
-ARIMA (AutoRegressive Integrated Moving Average) A classical statistical method for time series forecasting.

**Collecting Data:**

- Yahoo Finance by the yfinance library in Python to download historical stock or forex data.
- Quandl: Another source for financial and economic data. Offers various financial datasets.
- Kaggle: Offers various datasets, including financial data.

**Preprocessing the Data:**

- Clean the data: Handle missing values, outliers, etc.
- Feature engineering: create additional features if necessary, like moving averages, volatility, etc.

## Decision Making

After generating forecasts, we can make decisions based on predicted trends:

Buy: If the forecast shows a significant upward trend.
Sell: If the forecast indicates a downward trend.
Hold/Don't do anything: If the forecast shows no significant change or if there is high uncertainty.

## Conclusion

The probabilities shown on the graphs seem to be that the EUR/USD will continue to go up for the 3 months left of 2024 and for the 3 months after that, it is not very sure, since it will maybe stop growing and all trends are possible.
