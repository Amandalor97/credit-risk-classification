# MODULE 20: credit-risk-classification


Assignment:

Build a model that can identify the creditworthiness of borrowers.

1) Split the Data into Training and Testing Sets

2) Create a Logistic Regression Model with the Original Data

3) Write a Credit Risk Analysis Report

CREDIT RISK ANALYSIS REPORT: 

In this analysis we created a model that can predict the outcome of a loan depending on multiple factors: loan size,	interest rate,	borrower income,	debt to income,	number of accounts,	derogatory marks and total debt.
The model then divided the loans into two categories : healthy loans (marked as 0) and high-risk loans (marked as 1) in a single colum named : loan status.

STEPS TO CREATE THE MODEL:

1)Data Analysis: Imported the data and analyzed what we are working with. 
2)Labels and Features creation: We divided the data between features (X) and labels (y).
3)Testing and training datasets: We then used train_test_split in order to dispatch datasets into training or testing.
4)Logistic Regression: We used LogisticRegression on the different datasets. 
5)Prediction: Using confusion_matrix we generated a confusion matrix for the model.

RESULTS: 
-The model accurately predicted 18663 healthy loans and predicted 102 healthy loans as high-risk loans. 
-The model accurately predicted 563 high-risk loans and predicted 56 high-risk loans as healthy loans.
-Accuracy: 99%
-Precision: 100% for healthy loans and 85% for high-risk loans
-Recall: 99% for healthy loans and 91% for high-risk loans

CONCLUSION:
This machine learning model works very well and I would recommend the company to use it. However, I would also advise to pay attention to the prediction of high-risk loans because an imbalance of the dataset. 
By using balanced data this machine learning would be highly effective. 
