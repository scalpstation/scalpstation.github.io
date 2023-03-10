---
title: "Screener"
date: 2023-03-09T21:21:19+03:00
weight: 2
---

The default screener displays 5m charts of 9 coins with a maximum range of 15 minutes. The timeframe can be set by selecting interval. Prices are updated directly from Binance, i.e. about the same as everywhere else. Volumes are about once every 10 seconds.

There is a markup on the charts:

![schreener chart](/screener-chart.png)

* Candlestick chart - main display tool
* Volume histogram - useful for confirmation of hypotheses and additional analysis
* Bollinger Bands - They can be used to see possible reversals in the sidewall and exits from it
* Yellow lines 3 percent above and below the current price - convenient for quickly assessing the scale of the chart and the potential for expected movement
* Red lines important levels - the algorithm for their calculation is not very easy to describe and it is still changing

There are several indicators above the graph:
* Price range 5 minutes [(max-min)/current*100]
* Price range 15 minutes
* Price range 1 hour
* Price range 3 hours
* Number of transactions on futures contracts
* Volume on futures contracts in USDT
* There are several sortings, in some cases they may be more useful:

![sorts select](/sorts-select.png)

* 5m - Price range in 5 minutes (in percent) - it is convenient to determine what is actively walking right now to catch
* 15m - Price range in 15 minutes (in percent)
* 1h - Price range in 1 hour (in percent) - it is convenient to determine what is actively walking
* 3h - Price range in 3 hours (in percent) - may be useful to someone
* DExt - Relative proximity to the daily maximum/minimum - you can try to catch the moment of approach on the breakdown or false breakdown of a fairly strong level
* trades - Number of trades in futures contracts in last 15 minutes - allows you to estimate where everyone is sitting right now
* gTrades - The increase in the number of transactions in last 5 minutes compared to 2 hours earlier - allows you to see an increase in transactions, and thus a possible trend in the near future
* volume - Volume of futures contracts in last 15 minutes in USDT - allows you to understand where the money is right now
* gVolume - Increase in volume in last 5 minutes compared to 2 hours earlier - allows you to assess the growth in volume and understand where traders are moving to
