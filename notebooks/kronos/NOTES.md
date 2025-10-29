# General notes

## Goal

We want to be able to leverage a forecasting model, such as Kronos, to realize small ($10) daily gains in BTC trades, on average. We are ok with not gaining anything, but want to deploy a conservative approach that ensures, we are not incurring large losses, particularly in a downwards trending market.

## Technical considerations



## Unsorted considerations

* What is the trading agent's strategy?
* Mean reversion
* Stop loss
* Is overestimating the close price worse than underestimating? For example, having an actual close price of 9.8 vs. a predicted one of 10.4
* Needs to factor in the cost of trades to understand overall profitability. More trades will drive up the cost. Are there limits?
* Also: Cost for accessing bot trading platforms.
* Are there bot frameworks that can be leveraged?
  