# Pairs-Trading
## Implementing a Pairs Trading Algorithm on JPMorgan and Tesla Stock

This notebook explores the selection of a pair as well as how to trade them. Once a pair is selected, a cointegration test is applied to determine if there is truly a relationship between the two stocks. Once a relationship is determined, the trading model finds local extrema in the difference between the two stocks - at which positions can be opened. Positions are then closed when the stocks revert back to their mean. The stock that rises is shorted, betting that it will fall back to its mean. The stock that falls is longed, betting that it will rise back to its mean.   

<b>This repository contains the notebook (which has all the code and explanations), diagrams that help explain some of the concepts, and a csv file that contains the daily results of the trading simulation.</b>

### The trading algorithm acheives profit that is 27.1% of the money invested. The cointegration test proves cointegration with greater than 99% accuracy.
