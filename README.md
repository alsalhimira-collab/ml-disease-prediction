# Explainable Machine Learning for Gallstone Disease Prediction

## Overview
This project predicts gallstone disease using supervised machine learning and explains predictions using SHAP and LIME.

## Dataset
- 319 patients
- 39 biomedical + clinical features
- Binary classification (Gallstone / No Gallstone)

## Models Compared
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Techniques
- Data scaling (StandardScaler)
- Hyperparameter tuning (GridSearchCV)
- Train/Test split
- Bias–Variance analysis
- Model comparison

## Results
XGBoost achieved the best performance:
- Accuracy: 0.84
- Precision: 0.86
- Recall: 0.80
- F1-score: 0.83

## Explainability
- SHAP for global + local explanations
- LIME for instance-level interpretation

## Tech Stack
Python, Scikit-learn, XGBoost, SHAP, LIME, Pandas, Matplotlib

## Author
Mira Ibrahim AlSalhi
