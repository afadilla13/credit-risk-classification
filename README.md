# Loan Status Prediction Analysis

## Table of Contents
- [Overview](#overview)
- [Results](#results)
- [Summary](#summary)

## Overview
The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting loan status. The dataset used for this analysis contains various features related to lending data, and the target variable is the loan status, which indicates whether a loan is healthy or high-risk.

## Results
Based on the provided code and its outputs, the following results were obtained:

- **healthy loans (0)**: 
  - The model boasts a precision of 1.00 and a recall of 0.99, resulting in an impressive f1-score of 1.00. This indicates that the model is highly accurate and reliable in identifying loans that are healthy.
  
- **high-risk loans (1)**:
  - The model has a precision of 0.85 and a recall of 0.91, leading to an f1-score of 0.88. While this is slightly lower than the metrics for healthy loans, it's still commendable, especially considering the challenges often associated with predicting high-risk categories.

The exact values for precision and recall can be obtained from the `classification_report` function.

## Summary
The logistic regression model provides a method to predict the loan status based on the given features. By evaluating the model using metrics like accuracy, precision, and recall, we can gauge its performance and reliability.

**Recommendation**: 
Based on the results, the model demonstrates exceptional performance in predicting both "healthy loans" and "high-risk loans".

The overall accuracy of the model is 0.99, which is outstanding. The macro average f1-score of 0.94 and the weighted average f1-score of 0.99 further emphasize the model's robustness and balanced performance across both classes.

In conclusion, the logistic regression model does a commendable job predicting both the 0 (healthy loan) and 1 (high-risk loan) labels, making it a valuable tool for decision-making in loan assessments.
