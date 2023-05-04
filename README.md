# Fraud-Detection
PySpark-Spark MLlib  

### Machine learning using Spark MLlib - PySpark

#### Problem Statement:
Financial fraud is the act of deceiving and scamming people out of their money. The strategy, scope, and scale of financial crimes are expanding in this age of digital technology, affecting everything from credit card transactions to health benefits to insurance claims.  
According to a PwC survey, 50% of the 7,200 organisations they looked at had experienced fraud of some form. A relatively recent report by FICO indicates, fraud activities have increased at 4 out of 5 banks surveyed, and this trend is projected to continue. So, the purpose of this Project is to build a robust ML model, that could predict financial fraud from a publicly available dataset, using Spark MLlib.  


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

#### MLlib in PySpark  
The MLlib machine learning API is offered by Apache Spark. The PySpark framework in Python also provides access to this API. There are both supervised and unsupervised machine learning techniques available. It is a framework for PySpark Core that makes it possible to analyse data using machine learning techniques. It uses distributed systems and is scalable. Machine learning techniques for classification, clustering, linear regression, and other applications are implemented in PySpark MLlib.  
Machine learning techniques can be used on huge datasets thanks to Spark's scalable machine learning library, MLlib. In-memory processing, fault tolerance, scalability, speed, and programming simplicity are all features of Spark's parallel computing architecture. Consequently, iterative machine learning methods are effectively used on spark.  


#### Spark ML Pipeline  
A pipeline connects several estimators and transformers to specify an ML workflow. Additionally, it provides tools for developing, analysing, and optimising ML Pipelines.  
Running several algorithms in machine learning is normal to process data and learn from it. Such a workflow is represented in MLlib by a pipeline, which is made up of several pipeline stages that need to be carried out in a specific order.
The stages of the pipeline defined act as a chain of command for Spark to run


#### Model Training and Evaluation:  
First, the dataset is divided into training and testing sets for the purpose of training. Then, as it works well for binary classification problems, the model is trained using logistic regression algorithm.
To see how Logistic Regression performed, Area Under ROC curve is used, (which is a standard metric for evaluating binary classification) as the metric to evaluate the model.  








