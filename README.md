# Key Cryptocurrencies: Bitcoin, Ethereum, Binance Coin (2020-2024)  

__*Project Overview*__    

This project analyzes the price trends, correlations, and patterns of three major cryptocurrencies—Bitcoin, Ethereum, and Binance Coin—from 2020 to 2024. Key aspects include examining price volatility, identifying trends, exploring seasonality and monthly patterns, and forecasting future prices. The study also investigates the interdependence of these cryptocurrencies and their stability during significant economic events. The insights provided aim to enhance understanding of the dynamics and relationships in the cryptocurrency market.  
The survey data, sourced directly from the site https://binance.com      
Binance is an online exchange where users can trade cryptocurrencies. It is the world's leading cryptocurrency exchange, catering to 235 million registered users in over 180 countries.   

💡 For an overview of *key cryptocurrency terms and concepts*, please refer to the [Intro to Cryptocurrencies](Intro%20to%20Cryptocurrencies%20README.md)   

### Goals    
1.	*Analyze Price Volatility:*  Explore fluctuations in cryptocurrency prices to understand market dynamics.  
2.	*Examine Correlations:*  Investigate Correlations between Bitcoin, Ethereum, and Binance Coin.    
3.	*Identify Trends:*  Study historical data to uncover long-term growth, decline, and stability patterns.  
4.	*Compare Average Prices:*  Evaluate and compare the mean values of the three cryptocurrencies.  
5.	*Detect Seasonality and Forecast:*  Identify recurring patterns and predict future price trends.  
6.	*Assess Cross-Impact:*  Analyze how the performance of one cryptocurrency affects others.  
7.	*Study Economic Event Impact:*  Understand price stability during major global events.
   
*This project delivers a well-rounded analysis of key cryptocurrency dynamics from 2020 to 2024.*  

### Tools Used   

**Programming Language**:  
-Python.  

**Python Libraries**:  
-requests  
-pandas, numpy  
-statsmodels (including scipy.stats)  
-seaborn, matplotlib  
-sklearn.linear_model  
-prophet  

 **Statistical Methods and Techniques**:  
-F-Test  
-Pearson Correlation Coefficient  
-Linear Regression  
-ANOVA  
-Facebook Prophet (Time Series Forecasting)  
-Granger Causality Analysis  
-T-Test.  

💡 For detailed information on the *statistical methods and approach* used in this analysis, see [Statistical Methods and Analytical Approach](Statistical%20Methods%20and%20Analytical%20Approach.md)   

### Files and Folders      
🐍 [Python Analysis](python/README.md): Statistical analysis and visualizations.   
📈 [Excel Data](excel/README.md): Raw data, processed data.   
🔍 [Images for visualisation](images/README.md)   

*Each folder contains a README file that provides a description of its contents.*  

### Key Findings 🔬  

**Price Volatility Across Cryptocurrencies:**  

-Bitcoin exhibits significantly higher volatility compared to Ethereum and Binance Coin, making it more appealing for short-term trading strategies.  
-Ethereum's lower variance reflects its widespread adoption in decentralized finance (DeFi) and smart contracts, indicating it may be less speculative than Bitcoin.  
-Binance Coin's relative stability positions it as a "safer" option for diversification, appealing to risk-averse investors.  
-Roles: Bitcoin as a speculative "store of value," Ethereum as a utility-focused blockchain, and Binance Coin as an ecosystem token.  

**Correlation Between Cryptocurrencies:**  

-Ethereum and Binance Coin have an exceptionally high positive correlation (0.918), reflecting a close relationship in their market movements.  
-Bitcoin's price movements strongly influence both Ethereum and Binance Coin, highlighting Bitcoin's anchoring role in the cryptocurrency market.  
-Shared involvement in DeFi and overlapping user bases contribute to the high correlation between Ethereum and Binance Coin.  

**Trend Analysis:**  

-Bitcoin's price shows the fastest upward trend, increasing by approximately $24.93 per day on average.  
-Ethereum's prices rise moderately, with an average daily increase of $1.22.  
-Binance Coin exhibits the slowest growth, with an average daily increase of $0.25.  
-Bitcoin's steep growth trajectory underscores its dominant position and increasing valuation in the market.  

**Comparing Average Prices:**  

-Bitcoin has the highest average price ($36,304.24) and a significantly wider price range than Ethereum ($1,981.85) and Binance Coin ($306.70).  
-Ethereum's average price reflects moderate variability, while Binance Coin demonstrates the smallest price range among the three.  

**Seasonality and Monthly Patterns, Forecasting:** 

-All three cryptocurrencies exhibit a long-term upward trend over the next year, as forecasted by the Prophet model.  
-Seasonal patterns and periodic dips suggest market behavior influenced by recurring factors such as market cycles or investor sentiment.  
-Forecasts for early 2026:  
• Bitcoin: $150,000–$160,000  
• Ethereum: $5,000–$6,000  
• Binance Coin: $1,200–$1,400  
-Forecasts indicate significant growth potential but remain subject to real-world market conditions.  

*🔍Below is a 1-year Price forecast for Bitcoin, Ethereum, and Binance Coin (created in Python)*    

<img src="images/Cryptocurrency%20Price%20Forecast%20(365%20days).png" alt="1-year Price forecast for Bitcoin, Ethereum, and Binance Coin" width="500" high="700"/>    

