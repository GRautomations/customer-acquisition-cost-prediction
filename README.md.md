# Customer Acquisition Cost Prediction

Machine learning project to predict customer acquisition cost (CAC) for Food Mart X media campaigns using multiple regression and ensemble learning models.

## Project Background

This project was developed as part of a collaborative capstone during the PG Diploma in Computer Science & Artificial Intelligence (IIIT Delhi).

## Problem Statement

Predict the media campaign cost for acquiring customers based on:

- Customer details
- Product details
- Store details
- Promotion details

## Algorithms Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression (SVR)
- Gradient Boosting Regressor
- Artificial Neural Networks (ANN)

## Techniques Applied

- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- Label Encoding
- Exploratory Data Analysis
- Model Comparison
- Hyperparameter Tuning (GridSearchCV)

## Results

| Model | R2 Score |
|---|---|
| Linear Regression | 0.3286 |
| Decision Tree Regressor | 0.9773 |
| Random Forest Regressor | 0.9869 |
| Support Vector Regression | 0.0489 |
| Gradient Boosting Regressor | 0.5066 |
| ANN | 0.9862 |

## Best Performing Models

- Random Forest Regressor
- Decision Tree Regressor

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TensorFlow / Keras

## Repository Structure

- `customer_acquisition_cost_prediction.ipynb` → Main implementation notebook
- `foodmart_train_dataset.csv` → Training dataset
- `foodmart_test_dataset.xlsx` → Testing dataset
- `docs/` → Research paper and project presentation