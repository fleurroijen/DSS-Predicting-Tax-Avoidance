# Predicting Tax Avoidance in the European Union

Thesis submitted in partial fulfillment of the requirements for the degree of Master of Science in Data Science & Society at the School of Humanities and Digital Sciences of Tilburg University

## Overview
This repository contains the code for the Data Science & Society Master's Thesis titled "Predicting Tax Avoidance in the European Union using Machine Learning Models: : A Comparative Study on Logistic Regression, Random Forest and XGBoost using metaheuristic feature selection algorithms." The study evaluates various machine learning models for forecasting the tax avoidance behavior of a company, focusing improving predictive performance and interpretability with metaheuristics algorithms for feature selection and SHAP for feature importance.

## Algorithms and Models
This thesis analyses the following supervised ML models:
- Logistic Regression ('LR')
- Random Forest ('RF')
- Extreme Gradient Boosting ('XGBoost')

Additionally, this thesis uses the following metaheuristic algorithms:
- Genetic Algorithm ('GA')
- Particle Swarm Optimization ('SWO')
- PSO-GA hybrid ('PSO-GA')

## Libraries and Tools
- Pandas
- NumPy
- joblib
- Matplotlib
- Seaborn
- missingno
- feature-engine
- SciPy
- collections.Counter
- imbalanced-learn
- Optuna
- scikit-learn (IsolationForest, LogisticRegression, RandomForestClassifier, StratifiedGroupKFold)
- XGBoost (XGBClassifier)
- SHAP

## Dataset
Firm-specific financial data extracted from Compustat ranging from 2005 to 2023.