💡 For more details:  
🐍Python: *"Cryptocurrencies"*  

**The impact of cryptocurrencies on each other:**  

-Bitcoin exerts the most influence, driving price movements in both Ethereum and Binance Coin.  
-Ethereum impacts Bitcoin and Binance Coin at higher lags, indicating delayed market responses.  
-Binance Coin reacts to Bitcoin and Ethereum but does not significantly predict their prices.  
-Lagged relationships suggest market psychology and external factors influence delayed responses, particularly for Binance Coin.  

**Price Stability During Economic Events:**   

-Major global events, such as the COVID-19 pandemic, significantly increased volatility across all three cryptocurrencies.  
-Economic uncertainty during such events drives market fluctuations due to shifts in investor sentiment and risk perception.  
-*COVID-19 Crisis (2020):*  
The pandemic triggered a sharp, short-term market crash followed by a rapid recovery. This rebound was driven by macroeconomic factors such as global stimulus measures and rising demand for digital assets.   
-Bitcoin Halving:  
The halving events typically lead to gradual price increases and heightened speculative interest due to reduced supply. Between 2020 and 2024, this evolution reflects a shift in market dynamics, with cryptocurrencies becoming more integrated into the global financial system.  

*🔍Below is a Visualisation (created in Python) - Daily percentage change in prices for Bitcoin, Ethereum, and Binance Coin during May 2020*    

<img src="images/Daily%20Percentage%20Change%20of%20Cryptocurrencies%20(May%202020).png" alt="Line Plot showing Daily Percentage Change of Cryptocurrencies (May 2020)" width="600"/>    

💡 For more details:  
🐍Python: *"Price Stability During Economic Events"*  


-*Ethereum’s London Upgrade:*  
The upgrade positively impacted Ethereum’s long-term price trend by addressing key concerns related to transaction costs and supply dynamics.  
-*China’s Cryptocurrency Crackdown:*  
The market demonstrated strong adaptability. Despite an initial price drop, cryptocurrencies recovered as mining activity shifted to other regions. This event highlighted the increasing decentralization of the crypto ecosystem and its reduced reliance on any single country.  
-*Crypto Winter 2022:*  
During this period, Bitcoin’s volatility declined after the crash, while traditional assets like the S&P 500 and gold became more volatile. Interestingly, correlations between crypto and traditional assets strengthened, suggesting that increased correlation does not necessarily imply similar risk behavior. This provides valuable insight into portfolio diversification and risk management strategies.    

*🔍Below is a Line Plot (created in Python) for Bitcoin, S&P 500, and Gold daily percentage changes during the Crypto Winter*    

<img src="images/Bitcoin%2CSP500%2CGold%20Daily%20Percentage%20Changes%20During%20Crypto%20Winter%20(2021-2022).png" alt="Line Plot showing Bitcoin, S&P 500, and Gold daily percentage changes during the Crypto Winter" width="600"/>    

💡 For more details:  
🐍Python: *"Price Stability During Economic Events"*

**🧮 For the full report**, read the [Detailed Conclusions](Detaile%%Conclusions.md).   


### Broader Implications 🌍    

*Investment Strategies:*  
•	Bitcoin’s high volatility suits high-risk, high-reward investors, while Ethereum offers more stability and Binance Coin appeals to those prioritizing reduced risk.  
•	Portfolios can balance speculative assets like Bitcoin with more stable options like Ethereum and Binance Coin to mitigate risk.  

*Market Dynamics:*  
•	The cryptocurrency market operates as a single ecosystem, with Bitcoin as the anchor driving the movements of Ethereum and Binance Coin.  
•	Ethereum and Binance Coin show strong correlation, likely influenced by their shared roles in DeFi.  

*Forecasting and Seasonal Insights:*  
•	Long-term forecasts predict significant growth for Bitcoin, Ethereum, and Binance Coin by early 2026, with seasonal patterns highlighting opportunities for market timing.  
•	Recurring dips and cycles indicate the influence of external events and market sentiment on cryptocurrency trends.  

*Global Events Impact:*  
•	Major events like the COVID-19 pandemic amplify cryptocurrency volatility, emphasizing their dual role as speculative assets and potential alternatives during market stress.  
•	Price stability in the cryptocurrency market remains highly sensitive to global economic events. During turbulent periods, Bitcoin's volatility may decline, while traditional assets like the S&P 500 show increased fluctuations. Gold, by contrast, continues to serve as a relatively stable safe-haven. This evolving dynamic highlights how cryptocurrencies are becoming more interconnected with traditional markets, yet still retain unique behavioral patterns.

*Key Takeaways:*  
•	Bitcoin dominates as a speculative "store of value," Ethereum excels in utility-driven applications, and Binance Coin provides stability through its ecosystem.  
•	Understanding these dynamics helps investors optimize portfolios and capitalize on the interconnected cryptocurrency market.  

## How to Access  
📂 [GitHub Repository](https://github.com/Iryna-Bo/Key-Cryptocurrencies-Bitcoin-Ethereum-Binance-Coin-2020-2024-)    

### License   
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Iryna-Bo/Key-Cryptocurrencies-Bitcoin-Ethereum-Binance-Coin-2020-2024-/blob/main/LICENSE) file for details.
