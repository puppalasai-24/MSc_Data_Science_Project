# MSc_Data_Science_Project
# House Price Prediction Using Machine Learning

## Overview

This project aims to predict residential house prices using machine learning techniques. The objective is to develop a reliable regression model that can estimate house prices based on various property-related features such as size, quality, and location.

The project follows a structured machine learning pipeline, including data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation.

---

## Dataset

* Dataset: Ames Housing Dataset (Kaggle)
* Number of records: Approximately 1460
* Number of features: 79
* Target variable: SalePrice

Dataset link:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

---

## Methodology

### Data Preprocessing

* Missing values handled using domain-based methods
* Numerical features imputed using median values
* Categorical variables encoded using one-hot encoding
* Train and test datasets aligned

### Exploratory Data Analysis

* Analysis of target variable distribution
* Identification of correlations between features
* Detection of outliers

### Feature Engineering

* Creation of new features such as TotalSF and HouseAge
* Log transformation applied to the target variable

### Model Development

The following models were implemented and compared:

* Linear Regression
* Ridge Regression
* Random Forest
* XGBoost

### Evaluation

* Metrics used: Root Mean Squared Error (RMSE) and R² score
* Cross-validation applied for model validation

---

## Results

| Model             | RMSE        | R²     |
| ----------------- | ----------- | ------ |
| Linear Regression | 51,405.0943 | 0.6555 |
| Ridge Regression  | 30,763.4088 | 0.8766 |
| Random Forest     | 28,631.2315 | 0.8931 |
| XGBoost           | 24,279.1196 | 0.9231 |

XGBoost achieved the best performance among all models.

---

## Key Findings

* Ensemble models outperform traditional linear models
* Feature engineering improves prediction accuracy
* Data preprocessing significantly impacts model performance

---

## Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost

---

## Future Work

* Implementation of LightGBM and CatBoost
* Use of model stacking techniques
* Development of a web-based deployment system

---

## Author

Venkata Sai Kumar Puppala
MSc Data Science
University of Hertfordshire

---

## Note

This project was developed for academic purposes as part of the MSc Data Science program.
