# credit_risk_analysis

The project here aims at modeling the risk at which the finance firms loan their money to customers. This is done by following the steps given below.

1) Read the csv file and use the following features to calculate probability of default:

Features used: Income, Age, Home ownership, Employment length, Loan intent, Percent income, Loan grade, Loan amount, Interest rate, Loan status, Historical default, Credit history length.

2) Clean and prep the data for the modeling.

3) Use Logistic regression/ XGBoost to train the model and calculate probability of default

4) assign a threshold of probability of default such that the Recall value of measuring number of defaults in the test data is maximum.

5) Use the parameters and the model that gave maximum roc_auc_score, recall score. 

Observation: XGBoost performed the best.