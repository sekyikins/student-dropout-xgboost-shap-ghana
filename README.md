# Student Dropout Prediction using XGBoost + SHAP

## Overview
This project predicts student dropout risk using machine learning. The system is built using an XGBoost classifier and enhanced with SHAP to explain model decisions.

## Objectives
- Predict students at risk of dropping out
- Improve early academic intervention
- Provide interpretable ML predictions for educators

## Methodology
- Data preprocessing (missing value handling, encoding, feature cleaning)
- Model training using XGBoost
- Evaluation using cross-validation and hold-out test set
- Model explanation using SHAP feature importance

## Models Used
- Logistic Regression (baseline)
- Random Forest
- Support Vector Machine (SVM)
- XGBoost (main model)

## Explainability
SHAP is used to interpret feature contributions to dropout predictions.

## Reproducibility
- Fixed random seed = 42
- Stratified train/validation/test split
- Standard evaluation metrics: Accuracy, F1-score, ROC-AUC

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- SHAP
- Pandas, NumPy

## Author
Student ML Research Project
