# Churn Decision Tree

This project involves two tasks related to predicting customer churn using the **Customer Churn Dataset**.

Customer Churn Dataset
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

## Tasks Overview

### Task 1: Data Preprocessing and Feature Engineering
- Clean and preprocess the data using **Pandas**.
- Handle missing values, perform **Z-score normalization**, **binning** of the "Total Spend" attribute, and **one-hot encoding** for "Contract Length".
- Create a new feature based on existing data.

### Task 2: Implementing a Decision Tree Classifier
- Implement three decision tree classifiers using **Information Gain**, **Gain Ratio**, and **Gini Index** for splitting.
- Combine these models into an **ensemble classifier** using a voting mechanism.

## What I Learned
- **Data Preprocessing**: Techniques like handling missing values, normalization, and feature engineering.
- **Decision Trees**: How to implement decision trees from scratch using different criteria (Information Gain, Gain Ratio, and Gini Index).
- **Ensemble Methods**: Combining multiple classifiers to improve performance.
  
## Requirements

- **Pandas** and **NumPy** for data manipulation and computations.
- **Matplotlib** for optional visualizations.
