# Housing Price Prediction (Python + Scikit-learn)

This project implements a machine learning pipeline to predict **housing prices** based on structured tabular data using various regression models. It focuses on evaluating and comparing multiple models using performance metrics like **MSE**, **RMSE**, **MAE**, and **R²** — without relying on data visualizations.

## 📊 Project Overview

The workflow includes:

- 🧼 Data cleaning and preprocessing
- 🏗️ Feature encoding and scaling
- 🧪 Train-test split
- 🤖 Model training and comparison
- 📊 Performance evaluation using standard regression metrics

> 🎯 **Goal**: Build a robust and accurate housing price predictor using multiple regression algorithms.

## 📁 Dataset

- Source: [Kaggle Housing Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction))
- Contains features such as number of rooms, area, location, lot size, and price.

## ⚙️ Tools & Libraries

- **Python 3.x**
- **pandas**, **numpy** – data manipulation
- **scikit-learn** – machine learning models and utilities
- **xgboost** – for gradient boosting
- **jupyter notebook / VSCode** – development environment

## 🤖 Models Used

- ✅ **K-Nearest Neighbors (KNN)**
- ✅ **Multiple Linear Regression**
- ✅ **Decision Tree Regressor**
- ✅ **Random Forest Regressor**
- ✅ **XGBoost Regressor**

## 🧠 Workflow

1. **Data Cleaning**: Handle nulls, correct data types, drop irrelevant columns
2. **Feature Engineering**:
   - Encoding categorical features
   - Scaling numerical features
3. **Train-Test Split**: Using `train_test_split` from `sklearn.model_selection`
4. **Model Training**: Fit all five models using training data
5. **Evaluation Metrics**:
   - **MSE** (Mean Squared Error)
   - **RMSE** (Root Mean Squared Error)
   - **MAE** (Mean Absolute Error)
   - **R² Score**
