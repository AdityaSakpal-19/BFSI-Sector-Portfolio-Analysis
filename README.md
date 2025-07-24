# 📊 BFSI Sector Portfolio Optimization using Python

This project explores top BFSI (Banking, Financial Services, and Insurance) stocks using Python libraries to identify the **best 2-stock portfolio** based on **Sharpe Ratio**, **correlation**, and **efficient frontier** analysis.

## 🔍 Objective
To determine the most efficient BFSI stock combination by:
- Analyzing stock trends and correlations
- Calculating risk-return metrics
- Applying portfolio optimization techniques

## 📈 Key Insights
- **ICICI Bank** and **State Bank of India (SBIN)** offer the **best risk-adjusted returns**
- Portfolio optimization yields:
  - 📈 **Expected Return**: 27.7%
  - ⚠️ **Volatility**: 21.8%
  - ⭐ **Sharpe Ratio**: 1.27
- Efficient frontier confirms this as the optimal portfolio

## 📊 Methodology
1. Fetch historical data using `yfinance`
2. Visualize price trends and correlation heatmap
3. Calculate daily returns, volatility, and Sharpe Ratio
4. Optimize portfolio using `PyPortfolioOpt`
5. Plot efficient frontier

## 🛠️ Tech Stack
- Python
- `yfinance`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `PyPortfolioOpt`
