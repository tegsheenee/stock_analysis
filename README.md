# 📌 Stock Exchange Trends Dashboard - Tableau
**📝 Overview**

This interactive Tableau dashboard delivers data-driven insights into historical stock market trends, enabling users to analyze price movements, trading volumes, and volatility patterns. Designed for traders, analysts, and investment professionals, it provides:  

 - Trend analysis (daily/weekly/monthly)  

 - Volume liquidity metrics  

 - Top-performing securities  

 - Technical indicators (Bollinger Bands®)  
  

**🔌 Data Source**

🔷  Web API: https://www.alphavantage.co/query   
    🐍 Python Pipeline: Using the above API to retrieve the last 6 months of data for the following stocks in JSON format. ["TSLA","AAPL","NVDA","PLTR","F","AMZN","NKE","AMD","GOOG","SOFI"] 
    Load data into the MySQL database  

  
**📊 Visualization**

    🔷 CandleStick Chart: Visualizes the open, high, low, and close (OHLC) prices of a stock (or other asset) over a specific time period (e.g., daily, hourly). It helps traders and analysts identify price trends, reversals, and volatility.
    🔷 Volume Table: Displays the total volume of respective stocks that were traded during the parameterized period.
    🔷 Packed Bubble: Visualize relative trading volumes across multiple stocks, where: 
        Bubble Size = Trading volume (larger = higher volume) 
        Bubble Label = Stock symbol (e.g., AAPL, TSLA).
    🔷 Bollinger Bands: Moving average indicator. Measure volatility (bands widen during high volatility, narrow during low volatility). Spot potential reversals or breakouts.
    🔷 Line Trend: Displays high and low rates for a specific period

  
**📌 Screenshots**

![image](https://github.com/user-attachments/assets/a64f436b-9a19-40b1-b3e3-f52261bd2515)

  
**🚀 Technologies Used**

        🔗 Data Source: Web API (last 6 months of data)  
        🐍 Data Pipeline: Python (Requests)  
        🗃️ Database: MySQL (Optimized queries)  
        📊 Visualization: Tableau (Dynamic dashboards)  

