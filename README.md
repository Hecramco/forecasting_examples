# ⚡Forecast project:  Energy Data

# ⚡ Forecasting Energy Consumption using Machine Learning

**Developed by**: Hector M. Ramírez C.
**Dataset**: [Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption/data) (Kaggle)

---

## 📌 Overview

Energy consumption patterns offer valuable insight into how societies operate — and how we might build more sustainable futures. In a world where carbon emissions and climate change are urgent concerns, smarter use of energy is not just an economic decision, but an environmental imperative.

This project tackles a core sustainability challenge: **predicting energy demand**. By forecasting future consumption, utility companies and communities can better integrate renewable sources, optimize energy storage, and reduce fossil fuel reliance.

---

## 🎯 Objective

This personal project aims to demonstrate a complete **end-to-end time series forecasting pipeline** using real-world data, driven by a strong interest in sustainability and AI for social good. My goals include:

- Understanding energy usage patterns at scale
- Applying both statistical and machine learning methods
- Evaluating model effectiveness through rigorous metrics
- Building a tool that could support more efficient, eco-friendly planning

---

## 🧪 Technical Highlights

- 📊 **Time Series Decomposition**: Extracted and visualized trend, seasonality, and noise
- ⚙️ **Models Used**:
  - **ARIMA** (Autoregressive Integrated Moving Average)
  - **XGBoost Regressor** with engineered features (lags, rolling stats, etc.)
- 🔁 **Cross-Validation**: TimeSeriesSplit to respect temporal order
- 📈 **Model Evaluation**:
  - RMSE: ~145 MW
  - R² Score: 0.996 (very high accuracy)
  - Residuals: Normally distributed, indicating low bias and good generalization

---

## 🌱 Why This Matters to Me

I believe that **technology should serve people and the planet**. Forecasting energy demand isn't just a technical challenge — it's a piece of the broader puzzle in building sustainable infrastructure.

This project reflects my long-term interest in:

- Clean tech and AI applications for **climate resilience**
- Using data science to **reduce waste and optimize resources**
- Contributing to solutions that align with the UN’s **Sustainable Development Goals (SDGs)**

I'm especially drawn to opportunities where machine learning can enable smarter environmental planning, and this project is a practical step in that direction.

---

## 📂 Project Structure

**Project Developed by**: Hector M. Ramírez C.

Data: [Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption/data) from Kaggle.

## 📌 Overview

Energy conspumption has become a major indicator, sustainable developement seeks to reduce the CO2 consuption by taking different meassures such as change the way we eat, the way we move and the way we consume energy but also the sources that are used. Forecasting energy consumption is an important step in the process to migrate to new technologies. By Forecasting the energy consumption it is possible to have an idea of the demand a company will face in a certain period, then the use of batteries and renewable energies can help to prepare for a possible rise or drop in demand based on former meassurable data.

## 🎯 Objective

As a personal  project, this aims to show an example of data analysis using energy data, by using different tools and models such as ARIMA and XGBoost.

## 📂 Project Structure

* `data/`: This directory is used to store the energy data downloaded from kaggle.
* `notebooks/:`: Jupyter Notebooks with exploratory analysis, preprocessing, modeling, and evaluation.
* `saved_models/`: Storage of the las trained model.
* `requirements.txt`: Requirements to run the experiments.
