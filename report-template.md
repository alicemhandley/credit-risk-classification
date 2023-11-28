# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to build a machine learning model that can predict the creditworthiness of borrowers. We used a dataset of historical lending activity from a peer-to-peer lending services company. The model was trained to identify the risk of loan default.

## Results

The performance of the logistic regression model was evaluated using accuracy, precision, and recall scores. Here are the results:

Accuracy Score: The model had an overall accuracy of 0.99, indicating that it made the correct prediction for 99% of the loans in the test set.

Precision Score: The model had a precision of 1.00 for healthy loans and 0.85 for high-risk loans. This means that almost all loans that the model identified as healthy were indeed healthy, and 85% of the loans that the model identified as high-risk were indeed high-risk.

Recall Score: The model had a recall of 0.99 for healthy loans and 0.91 for high-risk loans. This means that the model was able to correctly identify 99% of all actual healthy loans and 91% of all actual high-risk loans.

## Summary

The logistic regression model performed very well in predicting both healthy and high-risk loans. With high accuracy, precision, and recall scores, the model demonstrated a strong ability to correctly classify loans based on their risk of default.

Given these results, I would recommend the use of this model for the company's decision-making process. The model's high precision means that the company can trust the model's predictions when it identifies a loan as high-risk or healthy. The high recall means that the model is able to correctly identify a high percentage of all actual high-risk and healthy loans.

However, it's important to note that while the model performs well on this dataset, its performance may vary with different data. Therefore, it's recommended to continuously evaluate the model's performance as new data becomes available. 

