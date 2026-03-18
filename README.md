# Stock Portfolio Optimization

In this project, the Commercial Banking Corporation (the "Bank") seeks a recommendation of a portfolio with the following stocks: NVDA, GOOG, AVGO, AAPL, META, using the percent daily returns of the closing prices from January 2, 2025 through December 31, 2025. The Bank seeks to optimize the stock strategy to minimize the risk for a daily return rate of at least 0.18%.

To address this challenge, our team utilized Gurobipy to minimize the risk of the portfolio given the constraint of reaching a daily return rate of at least 0.18%. We found that the following allocation of resources resulted in the 0.18% return minimum risk (1.8%) portfolio: 19.66% in AAPL, 2.45% in AVGO, 69.1% in GOOG, 8.77% in META, and 0% in NVDA. We also created an efficient frontier to visualize the expected return for the accepted risk, which enabled us to develop high and low-risk portfolio options. The high-risk portfolio, with 0.225% daily returns and 2.63% risk is the following allocation: 66.17% in AVGO, and 33.83% in GOOG.

## Tools Used:
- Python
- numpy
- pandas
- yfinance
- matplotlib
- gurobipy
