# credit-risk-classification

### Description

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

### Info / Credits

- Analysis by `João Pedro Fortunato` [@joaopedrofortunato](https://github.com/joaopedrofortunato)

- `REPO:` https://github.com/joaopedrofortunato/credit-risk-classification.git

### Output/Report

#### Overview of the Analysis

##### Purpose of the Analysis:
The primary goal of this analysis is to assess the creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services company. By predicting the likelihood of loan default, the lending services company can make informed decisions about whom to lend to, ultimately mitigating financial risk.

##### Data Overview:
The data used for this analysis comes from the lending_data.csv file, which encompasses several financial parameters and characteristics of the borrowers. The primary feature of interest is the loan_status column, which indicates whether a loan is healthy (0) or has a high risk of defaulting (1).

##### Data Cleaning and Preprocessing
- Splitting the data into training and testing sets.
- Applying the Logistic Regression Model.
- Evaluating the model's performance using metrics like the confusion matrix, accuracy, precision, and recall scores.

##### Methods Used:
- train_test_split for splitting the data
- LogisticRegression for building the predictive model

#### Results

* Logistic Regression Model:
  * Accuracy Score: **95.2%**
  * Precision Score: **1.00** for healthy loans and **0.85** for high-risk loans
  * Recall Score: **0.99** for healthy loans and **0.91** for high-risk loans

* Logistic Regression Model with Resampled Training Data:
  * Accuracy Score: **99.4%**
  * Precision Score: **1.00** for healthy loans and **0.84** for high-risk loans
  * Recall Score: **0.99** for both healthy loans and high-risk loans
  
#### Summary

Based on the results of the logistic regression model, the following insights can be drawn:

The logistic regression model showcased an accuracy of 95.2, which signifies the proportion of true results (both true positives and true negatives) in the dataset.
Precision, which indicates the proportion of identified positives that were correct, stands at 1.00 for healthy loans and 0.85 for high-risk loans.
Recall or sensitivity, representing the proportion of actual positives that were correctly identified, is at 0.99 for healthy loans and 0.91 for high-risk loans.

On the other hand, the Logistic Regression Model with Resampled Training Data showcased an accuracy of 99.4, which signifies the proportion of true results (both true positives and true negatives) in the dataset.
Precision, which indicates the proportion of identified positives that were correct, stands at 1.00 for healthy loans and 0.84 for high-risk loans.
Recall or sensitivity, representing the proportion of actual positives that were correctly identified, is at 0.99 for both healthy loans and high-risk loans.

Given these metrics, the Logistic Regression Model with Resampled Training Data seems to perform better than just Logistic Regression Model itself. The decision on whether this model is appropriate also depends on the specific requirements of the business, but the Logistic Regression Model with Resampled Training Data seems to attend the requirements for the decision-making.

#### Recommendation:
Based on the results and the specific requirements of the lending services company, I would recommend the use of the Logistic Regression Model with Resampled Training Data for predicting loan default risks. The justification for this decision is based on its performance metrics and alignment with business goals.
