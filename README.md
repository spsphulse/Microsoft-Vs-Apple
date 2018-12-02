# Microsoft-Vs-Apple
The war for market capitalization

One of the biggest news this week was Mircrosoft briefly overtaking Apple as the biggest company in terms of market cap. I thought it would be a good idea to graph this decade long catch-up.

# Data
Since I could not get historical market cap data as far out as 2010 directly using any API(without paying), I decided to use historical ticker prices & historical outstanding shares

Historical Ticker prices - Historical ticker prices fetched using AlphaVantage API
Historical number of outstanding shares - Got this from https://sharesoutstandinghistory.com


# Formula

Market Cap = Number of Outstanding Shares * Closing price


# Tools used
Python 3.6
Matplotlib
Pandas
AlphaVantage API
