# MODULE 20: credit-risk-classification

Assignment: Develop a model to assess the creditworthiness of borrowers.

# Steps to Build the Model:

1)Data Preprocessing

Imported the dataset and conducted an in-depth analysis of its structure and summary statistics.

Segregated the data into features (X) and labels (y).

2)Data Splitting

Partitioned the data into training and testing sets using the train_test_split function.

3)Model Development

Constructed a Logistic Regression model utilizing the training data.

4)Model Evaluation

Assessed the model's performance using the testing data.

Created a confusion matrix to visualize the model's predictions.


# Credit Risk Analysis Report:


Introduction:

In this analysis, we engineered a model capable of forecasting loan outcomes based on various parameters such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The model classifies loans into two categories: healthy loans (labeled as 0) and high-risk loans (labeled as 1) under the "loan status" column.


Results:

The model exhibited the following predictions:

-Successfully identified 18,663 healthy loans and misclassified 102 healthy loans as high-risk.

-Successfully dentified 563 high-risk loans and misclassified 56 high-risk loans as healthy loans.


Model Performance Metrics:

-Accuracy: 99%

-Precision: Achieved 100% for healthy loans and 85% for high-risk loans.

-Recall: Attained 99% for healthy loans and 91% for high-risk loans.


Conclusion:

The machine learning model demonstrated strong performance with a 99% accuracy rate. However, it's crucial to acknowledge that the model's efficacy may be impacted by the dataset's imbalance. To enhance the model's reliability, utilizing balanced data is recommended. Furthermore, special attention should be given to the prediction of high-risk loans, as misclassifying them could have significant repercussions.
