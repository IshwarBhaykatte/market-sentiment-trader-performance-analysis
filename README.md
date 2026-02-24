# Power BI | Data Analytics | Financial Analysis | DAX | Data Modelin

👇
# 📊 Market Sentiment vs Trader Performance Analysis

End-to-end trading performance analysis integrating historical trade data with market sentiment (Fear & Greed Index) to evaluate profitability, risk exposure, and behavioral trading patterns.

# 🎯 Executive Summary

This project investigates how overall market sentiment influences trading performance.
By combining **211K+ closed trades** with daily sentiment data, I built both:

* 📌 Python-based exploratory analysis

* 📊 Interactive Power BI dashboard with dynamic DAX insights

The objective was to transform raw trade-level data into decision-ready intelligence.


# 🧠 Business Problem
Financial markets are often driven by fear and greed.
But does sentiment actually impact:
* Win rate?
* Risk-reward ratio?
* Profitability?
* Volatility?
* Capital efficiency?
This project answers those questions using real trading data.


# 📂 Dataset Overview
* **211,000+ historical trades**
* **$1.19B total trading volume**
* **Daily Fear & Greed Index classification:**
    * Extreme Fear
    * Fear
    * Neutral
    * Greed
    * Extreme Greed


# 🏗 Data Modeling Approach (Power BI)
* **To ensure accurate time-based analysis:**
     * Built a star schema data model
     * Created a dedicated Calendar table
     * Established proper one-to-many relationships
     * Cleaned and transformed data using Power Query
     * Implemented advanced DAX measures for dynamic insights

This ensured scalable and reliable performance analysis.

# 📊 Dashboard Features
* KPI cards for trading volume, profit, loss & win rate
* Sentiment-based performance comparison
* Risk-reward ratio by sentiment phase
* Volatility analysis
* Monthly trend analysis
* Trader behavior insights
* Dynamic sentiment insight detection using DAX
* Interactive date & sentiment filters
  
# 💎 Updated Key Insights
* $1.19B capital deployed across 211K+ trades.
* Generated $10.3M net realized profit.
* Extreme Greed phase delivered the highest win rate (~46%).
* Fear phases showed maximum volatility, indicating higher risk.
* Neutral markets produced more stable but lower returns.
* Capital efficiency remained below 1%, emphasizing the importance of risk-adjusted performance evaluation.

> Trader performance significantly shifts across sentiment regimes, highlighting the psychological impact of market emotion on financial decision-making.


# 🛠 Tools & Technologies
* Python (Pandas, Matplotlib)
* Power BI
* DAX
* Power Query
* Data Modeling (Star Schema)
* Time Intelligence Functions


# 📸 Dashboard Preview
<img width="1291" height="730" alt="Dashboard_Screenshot" src="https://github.com/user-attachments/assets/93f1e0cf-aed2-465c-a77a-8ab9b5898cfb" />


## 📌 Project Structure
* 📁 data
* 📁 python-analysis
* 📁 powerbi-dashboard
* README.md


# 🚀 What I Learned
* Designing scalable BI data models
* Writing dynamic DAX for insight automation
* Converting raw analysis into executive-level dashboards
* Evaluating performance beyond just profitability (risk + efficiency)

