# credit-risk-classification

## Table of contents

* [Overview](#Overview)
* [Key Objectives](#Key-Objectives)
* [Steps](#Steps)
* [Results and Insights](#Results-and-Insights)
* [Key Question Answered](#Key-Question-Answered)
* [Questions](#Questions)
* [References](#References)

## Overview

This project focuses on predicting credit risk using a logistic regression model. The analysis involves evaluating the performance of the model in predicting high-risk and healthy loans based on financial data. Metrics like accuracy, precision, recall, and F1-score are used to assess the model's effectiveness.

## Key Objectives

1. Preprocess and analyze the financial data for training and testing the model. 
2. Train a logistic regression model to predict the loan status.
3. Evaluate the model’s performance using confusion matrix and classification reports. 
4. Provide insights and recommendations based on the evaluation results.

## Steps

1. **Data Preprocessing**

* Load the dataset and inspect its structure.
* Separate features and labels (loan_status) for training.
* Split the data into training and testing sets.

2. **Model Training**

* Use a logistic regression model with the training dataset.

3. **Performance Evaluation**

* Generate predictions on the test dataset.
* Create a confusion matrix to visualize the model’s performance.
* Generate a classification report to review precision, recall, F1-score, and accuracy.

4. **Insights and Recommendations**

* Analyze the model’s performance for predicting high-risk and healthy loans.
* Identify areas for improvement and suggest future steps.

## Results and Insights

* **Healthy Loans (0):** The model achieves near-perfect predictions, with high precision, recall, and F1-scores.

* **High-Risk Loans (1):** While performance is slightly lower, the model shows good precision and recall in identifying high-risk loans.

* **Overall:** The logistic regression model demonstrates strong accuracy (99%).

## Key Question Answered

**How well does the logistic regression model predict credit risk?**

The model effectively predicts healthy loans with near-perfect metrics. Its performance in identifying high-risk loans is strong but can be further improved by addressing class imbalance or exploring advanced techniques like using alternative algorithms.

## Questions

In case of any additional questions please visit my GitHub link: [Feda](https://github.com/Feda2020)

## References

* Stach Overflow (https://stackoverflow.com/)
* Xpert Learning (https://bootcampspot.com)
* Scikit-Learn Documentation (https://scikit-learn.org/)