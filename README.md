# 🐦 Bird Classification

This repository contains a Jupyter Notebook (`BirdClassification.ipynb`) that demonstrates the process of classifying bird species based on morphological features using machine learning techniques.

## 🧹 Clean and PreProcess

The notebook starts with data cleaning and preprocessing steps. The dataset used for bird classification is loaded from a GitHub repository. Missing values in numerical columns are filled with the average value of each column. Duplicate rows are also checked and removed. The dataset is then prepared for further analysis.

## 🔍 Visualize What We Have

Exploratory data analysis (EDA) is performed to understand the distribution of features and the distribution of bird species in the dataset. These visualizations provide insights into the data distribution and help in understanding the relationships between variables.

## 📊 Prediction One: Random Forest Classifier

The first prediction task involves using a Random Forest Classifier to classify bird species based on morphological features. The model's accuracy is evaluated on the testing set using confusion matrix visualization.

## 🌟 Feature Importance

Feature importance is analyzed using the Random Forest model. This helps in identifying the most important features that contribute to the classification task.

## 📈 Logistic Regression

Another prediction task is performed using Logistic Regression. The model's performance is evaluated using accuracy and confusion matrix.

## 📉 Prediction Two: Linear Regression

A linear regression model is built to predict the length of the humerus bone based on other morphological features. The model's performance is evaluated using mean squared error (MSE) and R-squared (R^2) score.

## 🔧 Tuning and Validation

Hyperparameter tuning and validation are performed using a Random Forest Classifier. Cross-validation, Recursive Feature Elimination (RFE), and grid search are employed to find the optimal hyperparameters for the model.

The notebook provides a comprehensive overview of the bird classification task, including data preprocessing, model building, evaluation, and validation steps. It serves as a guide for anyone interested in using machine learning techniques for bird species classification based on morphological features.

