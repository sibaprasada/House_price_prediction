# 🏡 Boston House Price Prediction

A machine learning project to predict housing prices in Boston suburbs based on various features like crime rate, room count, and property tax. Developed using **Python** and **XGBoost** in Google Colab.

## 📝 Problem Statement
The goal is to analyze the Boston Housing dataset and build a regression model that can accurately estimate the median value of owner-occupied homes (`MEDV`). This helps in understanding how different factors like air quality (`NOX`) and pupil-teacher ratio (`PTRATIO`) impact real estate prices.

## 📂 Dataset
The dataset is sourced from the UCI Machine Learning Repository (via Kaggle).
- **Size:** 506 records
- **Features:** 13 input variables (CRIM, ZN, RM, AGE, etc.)
- **Target:** MEDV (Median value in $1000s)

## 🔧 Technologies Used
- **Python 3**
- **Google Colab** (Jupyter Notebook)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization/Heatmaps)
- **Scikit-Learn** (Train-Test Split, Metrics)
- **XGBoost** (Machine Learning Model)

## ⚙️ Project Steps
1. **Data Loading:** Parsed the raw CSV data.
2. **Exploratory Data Analysis (EDA):** - Checked for missing values.
   - Used correlation matrices (Heatmap) to find relationships between features.
   - Plotted price distributions.
3. **Model Building:** Implemented **XGBRegressor** for high-performance prediction.
4. **Evaluation:** Assessed model accuracy using R-squared and Mean Absolute Error.

