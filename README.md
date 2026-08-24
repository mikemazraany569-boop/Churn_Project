# Supervised Learning Projects

This repository contains two supervised learning projects developed using Python and Scikit-learn.

The projects cover both major types of supervised learning:

- **Regression** — predicting a continuous numerical value.
- **Classification** — predicting a categorical outcome.

---

## 📁 Projects

### 1. Monthly Charges Prediction — Regression

The first project is a **regression model** that predicts how much a customer spends per month.

The target variable is:

#MonthlyCharges

## 2. Customer Churn Prediction — Classification

This project focuses on building a **classification model to predict whether a customer will churn (leave the company) or remain with the company**.

The target variable is `Churn`, which was encoded as:

- `0` → No Churn
- `1` → Churn

### Objective

The main objective is to identify customers who are at risk of leaving the company. This can help businesses take proactive actions, such as offering personalized services or retention strategies, before customers churn.

### Machine Learning Workflow

The project follows a complete supervised learning workflow:

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Handling missing values
5. Encoding categorical variables
6. Splitting the data into training and testing sets
7. Building baseline classification models
8. Hyperparameter tuning using `GridSearchCV`
9. Comparing different classification algorithms
10. Evaluating models using classification reports
11. Analyzing confusion matrices
12. Optimizing classification probability thresholds
13. Selecting the final model
14. Saving the trained model

### Models Tested

Four classification algorithms were tested and tuned:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

### Evaluation Metrics

The models were evaluated using:

- **Accuracy** — Overall percentage of correct predictions.
- **Precision** — Percentage of predicted churners who actually churned.
- **Recall** — Percentage of actual churners correctly identified.
- **F1-score** — Balance between precision and recall.
- **ROC-AUC** — Measures the model's ability to distinguish between churners and non-churners.
- **Confusion Matrix** — Shows true positives, true negatives, false positives, and false negatives.

