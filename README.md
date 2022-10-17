# ADS505-Final-project

The goal of this project is to predict for churn and identify features that contribute to churn for MultiState Bank. 

Data mining models -- K-NN, logistic regression, random forest, XGBoost, and SVM -- will be utilized to make predictions and find insights that can be communicated to the bank's business leaders.

With these findings in mind, churn can be limited while creating optimal strategies for pushing the business forward.

The data we are using has the following descriptions:

### Number of records: 1000

### Number of features: 13, including target variable

### Feature names:

Customer_id -- Account number
credit_score -- Credit score (numerical)
country -- country of residence (categorical)
gender -- Sex (categorical)
age -- customer's Age (numerical)
tenure -- Years of owning bank account (numerical)
balance -- Balance in dollars (Numerical)
products_number -- Number of products from bank (numerical)
credit_card -- 1/0 if a customer has a credit card or not
active_member -- 1/0 if an active member of the bank
estimated_salary -- salary of account holder (numerical)
churn -- 1/0 for churn status

There are roughly 2000 records for churn and 8000 for non-churn, so this data is imbalanced as well for the classification problem.

The final notebook with the final modeling, results, and explanations are in the main branch under ADS505-FinalProject-ChrunPrediction. The link is here: https://github.com/ruddysimon/ADS505-Finall-project/blob/main/ADS505-FinalProject-ChrunPrediction.ipynb
