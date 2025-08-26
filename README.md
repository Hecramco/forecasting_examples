# ⚡ Forecasting with Machine Learning

**Developed by** : Hector M. Ramírez C.

**Datasets** :

* [Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption/data) (Kaggle)
* [Stock News &amp; Stock Prices](https://www.kaggle.com/) (Kaggle / public sources)

---

## 📌 Overview

This repository showcases **end-to-end forecasting pipelines** using machine learning on two domains:

1. **Energy Consumption Forecasting** – Predicting electricity demand to support more sustainable, efficient, and eco-friendly energy systems.
2. **Stock Forecasting with Sentiment Analysis** – Exploring how combining financial time series with news sentiment can improve predictions in highly volatile markets.

Both examples highlight how **machine learning can uncover hidden patterns in time-dependent data** and generate actionable insights.

---

## 🎯 Objectives

* Demonstrate forecasting workflows that mix **statistical methods, ML models, and feature engineering**
* Highlight how **domain knowledge** (energy → sustainability, finance → sentiment/news) makes predictions more relevant
* Show the versatility of ML applied to **different time series challenges**
* Share a personal commitment to using AI for **sustainability and social good**

---

## 🧪 Technical Highlights

### 🔋 Energy Consumption

* **Methods** : ARIMA, XGBoost
* **Features** : Lagged variables, rolling statistics, seasonal decomposition
* **Results** :
  * RMSE: ~145 MW
  * R² Score: 0.996
  * Residuals normally distributed → model generalizes well

### 📈 Stock Prices with Sentiment

* **Methods** : XGBoost, ARIMA, Feature engineering , Transformers/FinBERT (sentiment analysis on financial news)
* **Features** : Numerical (stock prices), categorical (tickers), textual (news sentiment)
* **Results** :
  * RMSE: ~19.2 USD
  * R² Score: 0.9825
  * Demonstrates benefit of **multimodal forecasting**

---

## 🌱 Why This Matters

Forecasting is more than just predicting numbers — it can guide  **real-world decisions** :

* ⚡ **Energy** → Better integration of renewable sources, reduced reliance on fossil fuels, smarter grid planning
* 💹 **Finance** → Understanding market dynamics, bridging human behavior (news sentiment) with quantitative models

This dual focus reflects my personal interests in:

* Clean tech and **climate resilience**
* **Data-driven decision-making** for complex systems
* Applying ML where it can **benefit people and the planet**

---

## 📂 Project Structure

```
forecasting-examples/
│
├── data/             # Energy & stock datasets
├── notebooks/        # Jupyter notebooks (EDA, preprocessing, modeling, evaluation)
├── saved_models/     # Trained models
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

---

## 🚀 Next Steps

* Deploy simple dashboards for visualization

---

👉 This repository is meant to serve as a **portfolio project** showing forecasting skills in different domains, with an emphasis on  **sustainability and AI for social impact** .

---
