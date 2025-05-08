# Data Wrangling Project 

<b> Project Background: </b> 

The motivation for this data wrangling project stems from a desire to better understand the relationship between a company's financial position and its market position. By compiling and analyzing key financial metrics--such as revenue, net income, and total debt--alongside market characertistics like current stock price, historical stock prices, and market capitalization, our team sought to make sense of how the financial story told by a company's 10-Q was reflected in the market. We aimed to produce insights that could benefit both a company's managemenet and the everyday investor. Understanding how financial metrics relate to stock price can help management in their cost-cutting initiatives and the framing of their earnings announcements, and it can help investors in their stock selection, asset allocation, and risk management practices. To guide our analyses, our team focused on answering the following research questions: <br>

<i>Question 1:</i>

<i>Question 2:</i> How does the average stock price vary for companies grouped by their profitability?

<i>Question 3:</i>

<i>Question 4:</i>

<b> Folder/File Structure: </b>
There are two folders in this repository: Data and Code. As the name suggests, the Data folder houses all of the data used in our analysis including the dataset scraped from [Nasdaq's Stock Screener](https://www.nasdaq.com/market-activity/stocks/screener?page=1&rows_per_page=25), the dataset of company financial metrics and stock price history, and our final, cleaned dataset. The Code folder stores the code used to produce these datasets as well as answer our research questions. 

<b>  File Table of Contents: </b>
| Folder | File | Description | 
| ------ | ---- | ----------- |
|  Code  | nasdaq_scraping.ipynb | Code used to scrape stock information from Nasdaq's Stock Screener website |
| Data | nasdaq_final.csv | CSV of the 6,561 scraped nasdaq stocks and their information (ticker, last sale, market capitalization, etc.) |
| Code | yfinance_data.ipynb | Code used to download and merge financial statement data (using yfinance library) and historical price history for a random sample of Nasdaq stocks | 
| Data | yfinance_data.csv | CSV of the randomly sampled stocks, their key financial indicators, and their historical price history|
| Code | final_data.ipynb | Code used to integrate and clean nasdaq_final.csv and yfinance_data.csv |
| Data | final_data.csv | Final dataset used for analysis |
| Code | project_analysis.ipynb | Code used to conduct analysis and answer research questions | 
