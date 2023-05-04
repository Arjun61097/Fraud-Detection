# Fraud-Detection
PySpark-Spark MLlib  

#### Machine learning using Spark MLlib - PySpark
Dataset: Synthetic Financial Datasets for Fraud Detection.  
It is saved in a csv file called "PS_20174392719_1491204439457_log.csv".  
Dataset Link: https://www.kaggle.com/datasets/ealaxi/paysim1?datasetId=1069   
Variables/Columns:  
step - maps a unit of time in the real world  
type - CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER.  
amount - amount of the transaction in local currency.  
nameOrig - customer who started the transaction  
oldbalanceOrg - initial balance before the transaction  
newbalanceOrig - new balance after the transaction  
nameDest - customer who is the recipient of the transaction  
oldbalanceDest - initial balance recipient before the transaction  
newbalanceDest - new balance recipient after the transaction  
isFraud - This is the transactions made by the fraudulent agents  
isFlaggedFraud - The business aims to control massive transfers from one account to another and flags illegal attempts  

#### Services and libraries used:  
Python version 3.11   
Google Colab.  
Pyspark version v3.3.1  
Supervised ML algorithms: logistic regression.  



