# credit-risk-classification

### Description

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

### Info / Credits

- Analysis by `João Pedro Fortunato` [@joaopedrofortunato](https://github.com/joaopedrofortunato)

- `REPO:` https://github.com/joaopedrofortunato/credit-risk-classification.git

### Data Sources

(Resources/lending_data.csv)

### Output/Report

#### Overview of the Analysis

##### Purpose of the Analysis:
The primary goal of this analysis is to assess the creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services company. By predicting the likelihood of loan default, the lending services company can make informed decisions about whom to lend to, ultimately mitigating financial risk.

##### Data Overview:
The data used for this analysis comes from the lending_data.csv file, which encompasses several financial parameters and characteristics of the borrowers. The primary feature of interest is the loan_status column, which indicates whether a loan is healthy (0) or has a high risk of defaulting (1).

loan_status value distribution: (This would typically be where you put the result of a value_counts method to show the distribution of 0's and 1's).
Stages of the Machine Learning Process:

##### Data Cleaning and Preprocessing
Splitting the data into training and testing sets
Applying the Logistic Regression Model
Evaluating the model's performance using metrics like the confusion matrix, accuracy score, precision score, and recall score.
Methods Used:

- train_test_split for splitting the data
- LogisticRegression for building the predictive model

#### Results

* Logistic Regression Model:
Accuracy Score: [Put the accuracy score here, e.g., 90%]
Precision Score: [For both healthy loans and high-risk loans, e.g., 0.9 for healthy loans and 0.8 for high-risk loans]
Recall Score: [For both healthy loans and high-risk loans, e.g., 0.85 for healthy loans and 0.7 for high-risk loans]

* Logistic Regression Model:
Accuracy Score: [Put the accuracy score here, e.g., 90%]
Precision Score: [For both healthy loans and high-risk loans, e.g., 0.9 for healthy loans and 0.8 for high-risk loans]
Recall Score: [For both healthy loans and high-risk loans, e.g., 0.85 for healthy loans and 0.7 for high-risk loans]

#### Summary

Based on the results of the logistic regression model, the following insights can be drawn:

The logistic regression model showcased an accuracy of [Insert Accuracy Score], which signifies the proportion of true results (both true positives and true negatives) in the dataset.
Precision, which indicates the proportion of identified positives that were correct, stands at [Insert Precision Score for Healthy Loans] for healthy loans and [Insert Precision Score for High-Risk Loans] for high-risk loans.
Recall or sensitivity, representing the proportion of actual positives that were correctly identified, is at [Insert Recall Score for Healthy Loans] for healthy loans and [Insert Recall Score for High-Risk Loans] for high-risk loans.
Given these metrics, the logistic regression model seems to [perform adequately / not perform adequately]. The decision on whether this model is appropriate also depends on the specific requirements of the business. If, for instance, predicting high-risk loans (1s) is more crucial to avoid potential financial losses, then a model with a higher recall for the high-risk category would be ideal.

If you do not recommend any of the models, please justify your reasoning.
