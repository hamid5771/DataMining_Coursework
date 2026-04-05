# 🔍 Data Mining & Predictive Classification Project

## 📑 Project Overview
This repository contains a comprehensive data mining pipeline developed for the **CS4850 Data Mining module**. The project focuses on building an automated system to classify data instances into predefined categories (e.g., software requirements or system classes) using a variety of machine learning algorithms and advanced feature engineering techniques.

## ✨ Key Features
* **Memory-Efficient Preprocessing**: Implements automatic type conversion (e.g., to `float32`) to reduce memory footprint by nearly 50%, enabling the processing of larger datasets on standard hardware.
* **Advanced Exploratory Data Analysis (EDA)**: Includes detailed visualizations of feature types, missing values, and outlier distributions to ensure data quality.
* **Feature Selection & Optimization**: Uses **Lasso (L1) regularization** and **RFECV** (Recursive Feature Elimination with Cross-Validation) to identify the most significant predictors and remove noise.
* **State-of-the-Art Modeling**: Compares performance across multiple high-performance classifiers:
    * **XGBoost** & **LightGBM**
    * **Random Forest**
    * **Logistic Regression**
* **Robust Validation**: Employs **Stratified Group K-Fold** cross-validation to ensure model generalizability and prevent data leakage.

## 🛠️ Tech Stack
* **Language**: Python 3.9+
* **Core Libraries**: 
    * `pandas` & `numpy` (Data Processing)
    * `scikit-learn` (Modeling & Selection)
    * `XGBoost` & `LightGBM` (Gradient Boosting)
    * `matplotlib` & `seaborn` (Visualization)

## 🚀 Getting Started

### 1. Prerequisites
Install the required dependencies using pip:
```bash
pip install pandas numpy scikit-learn xgboost lightgbm matplotlib seaborn
