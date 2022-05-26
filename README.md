# Telco-Customer-Churn-Prediction


This is my first project in machine learning.

This is a classification machine learning problem for predicting customers churn from the company based on customers who left within the last month labeled by 'yes' or 'no'.

# Data Source
 <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn"> IBM sample dataset </a>.
 
 # Data Attributes

The dataset has the following information:

 - Identifier
    - customerID - ID number of the customer

- Target Variable
    - Churn - Churn status, whether the customer churned or not

- Demographic information
    - gender - Whether the customer is a male or a female
    - SeniorCitizen - Whether the customer is a senior citizen or not
    - Partner - Whether the customer has a partner or not
    - Dependents - Whether the customer has dependents or not

- Customer account information
    - tenure - Number of months the customer has used the service
    - Contract - The contract term of the customer
    - PaperlessBilling - Whether the customer has paperless billing or not
    - PaymentMethod - The customer’s payment method
    - MonthlyCharges - The amount charged to the customer monthly
    - TotalCharges - The total amount charged to the customer

- Services that each customer has signed up for
    - PhoneService - Whether the customer has a phone service or not
    - MultipleLines - Whether the customer has multiple lines or not
    - InternetService - Customer’s internet service provider
    - OnlineSecurity - Whether the customer has online security or not
    - OnlineBackup - Whether the customer has online backup or not
    - DeviceProtection - Whether the customer has device protection or not
    - TechSupport - Whether the customer has tech support or not
    - StreamingTV - Whether the customer has streaming TV or not
    - StreamingMovies - Whether the customer has streaming movies or not

# Methods
- Exploratory data analysis (Univariate, Multivariate analysis)
- Descriptive analysis
- Multivariate correlation
- Predictive analysis
- Model deployment
- Model Evaluation

# Quick glance at the results
Correlation between the features.

<img src="https://github.com/xplict33/Telco-Customer-Churn-Prediction/blob/main/images/cor.png" width="600" height="400">

Confusion matrix

<img src="https://github.com/xplict33/Telco-Customer-Churn-Prediction/blob/main/images/confussion.png" width="600" height="400">

ROC Curve

<img src="https://github.com/xplict33/Telco-Customer-Churn-Prediction/blob/main/images/roc.png" width="600" height="400">

**Scores**

| Score  | In % |
| ------------- | ------------- |
| Accuracy  | 78.2 |
| Precision  | 61.96 |
| Recall     | 44.3 |
| ROC AUC    | 0.808 |

Precision: 61.96473551637279
Accuracy: 78.19905213270142
Recall: 44.32432432432433
