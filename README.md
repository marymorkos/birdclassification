# Bird Classification Project

## Overview
This repository contains code and resources for a bird classification project. The project involves cleaning and preprocessing a dataset containing morphological measurements of various bird species, exploring the data visually, building machine learning models for bird classification, and evaluating their performance.

## Data Cleaning and Preprocessing
The project begins with loading the dataset from Kaggle.com (https://www.kaggle.com/datasets/zhangjuefei/birds-bones-and-living-habits/data) and performing initial data cleaning and preprocessing steps. This includes handling missing values by filling them with the mean of each numerical column, and dropping unnecessary columns.

## Data Visualization
Visualizations are created to gain insights into the dataset. Boxplots and countplots are used to visualize the distribution of morphological measurements across different types of birds.

## Model Development and Evaluation
Two machine learning models are developed and evaluated for bird classification: Random Forest Classifier and Logistic Regression. The models are trained on the preprocessed data and evaluated using accuracy scores and confusion matrices. Feature importance is visualized to understand the significance of different features in predicting bird types.

## Cross-Validation
K-Fold Cross-Validation is performed to validate the model performance and assess its generalization ability. Mean cross-validation score is calculated to evaluate the average performance of the model across different folds.

## Feature Selection
Feature selection is conducted using SelectFromModel method to select the most important predictors based on feature importances provided by the model.

## Parameter Tuning
A parameter tuning process is carried out using GridSearchCV to optimize the regularization strength parameter (C) in Logistic Regression. The mean cross-validation score is visualized across different values of C to identify the optimal parameter setting.

---

This README provides an overview of the project, its components, and the methodologies used for data cleaning, visualization, model development, and evaluation. For detailed implementation and code, please refer to the provided Jupyter notebook.
