I am comparing treasury yields to stock market movements to determine correlation and possible predictive capabilities.  It has been said that an inverted yield curve is a reliable indicator that a pullback is soon to follow.  I have started pulling small amounts of recent data to build a prototype.  Once everything is set up and working properly I can add more data and scale up.
So far I have scraped the treasury.gov site to obtain treasury yields for 2021 using BeautifulSoup, and I have used a REST API to import JSON formatted data for the Nasdaq index.

I found an API to import Treasury Yield Data, streamlining the data gathering process.  I can now use API calls to gather data for the Treasury Yields and the Nasdaq, S&P500, and DOW Jones index.

Using Matplotlib, I have created a line plot comparing the timing of the dips for both treasury yields and the 3 indexes.  I am sending the data to Tableau for easier viewing
