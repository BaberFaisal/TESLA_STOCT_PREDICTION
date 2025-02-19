# Tesla Stock Price Prediction Using LSTM

## Project Overview

This project uses **Long Short-Term Memory (LSTM)** models to predict **Tesla’s stock price** for the next day. The model is trained on **historical data** from **2015 to 2025** using data sourced from **Alpha Vantage API** or **Yahoo Finance**. Several **exploratory data analysis (EDA)** techniques like **Bollinger Bands**, **SMA**, and **monthly returns** were used to understand stock trends. The LSTM model is then trained and evaluated to predict future prices.

## Key Features

- **Data Collection**: Fetches **Tesla stock data** from **2015 to 2025**.
- **Exploratory Data Analysis (EDA)**:
  - **Stock Price Trend**: General trend of Tesla stock over time.
  - **Moving Averages (SMA)**: Analyzes short-term and long-term stock trends.
  - **Bollinger Bands**: Measures stock price volatility and helps identify overbought/oversold conditions.
  - **Stock Returns**: Daily fluctuations and trends in stock returns.
  - **Monthly Trends**: Analyzes Tesla stock performance across different months of the year.
- **LSTM Model**: 
  - Trains the model using **60 days of past stock data** to predict **next-day stock prices**.

Results
Prediction for the Next Day’s Tesla Stock Price: $249.21 (based on the latest 60 days of stock data).

The model's accuracy improves as it learns from more data. The predictions are based on historical trends, and the results can be used to inform trading decisions.

Conclusion
The model predicts Tesla’s stock price based on historical data, providing insights into possible future trends. The LSTM model demonstrates the effectiveness of machine learning for stock market predictions.
