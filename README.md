

# **Binance Trading Dataset – EDA & Feature Engineering**  

## **📌 Overview**  
This project analyzes **90 days of historical trade data** from various Binance accounts. The dataset includes:  
- **Port_IDs** → Unique identifiers for trading accounts  
- **Trade_History** → Details of past trades, including timestamps, assets, trade side (Buy/Sell), prices, and more  

## **🎯 Objective**  
The goal is to perform **exploratory data analysis (EDA)** and **feature engineering (FE)** to extract meaningful financial insights, clean the dataset, handle missing values, and rank trading accounts based on key performance metrics.  

## **📊 Key Metrics Calculated**  
For each account, we compute:  
- **ROI (Return on Investment)** → Measures profitability  
- **PnL (Profit and Loss)** → Net earnings or losses  
- **Sharpe Ratio** → Risk-adjusted returns  
- **MDD (Maximum Drawdown)** → Largest decline from peak value  
- **Win Rate** → Percentage of profitable trades  
- **Win Positions** → Count of successful trades  
- **Total Positions** → Total number of trades  

## **📈 Ranking Algorithm**  
A custom ranking algorithm is developed to evaluate trading accounts based on the computed financial metrics, identifying the **top 20 best-performing accounts**.  

## **📑 Documentation & Insights**  
The analysis includes:  
- **Data Cleaning** → Handling missing values, correcting inconsistencies  
- **Feature Engineering** → Creating new meaningful variables  
- **Findings & Assumptions** → Key observations based on the dataset  

🚀 **This project provides valuable insights into trading performance, helping optimize strategies based on real data!**  
