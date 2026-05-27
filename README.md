# Nairobi Real Estate Price Prediction 

## Overview
Machine learning project predicting Nairobi property prices using
Linear Regression, Ridge Regression and XGBoost.

## Key Findings
- Linear Regression achieved the best RMSE of KES 2,768,298
- Location is the #1 price driver — Muthaiga, Runda and Karen dominate
- XGBoost overfitted on this dataset size — regularisation helped but
  simpler models won
- Physical features like size and bedrooms matter less than neighborhood

## Models Compared
| Model | RMSE |
|---|---|
| Linear Regression | KES 2,768,298 (The Better One) |
| Ridge Regression | KES 2,789,858 |
| XGBoost | KES 3,629,858 |

## Tools Used
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Author
Fred Onditi
