# S&P 500 Momentum Trading Strategy
Sector-based momentum trading strategy developed using Python and historical S&P 500 equity data.

## Overview
This project analyzes momentum signals across S&P 500 stocks to identify high-performing equities within selected sectors. The strategy ranks stocks based on rolling 20-day returns and constructs portfolios using the top-performing stocks in each sector.

The project focuses on sectors including:
- Information Technology
- Industrials
- Consumer Discretionary

Portfolio performance is evaluated using historical return analysis and quantitative risk metrics.

## Features
- Momentum-based stock ranking using 20-day returns
- Sector-specific portfolio construction
- Historical portfolio performance tracking
- Correlation analysis
- Annualized volatility calculations
- Max drawdown analysis
- Sharpe ratio evaluation

## Tools & Libraries
- Python
- pandas
- NumPy
- matplotlib
- yfinance

## Data Source
Historical equity data was sourced using Yahoo Finance APIs through the `yfinance` library.

## Strategy Logic
1. Pull historical S&P 500 equity price data
2. Group stocks by sector
3. Calculate rolling 20-day momentum signals
4. Select top-performing stocks within each sector
5. Construct and evaluate portfolios using historical returns
6. Analyze portfolio performance and risk metrics

## Repository Structure
- `QFC_Momentum_Code.py` — Main strategy and analysis code

## Future Improvements
- Add automated portfolio rebalancing
- Incorporate transaction cost optimization
- Expand to additional factors beyond momentum
- Compare against benchmark indices such as SPY
- Implement more advanced backtesting frameworks

## Author
**Author:** Madalyn Wilson  
University of Arizona, Political Sceince and Economics  
Quantitative Finance Club  
LinkedIn: www.linkedin.com/in/madalyn-wilson113
