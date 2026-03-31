# 💰 Cash Flow Intelligence Dashboard & Forecasting System (UMDAC Datathon)

## 📌 Overview

This project was developed as part of the UMDAC Datathon, focusing on analyzing and forecasting cash flow to support financial decision-making.

The goal was to provide finance teams with better visibility into short-term liquidity, identify abnormal cash flow behavior, and evaluate the reliability of forecasting models.

---

## 🧠 Problem Statement

Finance teams often lack reliable short-term visibility into weekly cash positions due to:

* Irregular cash inflows and outflows
* Complex transaction categories
* Uncertain forecasting accuracy

This makes it difficult to:

* Anticipate liquidity risks
* Trust forecasted cash positions
* Detect unusual financial activities

---

## 💡 Solution

We developed a **“Weekly Cash Control Tower”**, combining:

* 📊 Interactive Power BI dashboard
* 🤖 Python-based forecasting models
* 🚨 Anomaly detection logic

---

## ⚙️ Key Features

### 📊 1. Cash Flow Dashboard (Power BI)

* Weekly cash inflow & outflow tracking
* Net cash flow trends
* Country-level and category-level breakdown
* Weekly ending balance monitoring

### 📈 2. Cash Flow Drivers Analysis

* Identified major contributors to inflow (e.g., AR)
* Identified major contributors to outflow (e.g., Netting AP, Payroll)
* Highlighted concentration of cash movements in key categories

### 🚨 3. Anomaly Detection

* Detected abnormal weeks using threshold-based approach
* Identified:

  * 6 sudden spikes
  * 6 sudden drops
* Enabled early risk monitoring for unusual financial activity

### 🤖 4. Forecasting Model (Python)

Implemented multiple time-series approaches:

* Moving Average
* Exponential Smoothing
* Linear Regression
* Median-based method

---

## 📊 Results & Insights

* Cash outflows frequently exceeded inflows → consistent cash burn periods
* Cash flow exhibited high volatility across weeks
* A small number of categories drove the majority of cash movement
* 12 abnormal weeks were detected, indicating potential financial risks

---

## ⚠️ Forecast Performance (Honest Evaluation)

* MAPE (Net): **370.14 (Poor)**
* Directional Accuracy: **57.14%**

### 🧠 Key Learning:

The forecasting results highlight the **challenges of predicting real-world financial data**, which is:

* Highly volatile
* Influenced by external factors
* Not easily captured by simple models

This project emphasizes the importance of:

* Model evaluation
* Transparency in reporting
* Using forecasts with caution

---

## 🛠️ Tech Stack

* Power BI (dashboard & visualization)
* Python (forecasting & analysis)
* Pandas, NumPy, Scikit-learn

---

## 👩‍💻 My Contribution

* Developed Power BI dashboard for financial insights
* Assisted in data analysis and visualization
* Contributed to interpretation of forecasting results
* Participated in business storytelling and presentation

---

## 📷 Dashboard Preview

(Insert screenshots here)

---

## 💡 Business Impact

This system helps finance teams to:

* Monitor weekly liquidity
* Identify abnormal transactions early
* Understand key cash flow drivers
* Make informed decisions despite forecasting uncertainty

---

## 🏆 Experience

Completed under datathon conditions, focusing on:

* real-world financial data
* time constraints
* collaborative problem-solving

---

## 🚀 Future Improvements

* Use advanced models (e.g., LSTM, Prophet)
* Incorporate external economic factors
* Improve feature engineering for better accuracy

