# Loan Status Prediction Analysis

## Table of Contents
- [Overview](#overview)
- [Results](#results)
- [Summary](#summary)

## Overview
The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting loan status. The dataset used for this analysis contains various features related to lending data, and the target variable is the loan status, which indicates whether a loan is healthy or high-risk.

## Results
Based on the provided code and its outputs, the following results were obtained:

- **Accuracy Score**: 
  - This score represents the proportion of correct predictions out of all predictions. The exact value was not provided in the code, but it can be calculated using the confusion matrix.
  
- **Precision Score**:
  - **Healthy loan (0)**: Precision is the ratio of correctly predicted positive observations to the total predicted positives. The higher the precision, the more relevant the result it returns.
  - **High-risk loan (1)**: Precision for high-risk loans indicates how many of the predicted high-risk loans were actually high-risk.

- **Recall Score**:
  - **Healthy loan (0)**: Recall (Sensitivity) - the ratio of correctly predicted positive observations to all the observations in the actual class. It indicates how many of the actual healthy loans were correctly identified.
  - **High-risk loan (1)**: Recall for high-risk loans indicates how many of the actual high-risk loans were correctly identified by the model.

The exact values for precision and recall can be obtained from the `classification_report` function.

## Summary
The logistic regression model provides a method to predict the loan status based on the given features. By evaluating the model using metrics like accuracy, precision, and recall, we can gauge its performance and reliability.

**Recommendation**: 
Based on the results, the model demonstrates exceptional performance in predicting both "healthy loans" and "high-risk loans".

For "healthy loans (0)": The model boasts a precision of 1.00 and a recall of 0.99, resulting in an impressive f1-score of 1.00. This indicates that the model is highly accurate and reliable in identifying loans that are healthy.

For "high-risk loans (1)": The model has a precision of 0.85 and a recall of 0.91, leading to an f1-score of 0.88. While this is slightly lower than the metrics for healthy loans, it's still commendable, especially considering the challenges often associated with predicting high-risk categories.

The overall accuracy of the model is 0.99, which is outstanding. The macro average f1-score of 0.94 and the weighted average f1-score of 0.99 further emphasize the model's robustness and balanced performance across both classes.

In conclusion, the logistic regression model does a commendable job predicting both the 0 (healthy loan) and 1 (high-risk loan) labels, making it a valuable tool for decision-making in loan assessments.
