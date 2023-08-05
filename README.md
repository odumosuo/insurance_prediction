# Predicting Insurance Charges with Machine Learning
## Description
The aim of this project is to predict health insurance premium charges based on several different factors using three regression-based (Support Vector Regressor, Adaptive Boosting Regressor, and k-Nearest Neighbors Regressor) and three classification-based (Support Vector Classifier, Adaptive Boosting Classifier, and k-Nearest Neighbors Classifier) machine learning models in Python. Additionally, this investigation sought to identify which factors contribute to an individual's insurance premium charges.

After thorough data processing, we used the information to train all six models and evaluated their performance on unseen test data. The Support Vector Classifier performed the classification task best, as indicated by accuracy and F1 scores, while the AdaBoost Regressor performed the regression task best, with the lowest RMSE and highest R2 scores. Notably, age and smoker status were consistently identified as the most important features for determining insurance premium charges.

The results of this investigation can inform best practices in constructing machine learning models in the future and highlight lifestyle practices that individuals can modify to reduce their insurance expenses.

## How to Run
To execute the project, ensure that all files are in the same directory, and then run the pyhton script master_script.py

## Features
Health insurance premiums

Machine learning models (Regression and Classification)
k-Nearest Neighbors (kNN)
Adaptive Boosting Regressor (AdaBoost Regressor)
Adaptive Boosting Classifier (AdaBoost Classifier)
Support Vector Machine (SVM)
Data preprocessing
Outlier detection
Model evaluation
Hyperparameter tuning
Overfitting and underfitting considerations
Prediction
