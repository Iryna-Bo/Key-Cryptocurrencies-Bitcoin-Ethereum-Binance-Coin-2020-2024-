# Excel Data

This folder contains Excel files used in the analysis for the project "Key Cryptocurrencies: Bitcoin, Ethereum, Binance Coin (2020–2024)".  
The data in these files forms the basis for statistical computations, visualizations, and comparisons with traditional assets.  

## Files  

- `SP500.xlsx`: Daily closing prices of the S&P 500 index.  
  **Source**: [FRED - Federal Reserve Economic Data](https://fred.stlouisfed.org/series/SP500)
  
- `Gold_Prices_2021_2022.xlsx`: Historical prices of the SPDR Gold Shares ETF (GLD) from 2021–2022.    
  **Source**: Retrieved programmatically via the `yfinance` Python package using:  
  ```python  
  import yfinance as yf  
  gold = yf.Ticker("GLD")  
  gold.history(start="2021-01-01", end="2022-12-31")     
