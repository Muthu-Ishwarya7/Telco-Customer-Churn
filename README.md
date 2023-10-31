# Telco-Customer-Churn
# ***Enhancing Customer Retention in Telco: A Churn Prediction with Ensemble Learning***

## **Business Objectives**

Churn is referred to customers who left within the last month, and this phenomenon affects sales number as well as business revenue. The reason for this to happen could be related to the level of customer satisfaction. Therefore, the business objectives could be set to reduce customer churn to increase revnue, and improving customer satisfaction.

In order to reduce customer churn, it is necessary to predict which customers are at high risk of churn by detecting early signs of churn existing in different sales channels.

# **About Dataset**
## Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs."

## Content
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

# **The data set includes information about:**

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

# **About Feature**

## Target:
- **Churn Label**: Whether the customer churned or not (Yes or No)

## Numeric Features:
- **tenure**: Number of months the customer has stayed with the company
- **Monthly Charges**: The amount charged to the customer monthly
- **Total Charges**: The total amount charged to the customer

## Categorical Features:
- **customerID**: Customer ID
- **gender**: Whether the customer is a male or a female
- **Senior Citizen**: Whether the customer is a senior citizen or not (1, 0)
- **Partner**: Whether the customer has a partner or not (Yes, No)
- **Dependents**: Whether the customer has dependents or not (Yes, No)
- **Phone Service**: Whether the customer has a phone service or not (Yes, No)
- **Multiple Lines**: Whether the customer has multiple lines or not (Yes, No, No phone service)
- **Internet Service**: Customer’s internet service provider (DSL, Fiber optic, No)
- **Online Security**: Whether the customer has online security or not (Yes, No, No internet service)
- **Online Backup**: Whether the customer has online backup or not (Yes, No, No internet service)
- **Device Protection**: Whether the customer has device protection or not (Yes, No, No internet service)
- **Tech Support**: Whether the customer has tech support or not (Yes, No, No internet service)
- **StreamingTV**: Whether the customer has streaming TV or not (Yes, No, No internet service)
- **Streaming**: Whether the customer has streaming movies or not (Yes, No, No internet service)
- **Contract**: The contract term of the customer (Month-to-month, One year, Two year)
- **Paperless Billing**: Whether the customer has paperless billing or not (Yes, No)
- **Payment Method**: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

# **Implementations**
1. Imported Required Libraries
2. Data Extraction
3. Data Preparation
   1. Detecting Missing Values
   2. Detecting Outliers
   3. Label Encode Binary Data
4. Exploring Data Analysis
   1. Visualisng data
   2. Correlation between variables
   3. Identify Multicollinearity
5. Build Machine Learning Models
   1. kNN
   2. SVM
   3. Random Forest Classifier
   4. Decision Tree Classifier
   5. Logistic Regression
6. Improve Model Accuracy
   1. Feature Extraction/ Selection
   2. Standardisation
   3. Cross Validation
   4. Ensembling
        1. SVM with LR
        2. SVM with kNN
        3. SVM with DT
        4. SVM with RF
        5. LR with DT
        6. LR with kNN
        7. LR with RF
        8. DT with RF
        9. DT with kNN
        10. RF with kNN

7.Ensemble Model Performance

## **Identify Multicollinearity:**
Check for multicollinearity, which is the presence of high correlation between independent variables. Identifying multicollinearity is essential in regression modeling.

## **Standardization:**
Standardize or normalize your data to ensure that all features have the same scale.

## **Cross Validation:**
Implement cross-validation techniques to assess how well your models generalize to new, unseen data. This helps in preventing overfitting.

## **Ensembling:**
Consider building ensemble models that combine the predictions of multiple models to achieve better overall accuracy and robustness.
## Ensemble Models: 
In this stage, I've already built several individual machine learning models such as k-Nearest Neighbors (kNN), Support Vector Machine (SVM), Random Forest, Decision Tree, and Logistic Regression. Now, considering the use of ensemble methods to combine the predictions of these individual models. Ensemble methods are a powerful technique in machine learning, as they leverage the strengths of multiple models to make more accurate predictions.



