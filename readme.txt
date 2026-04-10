# Customer Churn Prediction - Telco Dataset

## Overview
This project focuses on analyzing customer churn in a telecommunications company. The goal is to predict whether a customer will churn based on various factors like tenure, service usage, and demographic information. The dataset used in this project is the "Telco Customer Churn" dataset from Kaggle, which provides details of customers' information and whether they churned.

## Dataset
The dataset contains customer information, including:
- **customerID**: Unique identifier for each customer.
- **gender**: Gender of the customer.
- **SeniorCitizen**: Whether the customer is a senior citizen (1 or 0).
- **Partner**: Whether the customer has a partner (Yes/No).
- **Dependents**: Whether the customer has dependents (Yes/No).
- **tenure**: Number of months the customer has been with the company.
- **PhoneService**: Whether the customer subscribes to phone service (Yes/No).
- **MultipleLines**: Whether the customer has multiple phone lines (Yes/No).
- **InternetService**: Type of internet service the customer has (DSL/Fiber optic/No).
- **Contract**: Type of contract the customer has (Month-to-month/One year/Two year).
- **PaymentMethod**: Method of payment used by the customer (Electronic check/Mailed check/Bank transfer/credit card).
- **MonthlyCharges**: Monthly charges for the customer’s service.
- **TotalCharges**: Total amount charged to the customer.
- **Churn**: Whether the customer has churned (Yes/No).

## Installation
To run this project, you will need to install the following Python libraries:
- pandas
- kagglehub (for downloading datasets from Kaggle)

You can install these libraries using `pip`:
```bash
pip install pandas kagglehub
