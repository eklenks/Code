# Highlighted Work
* Portfolio Optimization: Capstone Finance Project for the CFA Society
* Backtesting Signals: Using trading signals, comparing returns vs SPX
* Statistical Cointegration: Stationarity tests, allocating between pairs

## Trading Systems
* Bond Program: long vs short bonds based on central bank rates

    Goal - Automated rotation between 4 positions (buy/sell, short/long term) given a projected short term rate schedule. If drawdowns are reduced, determine optimal leverage profile.
* Equity Program: long vs short tech basket based on spx rates (futures)

    Goal - Backtest buying 3-12 equities within the S&P 500 that are outperforming the overall index. Find optimal rotation periods between equities, given short and long term projected rates (yearly, quarterly, monthly rate). Projection incorporates 
* Cowboy Program: long vs short 1 day straddle positions (vol, imp vol)

    Goal - buy SPX straddles when implied volatility is high, sell a basket of straddles regularly. Incorporate earnings date arbitrage
* Hedging Program: Find ways to derisk the overall portfolio

    Goal - Incorporate low beta positions that reduce volatility of the portfolio (Gold, Bitcoin). Reduce positions into cash when volatility is high

## Econ folder
Work done under Uvic - linear algebra applications, large scale macro models.

### Notes
 Dataset from yfinance may be minimal and limited to daily prices

 Should work on incorporating systems with a brokers API / data

### Downloads 
If downloading for your terminal, use pip to install:

numpy, pandas, quantstats, yfinance, matplotlib