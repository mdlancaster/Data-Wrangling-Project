<b> File Descriptions:</b>

<i>nasdaq_scraping.ipynb:</i> This notebook includes the code used to scrape information on 6,561 stocks from the Nasdaq Stock Screener website and format it as a data frame. <br>

<i>yfinance_data.ipynb:</i> This notebook includes the code used to download the financial metrics and historical stock prices used in our analysis from the yfinance Python library. First, our team randomly sampled a collection of companies from <i>nasdaq_final.csv</i>. Using yfinance, we then downloaded those companies' most-recently reported quarterly balance sheet, income statement, and cash flow statement as well as their stock price from one month, six months, and one year ago. We filtered the financial statements' columns (financial metrics) based on their relevance to our analysis and then merged all of the datasets (balance sheet, income statement, cash flow statement, and historical stock prices) together to form <i>yfinance_data.csv</i>. 

<i>data_final.ipynb:</i> This code merges the <i>nasdaq_final.csv</i> and <i>yfinance_data.csv</i> datasets and conducts some final data cleaning to produce our final dataset, <i> data_final.csv </i>. 

<i>project_analysis.ipynb:</i> This code contains the methods and results of our analysis which we used to answer our guiding research questions. 
