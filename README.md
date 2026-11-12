# Black-Litterman Portfolio Optimization

Implementation of the Black-Litterman model to estimate expected asset returns by combining market-implied equilibrium returns with subjective investor views and confidence levels. The project integrates historical market data, covariance estimation, Bayesian return adjustments, and mean-variance optimization to construct a diversified portfolio.

**Key Features:**
- Historical stock price and market capitalization data retrieval using Yahoo Finance.
- Covariance matrix estimation using the Ledoit-Wolf shrinkage method.
- Calculation of market-implied equilibrium returns.
- Integration of absolute investor views and uncertainty estimates.
- Estimation of posterior expected returns and covariance matrix using the Black-Litterman framework.
- Portfolio optimization using the Efficient Frontier and Maximum Sharpe Ratio.
- Portfolio weight allocation and risk-return performance analysis.

**Technologies:** Python, NumPy, Pandas, Matplotlib, Seaborn, Plotly, yfinance, PyPortfolioOpt.
