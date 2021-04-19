## 1. Introduction
The practice of short term trading relies mainly on the entry and exit
signals of instruments calculated on smaller time frames and generally do
not consider long term trends.
The two most popular types of trading strategies, momentum trading and
mean reversion trading, are based on the trend of the price or return of
stocks. But we know that the market laws that influence demand and
supply vary depending on human interactions. Over the years, the trading
strategies developed have been based mainly on technical, financial and
economic indicators.

With the advancement of technology, and the proliferation of news and
social media, many traders have joined the market, adding to the liquidity
and volatility of the market. Secondly, the current atmosphere in many
Western countries with the rise of social and political movements, and
mob-investors such as Wallstreetbets, make for a complicated market
environment based on fear and greed. An investment atmosphere driven
by emotion reduces the efficacy and accuracy of common technical
indicators, and erodes profits. There is a need therefore to investigate the
impact and influence of human sentiment on short term trading.
To accomplish our aim, we think that the use of a combination of technical
indicators such as Bollinger Bands and Relative Strength Index (RSI), and a
proxy for market sentiment such as the CBOE Volatility (VIX) Index will be
useful for improving short-term exit and entry signal precision.
The VIX Index incorporates a “fear gauge” of the markets. A high VIX
indicates that investors are weary of the current market environment and
are purchasing insurance contracts to hedge their portfolios in the wake of
or during a drawdown. On the other hand, a low VIX suggests complacency
and that any movement in the stock market will be restrained. In that
sense we think of the VIX Index as a leading indicator which will inform the
short-term entry and exit signals.
For our project, we are going to seek answers to the question: does the
incorporation of the CBOE Volatility (VIX) index improve performance of
Bollinger Band based mean reversion trading strategy? We propose two
methodologies. The first explores a multivariate time series: the
mean-reverting time series of historical intraday equity (ETF) prices and the
intraday VIX index values. If the linear combination of the two time series is
cointegrated, we will use a Vector Error Correction Model (VECM). If no
cointegration relationship is found, we will consider lagging the data or
using a Vector AutoRegression (VAR) Model. Secondly, we will build what
we call a cointegrated Bollinger band using the linearly combined data.
Our project will use data from Refinitiv DataScope. We are working with
the 2-year 15-second dataset of the SPDR S&P 500 (SPY) ETF and the CBOE
Volatility (VIX) Index, between January 1, 2019, and December 31, 2020. The
dataset includes the Open, High, Low, Close prices, as well as the Volume.
For short-term trading, we are going to aggregate the data to acquire less
frequent data such as minute data based on our research.


## 2. Theoretical Framework
The literature surrounding short term trading is immense and varied. In
this part, we will review articles and papers, particularly with regard to
keywords and key works done in the area we are exploring. We will look at
contributions in the literature on the use of sentiment proxies as an
indicator and their contribution to the literature.
Things we looked at:
   1. Understanding the relationship between market sentiment, VIX and
trading signals
   2. Investigation of the literature on the development of the mean
reversion method for short term trading.
   3. Vector AutoRegression and Vector Error Correction Model.
   4. 
Sentiment analysis is a growing area of interest for financial analysts and
investors. Many ongoing researches especially in behavioral finance are
focused on understanding the impact of sentiments on retail and
institutional investors, and financial markets dynamics.
