# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to utilize historical lending information about borrowers in order to determine which loans would be healthy or high-risk.
* The financial information collected is based on 7 borrower feautures which included loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt to try and predict healthy or high-risk borrowers. 
* The goal of the model is to predict the loan_status as healthy or high-risk.
* The machine learning steps involved splitting the data into testing and training data sets utilizing 7 borrower features, fitting the model utilizing machine learning algorithims, predicting the loan status based on a 'LogisticRegression'model, and reviewing the performance of the model by reviewing a classification report. 
* The following machine learning techniques were used: 'LogisticRegression', 'balanced_accuracy_score','confusion_matrix', 'classification_report_imbalanced', and 'RandomOverSampler'

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Precision, Recall, and Accuracy scores.
    *Healthy: 1.00    **100% precision of true positives to sum of true and false positives
              0.99    **99% ratio of true positives to the sum of true positives and false negatives.
              1.00    **The F1 is the weighted harmonic mean of precision and recall. The closer the value of the F1 score is to 1.0, the better the expected   performance of the model is.
    *High-risk: 0.85  **85% precision of true positives to sum of true and false positives
                0.91  **91% ratio of true positives to the sum of true positives and false negatives.
                0.88  **The F1 is the weighted harmonic mean of precision and recall. The closer the value of the F1 score is to 1.0, the better the expected   performance of the model is. Lower performance compared to healthy.



* Machine Learning Model 2:
  * Description of Model 2 Precision, Recall, and Accuracy scores.
    *Healthy: 1.00    **100% precision of true positives to sum of true and false positives
              0.99    **99% ratio of true positives to the sum of true positives and false negatives.
              1.00    **The F1 is the weighted harmonic mean of precision and recall. The closer the value of the F1 score is to 1.0, the better the expected   performance of the model is.
    *High-risk: 0.84   **84% precision of true positives to sum of true and false positives
                0.99   **99% ratio of true positives to the sum of true positives and false negatives.
                0.91   **The F1 is the weighted harmonic mean of precision and recall. The closer the value of the F1 score is to 1.0, the better the expected   performance of the model is. Lower performance compared to healthy, but improved when oversampling.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Machine Learning Model #2 is recommended because it has better performance with recall which results in a higher F1 score. Both models perform identically for predicting healthy loans.
* It is most important to be accurate predicting true-positives for high-risk borrowers. Because Model #2 does this the best it is the recommended model. 

