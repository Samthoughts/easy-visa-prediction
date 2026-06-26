# Easy Visa Approval Prediction

## Overview

This project predicts visa approval outcomes using machine learning techniques. Multiple classification models were evaluated on original, SMOTE-oversampled, and undersampled datasets to identify the most effective model for predicting visa certification decisions.

## Objectives

* Predict visa approval status.
* Compare multiple classification algorithms.
* Handle class imbalance using SMOTE and undersampling.
* Improve model performance through hyperparameter tuning.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Models Evaluated

* Decision Tree
* Random Forest
* Bagging Classifier
* AdaBoost
* Gradient Boosting

## Techniques Used

* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Engineering
* SMOTE Oversampling
* Random Undersampling
* Hyperparameter Tuning (RandomizedSearchCV)
* Model Evaluation using Accuracy, Precision, Recall, and F1-Score

## Results

Gradient Boosting trained on SMOTE-balanced data achieved the best balance between predictive performance and generalization, making it the recommended model for visa approval prediction.

## Author

Samiksha Singh
