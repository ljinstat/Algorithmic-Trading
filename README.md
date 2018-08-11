# Algorithmic Trading
This is a project of my internship in BGFi Consulting, Paris. The topic of the internship is about algorithmic trading and its applications. Here are some strategies that I implemented in R, analyses about Bitcoin and application of Machine Learning for Bitcoin trading strategies.

## 1. Moving Average :
As basic trading strategies, moving averages are useful tools to indicate trends and momentums. In rmarkdown "Moving Average", simple moving average, exponential moving average, crossover strategy and Bollinger Bands are introduced.

## 2. Mean Reversion Test
For detecting mean reversion property, Augmented Dickey-Fuller test is used. The nul hypothesis is that the time series is not a trend-stationary series. In "reversion.pdf", the test is explained in mathematical way. I used R and Python to show the result. The document in Python is partly referred to an article in quantstart.com. *However, in the part of Hurst Exponent in this article, an expression is not related to mathematical formula.
In rmarkdown, I just showed a result of ADF.

## 3. Analyses about Bitcoin and Bitcoin trading strategies
Bitcoin can be related to fiat rates, oil prices and gold prices. According to my analyses, no special correlation exists. The price of Bitcoin associated to level of acception and number of users. Thus, many Bitcoin features like numbers of new adresses, hash rate, difficulty etc. are essential to analyse the potential trends of Bitcoin price.

Machine Learning methods such as SVM, Random Forest, neural networks are applied to build trading strategies. Also a time series strategy Hybrid ARIMA-GARCH is implemented. It outperforms Buy-and-hold strategy on the backtest (til January, 2017).
