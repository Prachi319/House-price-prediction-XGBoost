# 🏡 California House Price Prediction

This project aims to predict **median house prices** in California districts based on various demographic and geographic features using **regression models**. It’s an end-to-end machine learning project using the **California Housing Dataset**.

---

## 📁 Dataset

- **Source**: Scikit-learn’s built-in dataset
- **Features**:
  - `MedInc`: Median income in block group
  - `HouseAge`: Median house age
  - `AveRooms`: Average number of rooms per household
  - `AveBedrms`: Average number of bedrooms per household
  - `Population`: Block group population
  - `AveOccup`: Average number of household members
  - `Latitude`: Location coordinate
  - `Longitude`: Location coordinate
- **Target**: `MedHouseVal` — Median house value (in 100,000s USD)

---

## 🎯 Objective

To build a **regression model** that predicts the **median house price** in a given area using the available features.

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null values and data imbalance
- Used histograms, scatter plots, and heatmaps to understand distributions and correlations
- Found that `MedInc`, `Latitude`, and `Longitude` are strong predictors

---

## ⚙️ Models Used

- XGBoost Regressor
---

## 🧪 Model Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **R² Score (Coefficient of Determination)**


