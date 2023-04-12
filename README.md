# Analyzing-Stock-Performance-and-Building-a-Dashboard
Analyzing Stock Performance and Building a Dashboard [Achieved 100%]

<p align="center">
  <img width="150" height="150" src="https://github.com/Amertastic/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/main/Images/Python_Project_for_Data_Science.png?raw=true">
</p>

## Table of Contents

1) Navigating the Git Hub Repository
2) Executive Summary
3) Technologies and Libraries Used
4) Data Gathering
5) Evaluation

### Navigating the GitHub Repository

- Jupyter Notebooks: The main Jupyter Notebooks can be found in the Notebooks folder.
  - 01 Extracting Stock Data.ipynb
  - 02 Webscraping Financial Data.ipynb
  - 03 Extracting and Visualising Stock Data.ipynb
- README.md

### Executive Summary
This project involves working as a data scientist for a hedge fund to extract and analyze financial data for Tesla and GameStop. The aim is to create a dashboard to compare the price of the stock versus the profit for the hedge fund.

Historical share price and quarterly revenue reportings will be extracted using Python libraries and web scraping. BeautifulSoup will be used to extract data from HTML tables and convert it into a pandas DataFrame.

The dashboard will be built using Plotly for data visualization, which will help identify patterns or trends in the data. By analyzing the data, we can determine if the company's profits are increasing, and if so, whether the stock price should increase.

The concept of short selling will also be explored in this project. Short selling is when an investor borrows a stock, sells it, and then repurchases it to return it to the lender. If the stock price decreases, the investor can make a profit. However, if the stock price increases, the investor can lose money. The case of Tesla and GameStop will be used as examples of short selling and its consequences.

### Technologies and Libraries Used

- Python
- Pandas
- BeautifulSoup
- Requests
- Plotly Dash
- Jupyter Notebook

### Data Collection Overview

To collect the necessary financial data for this project, we utilized web scraping and APIs to gather information on four stocks: Apple, Netflix, Tesla, and GameStop. We used the BeautifulSoup library to extract data from HTML tables and created a DataFrame for the Apple and Netflix stocks. This data was then visualized in a dashboard to identify patterns and trends, with key performance indicators displayed using Plotly for data visualization. For the historical stock prices of the Tesla and GameStop stocks, we extracted the data from Yahoo Finance using the yfinance library in Python.

### Dashboard Output

<p align="right">
  <img src="https://github.com/Amertastic/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/main/Images/GameStop%20Stock%20Graph.png">
</p>

<p align="left">
  <img src="https://github.com/Amertastic/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/main/Images/Tesla%20Stock%20Graph.png">
</p>
