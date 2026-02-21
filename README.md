# coco-cola-stock-price-ml-powerbi-analysis
# Stock Price ML & Power BI Analysis

This project demonstrates an end-to-end workflow combining Python-based machine learning with Power BI visualization for stock price analysis.

---

## 📌 Project Overview

The project analyzes historical stock price data (Coca-Cola dataset) to:

- Perform data cleaning and preprocessing
- Engineer technical indicators
- Build a machine learning model
- Validate feature behavior using an interactive Power BI dashboard

The goal is to bridge technical modeling with business-friendly visualization.

---

## 🧠 Machine Learning Workflow

### 1. Data Preprocessing
- Handled null values
- Corrected data types
- Removed inconsistencies
- Generated cleaned dataset

### 2. Feature Engineering
- 20-Day Moving Average (MA_20)
- 50-Day Moving Average (MA_50)
- Daily Return
- Volatility

### 3. Model Building
- Target Variable: Closing Price
- Train-test split applied
- Model performance evaluated using standard regression metrics

  ## 📊 Power BI Dashboard

An interactive dashboard was built using the cleaned dataset to analyze feature relationships.

### Dashboard Highlights
- Distribution of closing prices
- Average closing price KPI
- Closing Price vs Trading Volume
- Closing Price vs MA_20
- Closing Price vs Volatility
- Interactive slicers for:
  - Volatility range
  - Trading volume range
 
    ![Power BI Dashboard](powerbi/dashboard_screenshot.png)

---

## 🛠 Tools & Technologies

- Python (pandas, numpy, matplotlib, sklearn)
- Jupyter Notebook
- Power BI Desktop
- Git & GitHub

---

## 🎯 Key Learning Outcomes

- Importance of proper data cleaning
- Feature engineering for financial data
- Combining ML with BI tools
- Improving interpretability using dashboards

---

## 🚀 Future Improvements

- Restore time-based trend analysis
- Implement advanced models (XGBoost / LSTM)
- Deploy as interactive web application
