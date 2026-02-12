![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)
![LSTM](https://img.shields.io/badge/Model-LSTM-green)

<h2>📈 Asset Price Prediction Using LSTM</h2>

A Deep Learning System for Multi-Interval Financial Market Forecasting

This project is a full-stack machine learning application that predicts future prices of financial assets such as stocks, cryptocurrencies, forex pairs, and commodities using LSTM (Long Short-Term Memory) neural networks.
The system integrates real-time data ingestion, technical analysis, risk analytics, and interactive visualization into a unified Streamlit dashboard.

<p align="center">
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7fe099ac-c548-4070-9158-6100e5f75ffa" />
</p>

<h2>🎯 Project Objectives</h2>

- ✔ Develop a robust LSTM model for multi-step financial time-series forecasting
- ✔ Support multiple assets and intervals (1h, 4h, 1d)
- ✔ Incorporate technical indicators for more stable predictions
- ✔ Provide real-time market risk analysis (Volatility, VaR, Sharpe Ratio, Drawdown)
- ✔ Build a user-friendly dashboard for traders, analysts, and researchers
- ✔ Maintain a modular, scalable codebase suitable for deployment and extension
- ✔ Cache data efficiently using SQLite to avoid redundant API calls
- ✔ Enable live visualization of past data, predictions, and confidence intervals

<h2>📌 Key Features</h2>
<h3>🔄 Dynamic Data Fetching</h3>

- Pulls the latest historical OHLCV data using yfinance

- Automatically updates based on the chosen asset and interval

- Uses SQLite caching to reduce network calls

<h3>🧠 LSTM-Based Price Prediction</h3>

- Trains a dedicated LSTM model per asset + time interval

- Predicts the next price and provides confidence bounds

- Computes evaluation metrics:

1. R² Score

2. MAE

3. RMSE
<h3>📦 Packages Used </h3>
- Pandas, Numpy
- Matplotlib, Seaborn, Plotly
- Scikit-Learn, StatsModel
- Tensorflow
- sqlalchemy, os 
- Streamlit

<h2>📊 Technical Indicators (ta / TA-Lib)</h2>

- Integrated indicators include:

- SMA / EMA (Simple/ Exponential Moving Average)

- RSI (Relative Strength Index)

- MACD ((Moving Average Convergence Divergence)

- Bollinger Bands

- Volatility

- Daily Returns

These features improve the model’s predictive capability beyond raw prices.

<h2>📉 Risk Metrics Dashboard</h2>

Real-time risk evaluation: Volatility (%), Sharpe Ratio, Maximum Drawdown, Value at Risk (VaR 95%)
<p align="center">
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/134dd375-ef54-4bbd-8314-930a72ee391f" />
</p>

<h2>📈 Interactive Visualization</h2>

- Built using Plotly + Streamlit, including:

- Historical price chart

- Future price predictions

- Confidence bands

- Indicator overlays

- Real-time metric cards
