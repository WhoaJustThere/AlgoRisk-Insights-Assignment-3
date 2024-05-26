# AlgoRisk-Insights-Assignment-3
### Problem   
This problem would be our first attempt at coding a strategy based on technical indicators. We would backtest it on the NIFTY50 index from 2018-01-01 to 2024-01-01 with an initial capital of INR 1 Cr. Let's follow the instructions:  

+ We would represent a buy signal as 1 and a sell signal as -1; all other values should be 0, indicating we don't initiate a new order.
+ At the end of the trading period, we should not have any open trades, i.e., close all the open positions on the last day.
+ We will invest all our current capital in the market, considering that we can trade only in integer values and hold only one position at a time for this assignment.
+ We would then calculate the usual parameters like returns, maximum drawdown, shape ratio, and portfolio value to evaluate our strategy. Note that the maximum drawdown of a trade would be the maximum of all drawdowns in our portfolio when we had the position, and the maximum drawdown of the strategy would be the maximum of all such maximum drawdowns.
  

(a) Code a strategy using the MACD indicator; the crossover between the signal and the MACD line represents the buy or sell signals.  
(b) Code a strategy using the Bollinger Bands; note that you must ensure the signals are alternating since we can only have one open position at a time. Such care is not required in (a), though, why?  
(c) Incorporate the stop loss measure to limit your risks in the strategy. In other words, for a stop loss of x\%, if the price goes below x\% of our buying price for a long trade, we square off our position.   
(d) (Optional) Modify your code to make it a trailing stop loss. Take any parameters you may need as input.  
(e) (Optional) We learned about denoising our data using the Heikin-Ashi Candles. Generate signals from the HA candles and trade at the real closing prices. Compare the performance of your strategy in (a) and (b) with the denoised one.  

