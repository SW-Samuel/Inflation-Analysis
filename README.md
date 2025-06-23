# Inflation Analysis - IPCA 📈🇧🇷

This repository contains a data analysis and forecasting project focused on the Brazilian inflation index **IPCA (Índice de Preços ao Consumidor Amplo)**.

## 📌 Project Overview

The main objective of this project is to analyze historical IPCA data and build a predictive model to forecast future inflation variations.

The analysis covers data visualization, correlation analysis, feature engineering with lag variables, and the use of a **Random Forest Regressor** for prediction.

## 📂 Dataset

The dataset used is from **IBGE (Instituto Brasileiro de Geografia e Estatística)**, containing monthly IPCA variation data from **2012 to 2024**.

- 📅 **Period:** 2012 - 2024  
- 🏢 **Source:** IBGE (Brazilian Institute of Geography and Statistics)

## 🔍 Project Steps

1. **Exploratory Data Analysis (EDA):**  
   - Visualization of inflation trends over time  
   - Monthly variation patterns  
   - Correlation analysis between variables  

2. **Feature Engineering:**  
   - Creation of lag variables (previous months' IPCA variations)  

3. **Model Building:**  
   - Train-test split  
   - Model training using **Random Forest Regressor**  
   - Hyperparameter tuning (basic)  

4. **Evaluation:**  
   - Error metrics: **Mean Squared Error (MSE)**  
   - Visualization of predicted vs actual inflation values  

5. **Visualization:**  
   - Time series plots showing historical and predicted IPCA variations  

## 🛠️ Technologies and Libraries Used

- Python 🐍  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  
- Numpy  

## 📈 Results

The model captures short-term variation patterns based on past months' data. Although Random Forest is not a traditional time series model, it provides a baseline for further improvements with more advanced forecasting models.

---

> 📌 **Author:** Samuel  
> 📅 **Last Update:** June 2025
