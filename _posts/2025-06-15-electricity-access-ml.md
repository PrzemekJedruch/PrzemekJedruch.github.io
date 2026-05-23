---
layout: post
title: "Predicting Global Electricity Access Using Machine Learning"
date: 2025-06-15
---

# Predicting Global Electricity Access Using Machine Learning

In this project, I developed a machine learning pipeline to predict electricity access levels across countries using socioeconomic and technological indicators.

## Project Workflow

- Data cleaning
- Correlation analysis
- Feature selection
- Random Forest regression
- Hyperparameter tuning
- SHAP explainability
- Future forecasting

## Machine Learning Model

The project used a Random Forest Regressor trained on global socioeconomic data.

The final model achieved:

- R² Score: 0.86
- MAE: 5.80
- RMSE: 10.63

## SHAP Explainability

SHAP values were used to interpret the model predictions and identify the most influential features affecting electricity access levels.

The analysis showed that:
- internet usage,
- education,
- and urbanization

were among the strongest predictors.

## Forecasting

The trained model was also used to forecast future electricity access levels for selected countries using scenario-based predictions.

## GitHub Repository

Project repository:

https://github.com/PrzemekJedruch/electricity-access-prediction
