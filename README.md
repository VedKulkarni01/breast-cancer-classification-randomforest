# Breast Cancer Classification

Comparing Random Forest, Logistic Regression, and XGBoost on the Wisconsin Breast Cancer dataset.

## What this project does
- Loads and explores the breast cancer dataset (569 samples, 30 features)
- Handles class imbalance using Stratified K-Fold Cross Validation
- Trains and compares three classifiers
- Evaluates using F1 score and confusion matrix

## Results
| Model | Mean F1 | Std |
|---|---|---|
| XGBoost | 0.971 | 0.008 |
| Random Forest | 0.965 | 0.010 |
| Logistic Regression | 0.964 | 0.014 |

## Tools
scikit-learn · xgboost · pandas · matplotlib · seaborn
