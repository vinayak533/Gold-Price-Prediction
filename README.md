# 🪙 Gold Price Prediction using Machine Learning

This project builds a machine learning model to predict the price of gold using historical financial data. By leveraging Python's data science libraries, we perform end-to-end analysis — including preprocessing, model training, and prediction visualization.

This project is ideal for anyone learning how to apply regression in real-world financial forecasting.

---

## 📝 Overview

Gold is a major financial asset that responds to multiple economic factors like oil prices, stock indices, inflation, and geopolitical risk. Predicting gold price trends can be valuable for:

- Financial analysts
- Economists
- Traders
- Data science learners

This project trains a regression model on historical data to forecast gold prices and visualize the accuracy of predictions against actual values.

---

## 📊 Dataset

The dataset includes historical financial features such as:

- Gold Price (`GLD`)
- SPX (S&P 500 Index)
- USO (Oil ETF)
- SLV (Silver Price)
- EUR/USD Exchange Rate

> Make sure your dataset is cleaned and has no missing values. You can download similar datasets from [Kaggle](https://www.kaggle.com/), [Yahoo Finance](https://finance.yahoo.com), or other data providers.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze feature correlation with gold prices
- Build and evaluate a Linear Regression model
- Visualize Actual vs Predicted values

---

## 💻 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib / Seaborn** – Visualization
- **Scikit-learn** – ML algorithms & model evaluation

---

## 🔁 Workflow

1. **Import libraries & load dataset**
2. **Data cleaning** (null values, data types)
3. **EDA & correlation heatmap**
4. **Split data into training and test sets**
5. **Train a Linear Regression model**
6. **Predict and visualize results**
7. **Evaluate model using R² score**

---

## 📈 Model Evaluation

We use the **R² score** to evaluate how well the predictions match the actual values:

- **R² = 1** → Perfect prediction
- **R² ≈ 0.9+** → Very good model
- The notebook also includes a **line plot** comparing real vs predicted prices.

---
