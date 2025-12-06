# Indian-Stock-Market-Analysis-and-Trend-Visualization

📊 ISE Market Analysis Using Python

A Data Science Project on Financial Time-Series Trends, Correlations & Volatility

📌 Overview

This project focuses on analyzing the Indian Stock Exchange (ISE) market using Python's data-science ecosystem.
The goal is to study stock price behavior, understand market trends, evaluate correlations, and measure volatility across selected companies.

Using Pandas, NumPy, Matplotlib, Seaborn, and yfinance, this project demonstrates core data-analysis techniques applied to real financial data.

🧰 Tools & Libraries Used
Tool / Library	Purpose
Python	Scripting, logic, data handling
NumPy	Moving averages, numerical computation
Pandas	Time-series analysis, returns, data cleaning
Matplotlib & Seaborn	Data visualization (line charts, heatmaps, bar plots)
yfinance API	Fetching real-time Indian stock data
📂 Project Workflow
1. Data Collection

Fetched OHLCV stock data from Yahoo Finance using yfinance.

Selected multiple ISE-listed companies over a range of years.

Loaded all data into Pandas DataFrames for further processing.

2. Data Cleaning & Preparation

Extracted Close or Adjusted Close prices.

Handled missing values and multi-index formatting (common when pulling multiple tickers).

Created aligned datasets for fair comparison.

3. Exploratory Data Analysis (EDA)

Inspected dataset structure using .head() and .describe().

Visualized overall closing price trends for all selected companies.

4. Technical Indicators: Moving Averages

Computed:

20-day Moving Average (Short-term trend)

50-day Moving Average (Long-term trend)

These indicators help identify upward/downward momentum and potential buy/sell signals.

5. Correlation Analysis

Calculated daily stock returns using pct_change().

Generated a correlation heatmap to understand how each stock moves relative to others.

Useful for diversification and risk-reduction decisions.

6. Volatility Assessment

Measured volatility using standard deviation of daily returns.

Compared which stocks are stable vs more risky.

📈 Key Visualizations

(These appear inside the notebook)

1. Closing Price Trends (Line Chart)

Shows how each stock behaved across the selected time period — growth, dips, volatility cycles, etc.

2. Moving Averages Plot

Overlay of price + MA20 + MA50, helping identify market momentum and trend reversals.

3. Correlation Heatmap

Color-coded matrix showing stock relationships:

High correlation → move together

Low correlation → good for diversification

4. Volatility Comparison

Bar or line chart showing risk levels across companies.

🧠 Insights & Findings

Stocks with higher volatility showed more aggressive price swings.

Strong correlations were observed among companies in similar sectors.

Moving averages provided clearer signals than raw price movements.

Visualization greatly simplified trend interpretation and comparison.

🎯 Why This Project Matters

This project demonstrates your ability to:
✔ Manipulate real-time financial datasets
✔ Perform meaningful exploratory data analysis
✔ Apply technical indicators used in financial markets
✔ Use Python for time-series analytics
✔ Present insights visually and clearly

This is a strong project piece for both GitHub portfolios and data-science interviews.

🚀 Future Enhancements

You can extend this project by adding:

Moving Average Crossover Strategy

RSI, MACD, Bollinger Bands

Forecasting models (ARIMA, Prophet, LSTM)

Interactive dashboard (Streamlit / Dash)

Live auto-updating data pipeline



🏁 Conclusion

This project showcases a complete workflow of financial data analysis — from collection to visualization to interpretation — using Python's most widely used data-science tools.

It serves as a strong demonstration of both technical ability and understanding of financial markets.
