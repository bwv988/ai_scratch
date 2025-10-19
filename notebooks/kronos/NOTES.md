# General notes

## Goal
We want to be able to leverage a forecasting model, such as Kronos, to realize small ($10) daily gains in BTC trades, on average. We are ok with not gaining anything, but want to deploy a conservative approach that ensures we are not incurring large losses, particularly in a downwards trending market.

## Building a trading agent

* What is the strategy?
* Is overestimating worse than underestimating? For example, having an actual close price of 9.8 vs. a predicted one of 10.4
* Need to factore in the cost of trades to understand overall profitability.