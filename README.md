# Stock-Market-Analysis-Using-Python
Time-series stock market analysis and backtesting project using Python. Includes moving average crossover strategy, fixed risk–reward exits, trade-level performance metrics, and visualizations on HDFCBANK data.
# 📈 Stock Market Analysis Using Python

## 📌 Overview
This project performs time-series stock market analysis and backtesting using Python. A rule-based moving average crossover strategy is evaluated with predefined risk–reward constraints.

## 🎯 Objectives
- Analyze historical price trends
- Implement MA20–MA50 crossover strategy
- Apply fixed risk (₹500) and reward (₹1000) rules
- Backtest strategy performance
- Visualize equity curve and results

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- yFinance

## 📊 Strategy Logic
**Entry**
- Buy when MA20 crosses above MA50

**Exit**
- Stop-loss: ₹500 per trade  
- Target: ₹1000 per trade  
- Exit if MA20 crosses below MA50

**Capital per Trade**
- ₹5000

## 📈 Metrics Evaluated
- Total number of trades
- Win rate (accuracy)
- Total profit / loss
- Equity curve

## 📉 Data Source
- Yahoo Finance (HDFCBANK.NS)

## ⚠ Disclaimer
This project is for educational and analytical purposes only and does not constitute financial or investment advice.

## 🚀 Future Enhancements
- Add transaction costs & slippage
- Compare with Buy & Hold strategy
- Extend to multiple stocks
- Integrate results into Power BI
