# Momentum Trading Strategy (Python)

This project implements a simple momentum-based trading strategy using Python and historical stock data from Yahoo Finance.

## Strategy Logic

1. Download stock data using yfinance
2. Calculate daily returns
3. Compute 90-day momentum
4. Rank stocks by momentum
5. Invest in the top-performing stocks
6. Backtest portfolio performance

## Performance Metrics

The strategy evaluates performance using:

- Sharpe Ratio
- Maximum Drawdown
- Portfolio equity curve
- Comparison with NIFTY 50 benchmark

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance

## Example Output

The notebook generates:

- Portfolio growth chart
- Drawdown analysis
- Strategy vs NIFTY 50 comparison
## Strategy Overview

This project implements a  momentum strategy.

Stocks are ranked daily based on their 90day return.
The strategy invests in the top stocks and rebalances
the portfolio based on updated rankings.

Momentum is a well known factor in quantitative finance where
stocks that have performed well recently tend to continue
performing well in the short term.
## Author

Vaibhav
