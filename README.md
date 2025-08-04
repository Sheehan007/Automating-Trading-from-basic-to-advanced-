# Automating-Trading-from-basic-to-advanced-
This GitHub repository is about my journey on learning how to automate trade on a paper account from Alpaca. I will be updating everything here as I keep learning. 

INDEX
1. Trading-1: buying a share via Python code
Description: I created a paper trading account on Alpaca. Downloaded the API on my PC and started writing code. Tried buying one share but didn't realize that it was already 2am here (I'm kinda zone-out sometimes hehe). The order didn't execute but the code ran without any errors and the latter one shows that the market is closed as well.
EDIT: Logged in the next day and was able to buy 6 shares of Apple (AAPL) and 3 shares of Meta (META)

2. Trading-2: Optimizing the already made trading startegy. In this part, I have used a very important library for stock analysis in Python named "Technical Analysis". It can be donwloaded using 'pip install ta' command.
I applied RSI (Relative Strength Index) indicator, it is the most commonly used momentum indicator used in technical analysis. It is a momentum oscillator that is used to identify the oversold and the overbought stocks It was developed by John Welles Wilder Jr. It measures the speed and magnitude of recent price changes. 

[It is suggested that you read more about this on trusted websites like Investopedia, etc.]

> **Formula: RSI=100−(100/1+RS)**  
[where RS (Relative Strength) = average gain over a specified period/average loss over the same period]


3. Trading-3: Visualization. It is very important to interpret the changes that we are committing! Hence, I decided to plot five graphs that will help us visualize market data and trading performance. Each graph focuses on a different aspect of market data or trading strategy. The five graphs are:
   
      i. Candlestick Chart with RSI: Displays stock price movements (OHLC) and RSI signals for a symbol, highlighting buy/sell signals for the momentum strategy.
   
     ii. Portfolio Equity Curve: Shows the portfolio’s value over time, useful for evaluating trading performance and showcasing optimization skills.
  
    iii. Drawdown Plot: Visualizes maximum drawdowns to assess risk, critical for quant finance and risk management.
 
     iv. Pairs Trading Spread and Z-Score: Plots the price spread and z-score for AAPL/MSFT pairs trading, emphasizing cointegration and statistical arbitrage.
  
      v. Volume and Volatility Plot: Displays trading volume and rolling volatility to identify market activity, supporting data-driven approach.    

[WILL KEEP UPDATING.. ]

INDEX for DOCS:
1. Basics of Quantitative Trading: 
This doc includes all the basics of Quant trading that you would need to understand the history, and ideology behind the advent of Quant Trading. In addition, you will also be able to understand the complex programs and strategies that quants deploy to trade in millisecond time ranges (also called HFT quants), etc.    

Resources used:
1. Python for Finance by Yves Hilspich
2. 
