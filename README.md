# Customer Churn Prediction using SVM

This project uses Support Vector Machine (SVM) to predict customer churn based on various features. The model has been trained and tested on a dataset with an accuracy of 80%.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Evaluation](#model-evaluation)

## Project Overview

Customer churn prediction is a critical task for businesses to retain customers and understand factors leading to churn. This project uses the **Support Vector Machine (SVM)** algorithm to predict whether a customer will leave the company based on various features, such as customer service usage and demographics.

The model achieved an accuracy of 80% during testing, making it a good candidate for churn prediction. The project demonstrates how machine learning can be applied to real-world business problems.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- Numpy

## Dataset

The dataset used in this project contains customer data with several features. The target variable is whether the customer has churned (left the company). Below are the columns of the dataset:

### Dataset Features:
- **SeniorCitizen**: Whether the customer is a senior citizen (1 or 0).
- **Partner**: Whether the customer has a partner (Yes or No).
- **Dependents**: Whether the customer has dependents (Yes or No).
- **Tenure**: Number of months the customer has been with the company.
- **PhoneService**: Whether the customer has phone service (Yes or No).
- **MultipleLines**: Whether the customer has multiple lines (Yes, No, or No phone service).
- **InternetService**: Type of internet service the customer has (DSL, Fiber optic, or No).
- **OnlineSecurity**: Whether the customer has online security (Yes, No, or No internet service).
- **OnlineBackup**: Whether the customer has online backup (Yes, No, or No internet service).
- **DeviceProtection**: Whether the customer has device protection (Yes, No, or No internet service).
- **TechSupport**: Whether the customer has tech support (Yes, No, or No internet service).
- **StreamingTV**: Whether the customer has streaming TV (Yes, No, or No internet service).
- **StreamingMovies**: Whether the customer has streaming movies (Yes, No, or No internet service).
- **Contract**: Type of contract the customer has (Month-to-month, One year, or Two year).
- **PaperlessBilling**: Whether the customer has paperless billing (Yes or No).
- **PaymentMethod**: The customer's payment method (Electronic check, Mailed check, Bank transfer, or Credit card).
- **MonthlyCharges**: The monthly charges for the customer.
- **TotalCharges**: The total charges for the customer.
- **Churn**: Whether the customer has churned (Yes or No). This is the target label.

### Target Label:
- **Churn**: "Yes" indicates the customer has churned, "No" indicates the customer has stayed.

## Model Evaluation

The SVM model was evaluated using the following metrics:

- **Accuracy**: 80%
- **Confusion Matrix**: Displays the number of true positives, true negatives, false positives, and false negatives.
