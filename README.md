# Python-Project
TGameStop & Tesla Stock and Revenue Analysis Using Python

This project explores the historical stock performance and quarterly revenue trends of GameStop (GME) and Tesla (TSLA) using Python. The goal is to practice real-world data extraction, web scraping, data cleaning, and visualization using common data science libraries.

📌 Project Objectives

Extract stock price data using the yfinance library
Scrape revenue data from HTML tables using requests and BeautifulSoup
Clean and transform raw financial data into analysis-ready format
Visualize stock performance and revenue trends
Practice end-to-end data analysis workflow from data extraction to visualization

📂 Technologies Used

Python
yfinance (stock price extraction)
requests (downloading webpage source)
BeautifulSoup (bs4) (web scraping)
pandas (data cleaning & manipulation)
matplotlib (visualizations)
html5lib / html.parser (HTML parsing)

📊 Key Steps
1. Stock Data Extraction
Using the yfinance.Ticker function:
Created ticker objects for GME and TSLA
Extracted full historical datasets using period="max"
Reset index and stored values in DataFrames

2. Revenue Data Scraping
Downloaded target webpage using requests
Parsed HTML using BeautifulSoup
Located the appropriate revenue table
Extracted date and revenue values into DataFrames
Cleaned revenue values (removed commas, dollar signs, empty strings)

3. Data Cleaning
Converted dates to datetime format
Converted revenue to numeric values
Filtered data up to June 2021 for consistent comparison
Handled missing values

4. Data Visualization
Built the make_graph function to:
Plot stock closing prices over time
Plot quarterly revenue trends
Generate clear, readable, and visually aligned charts for each company
Charts demonstrate how stock prices and revenue evolved over time, especially during periods of high market volatility and growth.

📈 Final Visualizations
The project outputs two main graphs for each company:
Stock Price Over Time
Quarterly Revenue Over Time
These help showcase trends, spikes, and long-term performance patterns.

📦 Skills Demonstrated

✔ Web scraping
✔ Data cleaning and preprocessing
✔ Working with financial datasets
✔ Time-series data analysis
✔ Data visualization
✔ Python scripting and function creation
✔ Reproducing analysis from industry-relevant datasets

📁 Project Structure
project/
│── gme_stock_revenue_analysis.ipynb
│── tesla_stock_revenue_analysis.ipynb
│── README.md
│── requirements.txt

📝 Conclusion
This project demonstrates end-to-end data analysis skills suitable for real data analyst roles, including working with APIs, handling messy data, and producing meaningful visual insights. It is also a great foundation for more advanced financial analytics.
