# Equity-Investment-Decision
Scrape financial data and give recommendation on which ones to invest

1. Crawler and Indicators:
- Collect SP500 stock info from Wikipedia from Wikipedia [List of S&P 500 companies](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies)
- Scrape [Income Statement](https://www.marketwatch.com/investing/stock/aapl/financials), and [Balance Sheet](https://www.marketwatch.com/investing/stock/aapl/financials/balance-sheet) 
- Calculate indicators (eps, eps growth, net income)

2. Eligibility Check
Filter stock tickers which satisfy certain criteria:
- EPS increases over the year (consistent)
- ROE > 0.15
- ROA > 0.07
- Long term debt < 5 times * income
- Interest Coverage Ratio > 3
