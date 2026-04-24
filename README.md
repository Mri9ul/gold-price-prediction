# 🪙 Gold Price Prediction

This project uses machine learning to predict **gold prices** using historical financial indicators such as stock index data, oil prices, silver prices, and currency exchange rates.

---

## 📌 Objective

The objective of this project is to build a regression model that predicts the gold price using related financial market features.

The target variable is:

* **GLD** – Gold ETF price, used as a proxy for gold price

---

## 📊 Dataset

The dataset contains historical financial data with the following columns:

* **Date** – Observation date
* **SPX** – S&P 500 index value
* **GLD** – Gold ETF price / target variable
* **USO** – Oil price indicator
* **SLV** – Silver price indicator
* **EUR/USD** – Euro to US Dollar exchange rate

---

## ⚙️ Project Workflow

1. Data loading
2. Data inspection
3. Missing value check
4. Correlation analysis
5. Exploratory Data Analysis
6. Feature-target separation
7. Train-test split
8. Model training using Random Forest Regressor
9. Model evaluation
10. Feature importance analysis
11. Sample prediction
12. Model saving

---

## 🧠 Model Used

* **Random Forest Regressor**

---

## 📈 Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 💡 Features Used for Prediction

The model uses the following features:

* SPX
* USO
* SLV
* EUR/USD

The target variable is:

* GLD

---

## 📊 Feature Importance

Feature importance analysis was performed to understand which financial indicators had the strongest influence on gold price prediction.
---

