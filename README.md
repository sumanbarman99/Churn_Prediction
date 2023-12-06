# Telecom Churn Prediction | Classification

## Overview

Welcome to the Telecom Churn Prediction project! This classification project aims to predict customer churn using a dataset with 4250 samples. Each sample has 19 features, and the target feature is a boolean variable indicating churn. The project involves comprehensive data analysis, feature engineering, handling class imbalance using SMOTE, and applying three different classification models: Logistic Regression, AdaBoost, and Random Forest. The best-performing model, Random Forest Classifier, achieved an accuracy of 0.912 after hyperparameter tuning using RandomizedSearchCV.

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Data Analysis](#data-analysis)
- [Feature Engineering](#feature-engineering)
- [Handling Class Imbalance](#handling-class-imbalance)
- [Classification Models](#classification-models)
  - [Logistic Regression](#logistic-regression)
  - [AdaBoost](#adaboost)
  - [Random Forest](#random-forest)
- [Best Model and Results](#best-model-and-results)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)

## Dataset Overview

The dataset consists of 4250 samples, each with 19 features, and a binary target feature indicating customer churn.

## Data Analysis

The project begins with thorough Univariate and Bivariate analysis to understand the distribution and relationships of the features. Exploratory data analysis is crucial for gaining insights and identifying patterns that may influence customer churn.

## Feature Engineering

Feature engineering involves creating new features or transforming existing ones to enhance the predictive power of the models. This step is essential for capturing relevant information and improving model performance.

## Handling Class Imbalance

The class imbalance problem is addressed using the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE generates synthetic samples for the minority class to balance the distribution, preventing bias toward the majority class during training.

## Classification Models

### Logistic Regression

Logistic Regression is a fundamental classification algorithm used to model the probability of a binary outcome.

### AdaBoost

AdaBoost is an ensemble learning method that combines weak classifiers to create a strong classifier. It adapts by giving more weight to misclassified samples.

### Random Forest

Random Forest is an ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction.

## Best Model and Results

After evaluating the models, the Random Forest Classifier with hyperparameter tuning using RandomizedSearchCV emerged as the best performer, achieving an accuracy of 0.912.

## Getting Started

To get started with the project, follow these instructions:

### Dependencies

Make sure you have the following dependencies installed:

- Python (>=3.6)
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- imbalanced-learn (for SMOTE)
