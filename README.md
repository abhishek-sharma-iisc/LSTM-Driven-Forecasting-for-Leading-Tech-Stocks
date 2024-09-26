# LSTM-Driven-Forecasting-for-Leading-Tech-Stocks

# Stock Market Analysis using Fbprophet, AutoArima and LSTM

<img src="https://github.com/user-attachments/assets/08b84f54-14e2-4d2b-b0c0-4e93fc5aacc9" alt="image" width="800"/>

Time series data consists of data points indexed in chronological order. This type of data is ubiquitous, making its manipulation crucial for data analysts and data scientists.

In this notebook, we will delve into stock market data, focusing on technology giants such as Apple, Amazon, Google, and Microsoft. We will utilize the yfinance library to fetch stock information and employ Seaborn and Matplotlib for visualization. Additionally, we will analyze stock risk based on historical performance and predict future stock prices using Long Short Term Memory (LSTM) networks.

Throughout this notebook, we will address the following questions:

1) How has the stock price changed over time?
2) What is the average daily return of the stock?
3) What are the moving averages of the various stocks?
4) What is the correlation between different stocks?
5) What is the value at risk when investing in a particular stock?
6) How can we predict future stock behavio using Auto Arima?
7) How can we predict future stock behavio using Fbprophet?
8) How can we predict future stock behavio using LSTM? (<b>best performer</b>)

***   

## Getting the Data
The first step is to get the data and load it to memory. We will get our stock data from the Yahoo Finance website. Yahoo Finance is a rich resource of financial market data and tools to find compelling investments. To get the data from Yahoo Finance, we will be using yfinance library which offers a threaded and Pythonic way to download market data from Yahoo.
