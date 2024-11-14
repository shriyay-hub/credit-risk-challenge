# Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis is to develop and evaluate a machine learning model that predicts the creditworthiness of potential borrowers based on historical lending data from a peer-to-peer lending company. By identifying high- and low-risk borrowers, the model aims to enhance the decision-making process, reducing the likelihood of loan defaults and ensuring better management of risk.

## Results

### Model with Original Data
- **Balanced Accuracy Score**: 95.20%
- **Precision Score**: 92%
  - Indicates that 92% of predicted high-risk loans were accurately identified.
- **Recall Score**: 95%
  - Reflects that the model correctly identified 95% of true positive values for high-risk loans.

### Model with Resampled Data
- **Balanced Accuracy Score**: TBD (calculated with resampled data)
- **Precision Score**: TBD
- **Recall Score**: TBD

## Summary

The logistic regression model with the original data demonstrated high accuracy, precision, and recall, suggesting it is effective for predicting borrower creditworthiness. However, due to the initial imbalance in the dataset (fewer high-risk loans), the model was re-evaluated using a resampled training dataset with equal instances of high- and low-risk labels. This second evaluation aims to verify if oversampling improves model performance, particularly for identifying high-risk loans.

