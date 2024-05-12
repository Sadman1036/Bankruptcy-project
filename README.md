# Bankruptcy Prediction Using Machine Learning

## Overview
This project investigates the application of various machine learning models to predict bankruptcy, which is crucial for financial risk management. Using a dataset of financial attributes from numerous firms, models like Multivariate Discriminant Analysis (MDA), Logistic Regression (LR), GBM Classifier, and Naïve Bayes are employed to identify potential bankruptcies.

## Dataset
The dataset consists of 92,872 entries with 13 attributes, primarily skewed towards non-bankrupt instances. Attributes include financial metrics like EPS, Liquidity, and Profitability. The data has been cleaned and preprocessed to handle missing values and outliers, ensuring robust model training.

## Models Used
- **Multivariate Discriminant Analysis (MDA)**: Traditionally used for risk assessment by finding a linear combination of features that characterizes or separates two or more classes.
- **Logistic Regression (LR)**: A statistical model known for its simplicity and effectiveness in binary classification problems.
- **GBM Classifier**: A powerful ensemble learning model particularly effective in handling imbalanced datasets.
- **Naïve Bayes**: A simple probabilistic classifier based on applying Bayes' theorem with strong independence assumptions.

## Model Performance
The models' performances were evaluated based on precision, recall, F1-score, and overall accuracy:
- **Gradient Boosting Model (GBM)** emerged as the top-performing model with the highest overall accuracy and substantial discriminatory power, as evidenced by its AUC of 0.89.
- **Logistic Regression and MDA** showed robust results but were less effective in minority class predictions.
- **Naïve Bayes** struggled with a high rate of false positives, affecting its overall precision and F1-score.

