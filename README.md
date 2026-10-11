# 🏦 Bank Customer Churn Prediction Engine

An end-to-end Machine Learning pipeline using **Scikit-Learn** (Stacking Ensemble) to predict retail banking customer attrition.

## 📌 Project Highlights
* **Dataset:** Kaggle Playground Series s4e1 (165k+ records)
* **Model:** 2-Level Stacking Ensemble (Random Forest + HistGradientBoosting $\rightarrow$ Logistic Regression)
* **Performance:** **0.8889 ROC-AUC** on hold-out validation data

## 🎯 Optimization & Impact
* **Custom Feature Engineering:** Added `Balance_per_Product`, `Balance_to_Salary`, and interaction labels (`Active_Product_Group`).
* **Decision Threshold Tuning:** Tuned probability threshold from 0.5 to 0.35, lifting **Churn Recall from 55% to 62%** (+489 retained clients captured) while maintaining 69% precision.
