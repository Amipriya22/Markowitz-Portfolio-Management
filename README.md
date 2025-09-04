# Markowitz Portfolio Management

This project applies the principles of Markowitz Portfolio Theory to construct an optimized equity portfolio from NIFTY 50 stocks. The objective was to achieve a target return while minimizing risk through diversification and quantitative analysis.

---

## Objective

- Implement Markowitz Portfolio Optimization using Python.
- Evaluate the optimized portfolio against the NIFTY 50 benchmark.
- Identify high-return, low-risk stocks using historical data and simulation techniques.

---

## Assignment 1 – Stock Screening

- Processed NIFTY 50 stock data (01/01/2016 – 31/12/2020) using NumPy and Pandas.
- Calculated key metrics: Volatility, CAGR (Compounded Annual Growth Rate), and Sharpe Ratio.
- Selected the top 15 stocks with the highest Sharpe Ratios to maximize return per unit of risk.

---

## Assignment 2 – Portfolio Optimization

- Initialized 600,000 random weight combinations for the selected 15 stocks.
- Computed Expected Return (equal to CAGR), Volatility, and Sharpe Ratio for each portfolio.
- Identified the portfolio with maximum Sharpe Ratio and visualized results using Matplotlib.
- Plotted the Efficient Frontier using the SLSQP optimization method.
- Allocated ₹1,00,00,000 across stocks and calculated the number of shares to be held.

---

## Assignment 3 – Backtesting and Evaluation

- Backtested the optimized portfolio on data from 01/01/2021 to 30/06/2021.
- Scraped updated stock prices using Pandas DataReader from Yahoo Finance.
- Evaluated portfolio performance using the following metrics:
  - Total Return
  - Volatility
  - Beta
  - Sharpe Ratio
  - Jensen’s Alpha
  - Sortino Ratio
  - Treynor Ratio
- Compared results against the NIFTY 50 benchmark to assess relative performance.

---

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy (SLSQP)
- Yahoo Finance API

---

## Outcome

- Constructed a diversified portfolio with superior Sharpe Ratio and lower volatility than the benchmark.
- Demonstrated practical application of financial theory in portfolio construction and performance evaluation.

---

Project developed under the Science and Technology Council (SNT), IIT Kanpur – Semester II, 2020–21.
