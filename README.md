Candlestick Pattern Recognition: A Viable Algorithmic Technique for Amateur TradingView Users?
An AP Research paper that builds and backtests a multi-indicator trading algorithm in TradingView's Pine Script (v6).

Research question: To what extent does a candlestick pattern recognition, sentiment-proxy indicator, and support/resistance algorithm provide an effective trading strategy for retail investors on the AAPL daily time frame?

Short answer: It didn't. The strategy lost money and badly trailed buy-and-hold. The paper covers the design, the full results, and my analysis of what went wrong.

Strategy: candlestick pattern recognition combined with a Fear & Greed-style sentiment proxy and a support/resistance filter, with an ATR-based trailing stop
Asset / timeframe: AAPL, daily, 2007 to 2020
Platform: TradingView (Pine Script v6), using its free data

Over the test period the strategy made 86 trades and finished with a net profit of -40.90%, funnily far behind buy-and-hold.

The paper received a top score and is used as an exemplar for incoming AP Research classes.
