# Portfolio Optimisation and Risk Analysis

## Overview

This project uses Python and financial mathematics to analyse historical stock performance, measure investment risk, and optimise portfolio allocations. It explores the relationship between risk and return using historical market data.

## Objectives

* Analyse historical stock returns and volatility.
* Examine relationships between assets using covariance and correlation.
* Construct and compare portfolios with different investment strategies.
* Minimise portfolio volatility through numerical optimisation.
* Identify the maximum-return and maximum-Sharpe-ratio portfolios.
* Visualise portfolio risk and return using the efficient frontier.

## Assets Analysed

* Apple (AAPL)
* Microsoft (MSFT)
* Amazon (AMZN)
* JPMorgan Chase (JPM)
* Coca-Cola (KO)

## Technologies

* Python
* pandas and NumPy
* Matplotlib
* SciPy
* yfinance
* Jupyter Notebook

## Methods

1. Download and prepare historical market data.
2. Calculate daily returns and annualised performance metrics.
3. Estimate covariance and correlation between assets.
4. Construct an equally weighted portfolio.
5. Optimise portfolio allocations under long-only constraints.
6. Compare minimum-risk, maximum-return, and maximum-Sharpe-ratio portfolios.
7. Simulate random portfolios and calculate the efficient frontier.

## Key Results

The equally weighted portfolio achieved an annualised historical return of **17.69%** and annualised volatility of **18.83%**.

The minimum-risk portfolio achieved an annualised historical return of **14.45%** and annualised volatility of **14.34%**.

The maximum-return portfolio allocated 100% to JPMorgan Chase, producing an annualised historical return of **27.68%** and volatility of **25.15%**.

These results illustrate the trade-off between portfolio return and risk. The maximum-return portfolio is concentrated in one asset, while diversification can reduce portfolio volatility.

## Visualisations

### Efficient Frontier

![Efficient Frontier](results/efficient_frontier.png)

### Cumulative Stock Returns

![Cumulative Stock Returns](results/cumulative_returns.png)

## Project Structure

```text
portfolio-optimisation/
├── data/
├── notebooks/
│   └── 01_data_exploration.ipynb
├── results/
│   ├── portfolio_comparison.csv
│   ├── optimal_weights.csv
│   ├── efficient_frontier.png
│   └── cumulative_returns.png
├── src/
├── README.md
└── .gitignore
```

## Limitations

* The analysis uses historical data, which does not guarantee future performance.
* The results depend on the selected assets and historical period.
* The optimisation assumes estimated returns and covariance are useful inputs for portfolio construction.
* Transaction costs, taxes, and changing market conditions are not modelled.

## Skills Demonstrated

Python programming, data analysis, statistical risk measurement, linear algebra, numerical optimisation, financial mathematics, data visualisation, and interpretation of quantitative results.

## Disclaimer

This project is for educational purposes only and does not constitute financial advice.