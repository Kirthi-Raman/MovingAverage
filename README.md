# MovingAverage
Estimating the Moving Average of Stocks

# MovingAverage

Moving Average is mean of the n last closing prices.

Generally n is considered to be 20 since it is equal to the number of trading days in a month.

Moving Average Formula:

MA = (A1 + A2 + .... + An)/n

where 
A: is the average in the period n
n: number of periods

### Trends in Price based on Moving Average:
1) Downtrend: When in downtrend, the closing price is lesser than the moving average
2) Uptrend: When in uptrend, the closing price is higher than the moving average

### Moving Average can be calculated for a short term and long term.
1) Short Term: When moving average is considered over a short duration. Example: 20 days
2) Long Term: When moving average is considered over a long duration. Example: 250 days

### Price Trend Change: 
 - When short term MA crosses the long term MA.
Two types of Price trend changes:
1) Golden Cross: When short term MA crosses above the long term MA. This is considered as a good time to buy stocks.
2) Dead Cross: When short term MA crosses below the long term MA. This is considered as a good time to seel stocks.

### Steps in calculating the MA in Python:

1) Download stock price information from website: https://financialmodelingprep.com/ via API
2) Parse the API extracted stock data and convert it into a Pandas Dataframe
3) Calculate the short term and long term MA
4) Plot the closing price and MA together in a graph.
