# Python Analysis

This section contains Jupyter Notebooks that provide detailed analysis and visualizations using Python.   

## Files  

- `Cryptocurrencies.ipynb`
    
  *CONTENT*:
### 1. Price Volatility Across Cryptocurrencies.  
   1.A Calculate daily percentage changes for Bitcoin, Ethereum, and Binance Coin.  
   1.B Perform an F-test to compare variances.  
   1.C Visualize the daily percentage changes for all cryptocurrencies on the graphs.  
### 2. Correlation Between Cryptocurrencies.  
   2.A Compute the Pearson correlation coefficient between Bitcoin, Ethereum, and Binance Coin prices.  
   2.B Create a heatmap.  
### 3. Price Trend Analysis.  
   3.A Perform linear regression with time as the independent variable and currency prices as the dependent variables.  
   3.B Visualisation.  
### 4. Comparing Average Prices.  
   4.A Perform one-way ANOVA to compare the means of Bitcoin, Ethereum, and Binance Coin prices.  
   4.B Calculate Mean for each cryptocurrency.  
   4.C Boxplots to compare the distributions of cryptocurrency prices.  
### 5. Seasonality and Monthly Patterns, Forecasting.  
   5.A Group prices by month and check for significant differences.  
   5.B Create individual plots for each cryptocurrency.  
   5.C Use Facebook Prophet and plot 1-year forecast for Bitcoin, Ethereum, and Binance Coin.  
### 6. The mutual Impact of Cryptocurrencies on each other.  
   6.A Use Granger causality to determine if currencies affect each other.  
   6.B Scatterplot.    
   
- `Price Stability During Economic Events.ipynb`

  *CONTENT*:  
### 1. COVID-19:    
   1.A. Compare volatility during specific periods (e.g., COVID-19 in 2020).  
   1.B. Visualisation for each of currencies.  
### 2. Bitcoin Halving. Impact on Cryptocurrency Markets.:  
   2.A. Bitcoin Halving on May 11, 2020. Daily percentage change in prices for Bitcoin, Ethereum, and Binance Coin during May 2020.  
        Visualisation for each currency.  
   2.B. Comparison of Pre-Halving Periods (2020 vs. 2024). Pre-halving 2020 vs. 2024 analysis, emphasizing price volatility.  
        2.B.1. Statistical summaries for Bitcoin, Ethereum, Binance Coin, trend visualizations for Bitcoin.  
        2.B.2. Pre-Halving Periods Analysis (2020 vs. 2024) for Bitcoin. Daily percentage changes. Outliers - "Black Thursday".  
        90 Days Pre-Halving: price and percentage changes. Visualisations.  
   2.C. Comparisons between the impacts of Halving and COVID-19.  
### 3. Ethereum's London Upgrade (EIP-1559) in August 2021.  
   3.A. Price Trend Analysis (pre and post upgrade). Visualisation.  
   3.B. Volatility (Price Fluctuation) Comparison.  
   3.C. T-test to compare Price Behavior before and after the upgrade.  
### 4. China's Crackdown on Cryptocurrencies (2021-2022) - Starting in 2021  
   4.A. Standard deviation of daily percentage changes for both pre- and post-crackdown periods.  
   4.B. T-test.  
   4.C. Compare Bitcoin's price changes to Ethereum and Binance Coin.  
### 5. Crypto Winter 2022.  
   5.A. Gather Data for SP500.  
   5.B. Gather Data for Gold (Gold ETF).  
   5.C. Prepare Data for Bitcoin.  
   5.D. Merge data for S&P 500, Gold and Bitcoin by date.  
   5.E. Compare the volatility of cryptocurrencies with traditional assets.  
   5.F. Broad Comparison: January 2021 – October 2021 vs. November 2021 – December 2022.   
        Visualisations(interactive histogram and a distplot in Plotly).  
   5.G. Focused Analysis of the Crash: November 2021 – April 2022 vs. May 2022 – October 2022.   
        Visualisations(interactive histogram and a distplot in Plotly).  
   5.H. Correlation between cryptocurrencies and traditional markets before and during the Crypto Winter (Broad and focused comparison).  
   5.I. Visualisations. Using interactive Scatter plot, 3D Scatter plot, Correlation Hitmap, Bubble Chart.   
