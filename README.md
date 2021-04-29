## 1. Introduction

In this project, we are seeking answers to the question: 


* Does the incorporation of the CBOE Volatility (VIX) index improve performance of Bollinger Band based mean reversion trading strategy? 

To answer the question, we propose two methodologies. 

1. The first explores a multivariate time series: the mean-reverting time series of historical intraday equity (ETF) prices and the intraday VIX index values. 
    - If the linear combination of the two time series are cointegrated, we will explore further using Vector Error Correction Model (VECM). 
    - If no cointegration relationship is found, we will consider lagged data using Vector AutoRegression (VAR) Model. 
         
2. Secondly, we will build what we call a cointegrated Bollinger band using the linearly combined data.

Our data from Refinitiv DataScope is 2-year 15-second dataset; between January 1, 2019, and December 31, 2020; of the SPDR S&P 500 (SPY) ETF and the Chicago Board of Exchange (CBOE) Volatility (VIX) Index, . The dataset includes the Open, High, Low, Close prices, as well as the Volume.


## 2. Data Analysis

We did our data analysis using `Python 3.8.1`  on `Jupter Notebook`
 
 * **Required packages** 
  
      Python Packages used are: 

        - `numpy`
        - `Pandas`
        - `Matlabplot`
        - `Scklearn`
        - `Seaborn`
        - 
## 3. GitHub Files
* Analysis_xxxxxx.ipynb
    - Jupyter Notebook with python codes used in our data analysis.
   
## 4. Conclusion

