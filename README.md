# 🧾 Predicting Sales at Scale: Rossmann Forecasting with Time Series & Feature Engineering

In the dynamic world of retail, **one misstep in forecasting can cost millions**. 

Our team tackled this challenge for **Rossmann**, one of Germany’s largest drugstore chains, by building a robust **sales forecasting model** — rooted in meticulous **data preprocessing** and enhanced with time-aware feature engineering.

This repository includes our PowerPoint presentation for the data-preprocessing plan + my full individual report of our model.

---

## 🎯 Project Goals

- Prepare and clean multi-source historical sales data
- Engineer meaningful features from time and customer signals
- Model future 6-week sales using a seasonal time-series method (SARIMA)
- Evaluate robustness with real-world business considerations like seasonality, promotions, and competitors

---

## 🛠️ What We Did

### 📁 Data Sources
- `train.csv` – Daily sales and customer counts (Jan 2013–July 2015)
- `test.csv` – Future prediction period (Aug–Sept 2015)
- `stores.csv` – Store metadata (e.g., type, assortment, competition info)
- 📐 Evaluated with:
  - **MSE** (mean squared error) – model accuracy
  - **MAE** (mean absolute error) – robustness
  - **R² score** – model fit

---

## 🧠 My reflections:

- Data preprocessing is *not just cleaning* — it’s where real-world context enters your model.
- Promotion periods, store competition, and temporal shifts matter.
- Future improvements could include:
  - Using non-linear models like **Seasonal SVR** (as per Ensafi et al., 2022)
  - Incorporating **external macroeconomic data**
  - Exploring **deep learning** for nonlinearities (e.g., LSTM)

---
