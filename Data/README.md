<b> File Descriptions: </b> <br>
<i> nasdaq_final.csv </i>: This dataset includes scraped data for all 6,561 Nasdaq-listed companies. The features are outlined in Features 1-6 of the data dictionary below and the process used to scrape the data is outlined in the <i>nasdaq_scraping.ipynb</i> notebook within the Code folder. <br>

<i> yfinance_data.csv </i>: This dataset features select financial metrics and historical stock prices for a random sample of companies from <i>nasdaq_final.csv</i>. The financial metrics are detailed in Features 7-22 of the data dictionary, and the historical stock prices are included as Features 23-25. The code used to download and merge the financial metrics and historical stock prices from yfinance is presented in the <i>yfinance_data.ipynb</i> notebook in the Code folder. <br>

<i> data_final.csv </i>: This is our final dataset which merged the <i>nasdaq_final.csv</i> and <i>yfinance.csv</i> datasets. The code used to do so as well as conduct some additional data cleaning is shown in the <i>data_final.ipynb</i> notebook under the Code folder. The following data dictionary details all of the features in this dataset. 

<b> Data Dictionary (data_final.csv): </b>

| # | Feature | Description | 
| --| ------- | ----------- |
|1. | Ticker | Ticker symbol of the company's stock |
|2. | Name | Company name |
|3. | Last Sale | Last sale price of company's stock (as of 5/3/25) |
|4. | Net Change | Net change in sale price from 5/2/25 to 5/3/25 |
|5. | Percent Change | Percent change in sale price from 5/2/25 to 5/3/25 |
|6. | Market Cap | Market capitalization (current share price * shares outstanding |
|7. | Shares Issued | Number of shares issued |
|8. | Total Assets | Current and Non-Current Assets | 
|9. | Net PPE | Net Property, Plant, and Equipment (book value of long-term, tangible assets after deducting depreciation) |
|10. | Accounts Receivable | Amount of money the company is owed for goods/services sold on credit |
|11. | Cash and Cash Equivalents | Amount of cash on hand and highly-liquid investments |
|12. | Total Debt | Amount of short- and long-term debts | 
|13. | Accounts Payable | Amount of money due to suppliers/vendors for goods/services purchased on credit |
|14. | Stockholders Equity | Residual value of assets after deducting liabilities |
|15. | Retained Earnings | Amount of profit reinvested into the company |
|16. | Working Capital | Difference between current assets and current liabilities |
|17. | Total Revenue | Amount of income generated from selling products/services |
|18. | Operating Income | Income generated after deducting operating expenses (a.k.a., EBIT) |
|19. | EBITDA | Earnings before interest, taxes, depreciation, and amortization | 
|20. | Net Income | Profit after deducting all expenses |
|21. | Capital Expenditures | Amount spent on long-term, tangible assets | 
|22. | Free Cash Flow | Cash flow generated after deducting cash flows that maintain operations and capital assets | 
|23. | 1 Month Stock Price | Company stock price on 4/3/25 | 
|24. | 6 Month Stock Price | Company stock price on 11/3/24 |
|25. | 1 Year Stock Price | Company stock price on 5/3/24 |
