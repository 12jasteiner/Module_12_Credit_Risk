# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to determine the accuracy of a logistic regression model when using original data with a class imbalance compared with resampled (oversampled minority class) data.
* Loan lending data including: loan size, interest rate, debt-to-income ratio, etc. was used to predict if a potential borrower would default on their loan.
* These models were used to predict loan status (high-risk vs healthy).
* For this analysis we created/instanciated logistic regression models using separated training and test data. The models were fit to the training data and predictions were created. These predictions were evaluated against the test data to determine their recall/sensitivity, precision, F1 score, and other metrics useful in evaluating the model's relevence.
* Logistic regression was used to model the target (loan status). This model was used with original lending data and then again with resampled data (oversampled minority class) to acheive a more appropriately trained model. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy= 0.95
  * Precision_healthy= 1.00 ; precision_high-risk= 0.85
  * Recall_healthy= 0.99 ; recall_high-risk= 0.91


* Machine Learning Model 2:
  * Accuracy= 0.99
  * Precision_healthy= 1.00 ; precision_high-risk= 0.84
  * Recall_healthy= 0.99 ; recall_high-risk= 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Machine learning model 2, which used the resampled data, performed better. This improved performance is evidenced by a higher balanced accuracy score and 
Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
