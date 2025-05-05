# Data Wrangling Project 

<b> Project Background: </b> 
In this data wrangling project, we merged two datasets to analyze financial and market characteristics of NASDAQ-listed companies. The first dataset includes stock information such as ticker symbols, last sale prices, and market capitalizations. The second dataset was constructed using the yfinance library to extract a random sample of NASDAQ-listed companies' financial statement data, including revenue, net income, total debt, as well as other key indicators. After cleaning and integrating the two datasets, we explored the relationships between a company's stock performance and financial health by investigating questions related to volatility, profitability, capital structure, and predictive modeling of stock trends. 

<b> Folder/File Structure: </b>
There are two folders in this repository: Data and Code. As the name suggests, the Data folder houses all of the data used in our analysis--ranging from the raw dataset scraped from [Nasdaq's Stock Screener](https://www.nasdaq.com/market-activity/stocks/screener?page=1&rows_per_page=25) to our final, cleaned dataset. The Code folder stores the code used to clean and integrate the data as well as answer our research questions. 

<b>  File Table of Contents: </b>
| Folder | File | Description | 
| ------ | ---- | ----------- |
|  Code  | nasdaq_scraping.ipynb | Code used to scrape stock information from Nasdaq's Stock Screener |
| Data | nasdaq_final.csv | CSV of the 6,561 scraped nasdaq stocks and their information (last sale, market capitalization, etc.) |
| Code | fin_stmts.ipynb | Code used to download financial statement data (using yfinance library) for a random sample of nasdaq stocks | 
| Data | fin_stmts.csv | CSV of the randomly sampled stocks and their key financial indicators (revenue, debt, net income, etc.) |
| Code | final_data.ipynb | Code used to integrate and clean nasdaq_final.csv and fin_stmts.csv |
| Data | final_data.csv | Final dataset used for analysis |
