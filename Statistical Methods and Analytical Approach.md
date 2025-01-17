# Statistical Methods and Analytical Approach  

*In this project, a variety of statistical methods and techniques were applied to uncover insights into the price dynamics, interrelationships, and future trends of Bitcoin, Ethereum, and Binance Coin.   
These methods were selected for their relevance to cryptocurrency analysis, enabling a deeper understanding of volatility, correlations, trends, and seasonality.*

__Data Exploration with describe():__  

• *Purpose:* The describe() function in Pandas was used to generate a statistical summary of the numerical data, providing an overview of key statistics such as mean, standard deviation, min, max, and quartiles.  
• *Application:* This initial step helped quickly identify basic trends, outliers, and potential issues with the data, ensuring the dataset was ready for further statistical analysis.  

__F-Test (Variance Analysis):__  

• *Purpose:* This test compares the variances between two or more groups.  
• *Application:* It was used in the project, for example, to assess price volatility differences between Bitcoin, Ethereum, and Binance Coin. For instance, it revealed Bitcoin's higher variance compared to Ethereum and Binance Coin, offering insights into their risk levels and market behavior.  

__Pearson Correlation Coefficient:__  

• *Purpose:* Measures the strength and direction of a linear relationship between two variables.  
• *Application:* Used to explore the correlation between Bitcoin, Ethereum, and Binance Coin. A strong positive correlation (0.918) was found between Ethereum and Binance Coin, suggesting a closely linked market dynamic influenced by similar drivers like DeFi adoption.  

__Linear Regression:__  

• *Purpose:* Linear regression models the relationship between a dependent variable and one or more independent variables.  
• *Application:* Time was used as the independent variable, with the prices of Bitcoin, Ethereum, and Binance Coin as the dependent variables. The regression analysis calculated the slope for each cryptocurrency, which helped quantify the rate of growth. 
For example, Bitcoin showed the steepest slope, indicating the fastest rate of price increase compared to the others.  

__ANOVA (Analysis of Variance):__  

• *Purpose:* ANOVA tests if there are statistically significant differences between the means of more than two groups.  
• *Application:* It was used to identify significant differences in mean prices across the three cryptocurrencies, highlighting Bitcoin’s dominance in price and Ethereum’s moderate yet consistent growth.  

__Facebook Prophet (Time Series Forecasting):__  

• *Purpose:* Facebook Prophet is a forecasting tool designed for time series data with missing values, seasonality, and holidays.  
• *Application:* It generated one-year forecasts for Bitcoin, Ethereum, and Binance Coin, projecting significant upward trends. The model revealed seasonal patterns and potential future price ranges.  
*Note: A SARIMAX model was also explored but proved to be computationally expensive and slow.*  

__Granger Causality Analysis:__  

• *Purpose:* This statistical method determines whether one time series can predict another.  
• *Application:* It was used to investigate lagged relationships between Bitcoin, Ethereum, and Binance Coin, revealing causal connections. This analysis allowed the project to explore whether price changes in one cryptocurrency "cause" changes in another.  

__T-Test (Comparison of Means):__  

• *Purpose:* This statistical test compares the means of two groups to determine if they are significantly different.    
• *Application:* In this project, for example, the t-test was used to analyze differences in the mean percentage changes (daily returns) of Ethereum prices before and after the London upgrade. The analysis revealed a statistically significant reduction in mean daily returns post-upgrade, suggesting the upgrade may have influenced price behavior. 

### Why These Methods Were Chosen  

*The combination of these statistical tools facilitated a thorough exploration of the price volatility, trends, and interrelationships between the three cryptocurrencies. Specifically, the methods allowed for:*  

- Identifying Variances and Risks: The F-Test identified volatility differences, offering insights for risk management and investment strategies.  
- Understanding Relationships: Pearson correlation and Granger causality uncovered interdependencies between cryptocurrencies, shedding light on how their price movements are linked.  
- Analyzing Trends: Linear regression and ANOVA helped clarify long-term growth trends, revealing Bitcoin’s dominance in price and Ethereum's consistent progress.  
- Predicting the Future: Facebook Prophet provided robust forecasting, essential for making informed long-term investment decisions.  
- Together, these methods enabled a comprehensive, data-driven analysis of the market behavior of Bitcoin, Ethereum, and Binance Coin from 2020 to 2024, offering valuable insights into their price volatility, trends, and interrelationships.
  
