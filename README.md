# Portfolio Optimization using Python

This project explores portfolio optimization using **Modern Portfolio Theory (MPT)** and historical stock market data.

The goal is to identify optimal portfolio allocations that maximize return for a given level of risk.

## Overview

The notebook downloads historical price data for a set of stocks and simulates thousands of random portfolios to analyze their risk-return characteristics.

Using this simulation, we visualize the **efficient frontier**, which represents portfolios with the best possible expected return for a given level of risk.

## Stocks Used

- RELIANCE
- TCS
- HDFCBANK
- INFY
- ICICIBANK

Data is downloaded using the **yfinance** library.

## Tools & Libraries

- Python
- pandas
- numpy
- matplotlib
- yfinance

## Methodology

1. Download historical stock prices.
2. Calculate daily returns for each stock.
3. Compute mean returns and covariance matrix.
4. Generate thousands of random portfolio weight combinations.
5. Calculate portfolio return, volatility, and Sharpe ratio.
6. Plot the **efficient frontier** to visualize optimal portfolios.

## Output

The notebook generates a visualization showing:

- Expected portfolio return
- Portfolio volatility (risk)
- Sharpe ratio for each simulated portfolio

This helps illustrate how diversification affects portfolio performance.

## Key Concept

**Modern Portfolio Theory** suggests that investors can construct portfolios to maximize expected return based on a given level of market risk by optimally choosing asset weights.

## Future Improvements

Possible extensions for this project include:

- Adding more stocks and asset classes
- Identifying the portfolio with the **maximum Sharpe ratio**
- Including risk-free rate in Sharpe calculations
- Implementing optimization using `scipy`

## Author

Tanishka Saini  
BTech Student interested in fintech, quantitative analysis, and data-driven investing.
