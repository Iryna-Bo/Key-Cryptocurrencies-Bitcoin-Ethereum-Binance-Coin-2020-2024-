> **📌 TL;DR (Summary)**  
> • Analysis of Bitcoin, Ethereum, and Binance Coin from 2020–2024  
> • Visualizations, forecasting, and global economic event impact  
> • Includes comparisons to S&P 500 and Gold for portfolio diversification insights    

---      

# Key Cryptocurrencies: Bitcoin, Ethereum, Binance Coin (2020-2024)    

__*Project Overview*__    

This project analyzes the price trends, correlations, and patterns of three major cryptocurrencies—Bitcoin, Ethereum, and Binance Coin—from 2020 to 2024. Key aspects include examining price volatility, identifying long-term trends, exploring seasonal and monthly patterns, and forecasting future prices. The study also investigates the interdependence of these cryptocurrencies and their stability during significant economic events. The insights provided aim to enhance understanding of the dynamics and relationships in the cryptocurrency market.  
• Historical price data was collected from Binance.com using their public datasets and tools (https://binance.com)        
Binance, the world’s leading cryptocurrency exchange, serves over 235 million users across 180+ countries, offering a platform to trade a wide range of digital assets.  
To enrich the analysis with broader market context, the project also includes:  
• S&P 500 Index data sourced from the Federal Reserve Economic Data (FRED) database (https://fred.stlouisfed.org/series/SP500)  
• Gold ETF (GLD) data fetched via the yfinance Python package  
These financial indicators help assess how traditional assets performed alongside cryptocurrencies during key economic periods (e.g. COVID recovery, inflation spikes, 2022 crypto winter).  

💡 For an overview of *key cryptocurrency terms and concepts*, please refer to the [Intro to Cryptocurrencies](Intro%20to%20Cryptocurrencies%20README.md)   

### 🧮 Goals    
1.	*Analyze Price Volatility:*  Explore fluctuations in cryptocurrency prices to understand market dynamics.  
2.	*Examine Correlations:*  Investigate Correlations between Bitcoin, Ethereum, and Binance Coin.    
3.	*Identify Trends:*  Study historical data to uncover long-term growth, decline, and stability patterns.  
4.	*Compare Average Prices:*  Assess and compare the mean and distribution of prices across the three cryptocurrencies.    
5.	*Detect Seasonality and Forecast:*  Identify recurring patterns and predict future price trends.  
6.	*Assess Cross-Impact:*  Analyze how the performance of one cryptocurrency affects others.  
7.	*Study Economic Event Impact:*  Understand price stability during major global events.
   
*This project delivers a well-rounded analysis of key cryptocurrency dynamics from 2020 to 2024.*  

### Tools Used   

**Programming Language**  
• Python  

**Python Libraries**  
• requests  
• pandas, numpy  
• statsmodels, scipy.stats  
• seaborn, matplotlib  
• sklearn.linear_model  
• prophet  

**Statistical Methods and Techniques**  
• F-Test  
• Pearson Correlation Coefficient  
• Linear Regression  
• ANOVA  
• Facebook Prophet (Time Series Forecasting)  
• Granger Causality Analysis  
• T-Test  
 

💡 For detailed information on the *statistical methods and approach* used in this analysis, see [Statistical Methods and Analytical Approach](Statistical%20Methods%20and%20Analytical%20Approach.md)   

### Files and Folders      
🐍 [Python Analysis](python/README.md): Statistical analysis and visualizations.   
📈 [Excel Data](excel/README.md): Raw data, processed data.   
🔍 [Images for visualization](images/README.md)   

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

*🔍Below is a Heatmap - Correlation Between Cryptocurrencies (created in Python)*    

<img src="images/Correlation%20Matrix.png" alt="Correlation Between Cryptocurrencies" width="300"/>    

💡 For more details:  
🐍Python: *"Cryptocurrencies"*   

**Trend Analysis:**  

-Bitcoin's price shows the fastest upward trend, increasing by approximately $24.93 per day on average.  
-Ethereum's prices rise moderately, with an average daily increase of $1.22.  
-Binance Coin exhibits the slowest growth, with an average daily increase of $0.25.  
-Bitcoin's steep growth trajectory underscores its dominant position and increasing valuation in the market.  

**Comparing Average Prices:**  

-Bitcoin has the highest average price ($36,304.24) and a significantly wider price range than Ethereum ($1,981.85) and Binance Coin ($306.70).  
-Ethereum's average price reflects moderate variability, while Binance Coin demonstrates the smallest price range among the three.    

*🔍Below are the Boxplots - Comparison of the Distributions of Cryptocurrency Prices (created in Python)*    

<img src="images/Currency%20Price%20Distribution.png" alt="Boxplot comparing price distributions of Bitcoin, Ethereum, and Binance Coin" width="700"/>    

💡 For more details:  
🐍Python: *"Cryptocurrencies"*  

**Seasonality and Monthly Patterns, Forecasting:** 

-All three cryptocurrencies exhibit a long-term upward trend over the next year, as forecasted by the Prophet model.  
-Seasonal patterns and periodic dips suggest market behavior influenced by recurring factors such as market cycles or investor sentiment.  
-Forecasts for early 2026:  
• Bitcoin: $150,000–$160,000  
• Ethereum: $5,000–$6,000  
• Binance Coin: $1,200–$1,400  
-These forecasts suggest strong growth potential, but should be interpreted with caution due to the unpredictable nature of real-world market conditions.      

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
During this period, Bitcoin’s volatility declined after the crash, while traditional assets like the S&P 500 and gold became more volatile. Interestingly, correlations between crypto and traditional assets increased—highlighting that stronger correlations do not necessarily imply similar risk profiles. This provides valuable insight into portfolio diversification and risk management strategies.    

*🔍Below is a Line Plot (created in Python) for Bitcoin, S&P 500, and Gold daily percentage changes during the Crypto Winter*    

<img src="images/Bitcoin%2CSP500%2CGold%20Daily%20Percentage%20Changes%20During%20Crypto%20Winter%20(2021-2022).png" alt="Line Plot showing Bitcoin, S&P 500, and Gold daily percentage changes during the Crypto Winter" width="600"/>    

💡 For more details:  
🐍Python: *"Price Stability During Economic Events"*     


### Broader Implications 🌍    

*Investment Strategies:*  
• Bitcoin’s high volatility suits high-risk, high-reward investors, while Ethereum offers more utility-driven stability, and Binance Coin appeals to those prioritizing ecosystem-based reduced-risk exposure.  
• Portfolios can benefit from diversification—balancing speculative assets like Bitcoin with more stable or utility-oriented cryptocurrencies such as Ethereum and Binance Coin, alongside traditional assets like gold and the S&P 500, helps manage overall risk.    

*Market Dynamics:*  
• The cryptocurrency market functions as a connected ecosystem, with Bitcoin acting as the anchor asset influencing the broader market direction.  
• Ethereum and Binance Coin exhibit strong correlation, likely driven by their roles in decentralized finance (DeFi) and smart contract platforms.  
• Traditional markets, represented by the S&P 500 and gold, provide contrasting stability dynamics: the S&P 500 reflects broader economic sentiment and risk-on behavior, while gold continues to serve as a safe-haven during market stress.    

*Forecasting and Seasonal Insights:*  
• Long-term models suggest upward trends for Bitcoin, Ethereum, and Binance Coin through early 2026, despite short-term volatility.  
• Seasonal fluctuations and repeated market cycles reveal how investor psychology and macroeconomic shocks shape price behavior across both digital and traditional assets.  

*Global Events Impact:*  
• Major global disruptions — such as the COVID-19 pandemic and the 2022 “Crypto Winter” — have highlighted how both crypto and traditional assets react to uncertainty.    
• After the May 2022 crash, Bitcoin’s volatility decreased, while the S&P 500 and gold experienced increased fluctuations—yet the correlation between them and Bitcoin became stronger, suggesting closer financial market integration.  
• Gold continued to act as a reliable store of value during turbulent periods, while the S&P 500 mirrored broader economic sentiment and responded more strongly to fiscal and monetary policies.    
• Events like the Bitcoin halving led to gradual price appreciation due to reduced supply, while Ethereum's London Upgrade increased investor confidence by addressing key transaction and supply issues.  

*Key Takeaways:*  
• Bitcoin dominates as a speculative “store of value,” Ethereum excels in smart contract utility, and Binance Coin offers ecosystem-based stability.  
• The S&P 500 serves as a benchmark for risk assets in the traditional economy, while gold continues to offer consistent hedging benefits (i.e., helping protect investment portfolios against inflation, currency devaluation, or market crashes).    
• Understanding the evolving interplay between cryptocurrencies and traditional assets is essential for building resilient, diversified investment strategies, especially during periods of economic turbulence.     

## How to Access  
📂 [GitHub Repository](https://github.com/Iryna-Bo/Key-Cryptocurrencies-Bitcoin-Ethereum-Binance-Coin-2020-2024-)    

📫 For questions or suggestions, feel free to reach out via GitHub or [LinkedIn](https://linkedin.com/in/iryna-boiko-683aa3306)  

### License   
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Iryna-Bo/Key-Cryptocurrencies-Bitcoin-Ethereum-Binance-Coin-2020-2024-/blob/main/LICENSE) file for details.  
Feel free to use, modify, and distribute this project with proper attribution.    
