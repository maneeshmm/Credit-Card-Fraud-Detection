# Credit Card Fraud Detection

## Introduction

Credit card fraud detection is a critical task in financial security, aiming to identify fraudulent transactions while minimizing false positives. This project applies machine learning techniques to classify transactions as fraudulent or legitimate using an imbalanced dataset.

## Data Description

The dataset consists of transactions with 30 numerical features obtained from a PCA transformation. The 'Class' variable indicates whether a transaction is fraudulent (1) or legitimate (0). Due to a significant class imbalance, resampling techniques were used to balance the dataset.

## Data Preprocessing

Checked for missing values and inconsistencies.

Applied feature scaling to standardize numerical features.

Conducted Exploratory Data Analysis (EDA) to understand feature distributions.

Addressed class imbalance using under-sampling and over-sampling techniques.

## Handling Class Imbalance

Under-Sampling: Reduced the number of majority class instances to balance the dataset.

Over-Sampling: Used SMOTE (Synthetic Minority Over-sampling Technique) to generate synthetic samples for the minority class.

## Machine Learning Models

### Logistic Regression

Applied to classify transactions based on extracted features.

Evaluated using precision, recall, and F1-score.

### Decision Tree Classifier

Implemented a tree-based approach for classification.

Compared model performance against Logistic Regression.

## Model Evaluation

Used accuracy, precision, recall, and F1-score as performance metrics.

Compared results before and after applying sampling techniques.

## Conclusion

The use of under-sampling and over-sampling improved model performance.

Decision Tree and Logistic Regression provided insights into fraud detection.

Balancing techniques play a crucial role in handling imbalanced datasets.
