# Customer Churn Prediction

## Project Overview

Customer churn is one of the most important business problems in subscription-based industries such as telecommunications. Acquiring new customers is significantly more expensive than retaining existing ones.

This project builds an end-to-end machine learning pipeline to predict whether a customer is likely to churn based on demographic, contract, and service-related information.

---

## Business Objective

Predict customer churn and identify the factors that contribute most to customer attrition.

The insights generated from this model can help businesses:

* Improve customer retention
* Reduce revenue loss
* Design targeted retention campaigns
* Understand churn drivers

---

## Dataset

Dataset: IBM Telco Customer Churn Dataset

Features include:

* Customer demographics
* Contract type
* Internet service
* Payment method
* Monthly charges
* Total charges
* Customer tenure

Target Variable:

* Churn (Yes / No)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-Learn
* XGBoost
* SHAP
* Streamlit

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Data Preprocessing
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. SHAP Explainability
9. Streamlit Deployment

---

## Exploratory Data Analysis

Key findings:

* Month-to-month customers churn more frequently.
* Customers with shorter tenure are more likely to churn.
* Higher monthly charges are associated with higher churn rates.

(Add screenshots here)

---

## Models Evaluated

### Logistic Regression

Baseline interpretable model.

### Random Forest

Improved performance through ensemble learning.

### XGBoost

Best performing model on the dataset.

---

## Evaluation Metrics

Metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Example Results:

| Model               | Accuracy | F1 Score | ROC-AUC |
| ------------------- | -------- | -------- | ------- |
| Logistic Regression | XX       | XX       | XX      |
| Random Forest       | XX       | XX       | XX      |
| XGBoost             | XX       | XX       | XX      |

---

## SHAP Explainability

SHAP was used to understand the contribution of individual features to churn predictions.

Top churn drivers:

* Contract Type
* Tenure
* Monthly Charges
* Internet Service

(Add SHAP screenshot)

---

## Streamlit Application

The deployed application allows users to:

* Enter customer information
* Receive churn probability predictions
* Assess customer risk level

---

## Future Improvements

* Deep learning models
* Advanced feature engineering
* Real-time prediction API
* Cloud deployment

---

## Author

Swapnil

LinkedIn:  LinkedIn URL

GitHub:  GitHub URL
