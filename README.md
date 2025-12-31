# Trader Behavior Analysis Under Bitcoin Market Sentiment

## Overview
This project analyzes how **Bitcoin market sentiment (Fear & Greed Index)** influences **trader behavior, risk-taking and profitability** using historical trading data from **Hyperliquid**.

The objective is to uncover behavioral patterns that can help improve **trading strategies and risk management decisions** in crypto markets.

This analysis was completed **entirely in Python using Jupyter Notebook**.



## Objectives
- Understand how market sentiment impacts trader profitability
- Analyze risk behavior across Fear and Greed phases
- Compare Buy vs Sell behavior under different sentiment conditions
- Identify how top-performing traders adapt to market sentiment
- Derive actionable insights for smarter trading strategies



##  Datasets Used
1. **Bitcoin Fear & Greed Index**
   - Date
   - Classification (Fear, Extreme Fear, Greed, Extreme Greed)
   - Sentiment Score

2. **Hyperliquid Historical Trader Data**
   - Account-level trade data
   - Trade size, side (Buy/Sell), execution price
   - Timestamp
   - Closed P&L and related trade attributes



##  Tools & Technologies
- **Python**
- **Pandas & NumPy** – Data cleaning and feature engineering  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – End-to-end analysis and storytelling  



##  Key Analysis Performed
- Time-based data alignment and sentiment merging
- Feature engineering (profitability flags, risk buckets)
- Profitability and win-rate analysis by sentiment
- Trade size and risk behavior comparison
- Buy vs Sell behavior under Fear & Greed
- Top trader segmentation and performance comparison



##  Key Insights
- Traders tend to increase trade size during **Greed** phases, but this does not consistently lead to higher profitability.
- **Fear-driven markets** show fewer trades but higher win rates, indicating more disciplined execution.
- **Top-performing traders** adapt position sizing based on sentiment and avoid excessive risk during extreme market emotions.



##  Actionable Trading Strategies
- Use market sentiment as a **risk filter**, not a direct trade signal.
- Reduce position size during **Extreme Greed** phases.
- Focus on high-conviction setups during **Fear** phases.
- Avoid over-trading during sentiment extremes to control downside risk.



##  Limitations
- No order book or funding rate data available
- No macroeconomic or news-based sentiment included
- Analysis limited to historical trade data



##  Future Scope
- Integrate volatility metrics and funding rates
- Include on-chain indicators and macro sentiment
- Extend analysis to predictive or strategy backtesting models



##  How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Install required libraries (if not already installed)
4. Run all cells sequentially



##  Author
**Aditi**    
Dayananda Sagar College of Engineering, Bengaluru   
Data Analyst Intern  
**Linkedin** : www.linkedin.com/in/aditisrivastava14

