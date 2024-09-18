# Highlighted Work
* Portfolio Optimization: Capstone Finance Project for the CFA Society
* Backtesting Signals: Using trading signals, comparing returns vs SPX
* Statistical Cointegration: Stationarity tests, allocating between pairs

## Trading Systems
* Bond Program: long vs short bonds based on central bank rates

    Automated rotation between 4 positions (buy/sell, short/long term) given a projected short term rate schedule. If drawdowns are reduced, determine optimal leverage profile.

* Equity Program: long only equity basket based on statistical projections

    Automated rotation between 3-12 equities within the S&P 500 that are outperforming the overall index. Find optimal rotation periods between equities, given short and long term projected rates (yearly, monthly). Reduces long positions when implied volatility is high

* Cowboy Program: infrequently trades low risk high reward opportunities

    Explores buying SPX straddles when implied volatility is high and arbitrage opportunities during earnings.

* Hedging Program: Derisking the overall portfolio

    Adds short positions in dynamic allocations (long only, 75,25%, 50/50) based on interest rates. Incorporates low beta positions to reduce volatility (Gold, Bitcoin)

## Econ folder
Work done under Uvic - linear algebra applications, large scale macro models, educational materials. 

### Notes
 Dataset from yfinance may be minimal and limited to daily prices

 Needs work on incorporating systems with a brokers API / data

### Downloads 
If downloading for your terminal, use pip to install:

numpy, pandas, quantstats, yfinance, matplotlib