## 1. Introduction

In this project, we are seeking answers to the question: 


* Does the incorporation of the CBOE Volatility (VIX) index improve performance of Bollinger Band based mean reversion trading strategy? 

To answer the question, we propose two methodologies. 

1. The first explores a multivariate time series: the mean-reverting time series of historical intraday equity (ETF) prices and the intraday VIX index values. 
    i. If the linear combination of the two time series are cointegrated, we will explore further using Vector Error Correction Model (VECM). 
    ii. If no cointegration relationship is found, we will consider lagged data using Vector AutoRegression (VAR) Model. 
         
2. Secondly, we will build what we call a cointegrated Bollinger band using the linearly combined data.

Our data from Refinitiv DataScope is 2-year 15-second dataset; between January 1, 2019, and December 31, 2020; of the SPDR S&P 500 (SPY) ETF and the Chicago Board of Exchange (CBOE) Volatility (VIX) Index, . The dataset includes the Open, High, Low, Close prices, as well as the Volume.


## 2. Theoretical Framework
The literature surrounding short term trading is immense and varied. We reviewed articles and papers, particularly with regard to keywords and key works done in 
the area. We looked at contributions in the literature on the use of sentiment proxies as an indicator and their contribution to the literature.
Things we looked at:

   1. Understanding the relationship between market sentiment, VIX and trading signals
   2. Investigation of the literature on the development of the mean reversion method for short term trading.
   3. Vector AutoRegression and Vector Error Correction Model.
  
Sentiment analysis is a growing area of interest for financial analysts and investors. Many ongoing researches especially in behavioral finance are
focused on understanding the impact of sentiments on retail and institutional investors, and financial markets dynamics.
