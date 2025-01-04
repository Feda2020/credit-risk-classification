# Overview of the Analysis

The purpose of this analysis was to develop and evaluate a machine learning model to predict credit risk. Specifically, we wanted to determine whether loans are high-risk (1) or healthy (0) based on financial data provided. This information helps financial institutions assess the risk associated with lending and make informed decisions.

The dataset included the following financial variables:

* loan_size
* interest_rate
* borrower_income
* debt_to_income
* num_of_accounts
* derogatory_marks
* total_debt
* loan_status (the target variable)

The loan_status column was used as the label for classification. It had the following distribution:

* **Healthy loans (0):** Predominantly represented in the dataset.
* **High-risk loans (1):** Underrepresented, requiring careful attention to class imbalance during model evaluation.

The analysis followed these stages:

1. Loading and preparing the data.
2. Splitting the data into training and testing sets.
3. Training a logistic regression model.
4. Evaluating the model using a confusion matrix and classification report.

The primary method used was Logistic Regression, which is a simple yet effective classification algorithm.

## Results

**Logistic Regression Model:**

* **Accuracy:** 99%

* **Precision:**

    * For 0 (healthy loans): 100%

    * For 1 (high-risk loans): 84%

* **Recall:**

    * For 0 (healthy loans): 99%

    * For 1 (high-risk loans): 94%

* **F1-Score:**

    * For 0 (healthy loans): 100%

    * For 1 (high-risk loans): 89%

**The confusion matrix revealed:**

* True negatives (correctly predicted healthy loans): 18,655

* False positives (incorrectly predicted high-risk loans): 110

* False negatives (missed high-risk loans): 36

* True positives (correctly predicted high-risk loans): 583

## Summary

The logistic regression model performed exceptionally well in predicting healthy loans (0), achieving near-perfect precision, recall, and F1-score. However, its performance was slightly weaker for high-risk loans (1), with a precision of 84% and an F1-score of 89%.

Given the financial implications of misclassifying high-risk loans, it may be more critical to improve the model's precision for this class. Even though the current model is strong overall, but other techniques such as exploring alternative algorithms could further enhance its ability to predict high-risk loans.

**Recommendation:**

* The logistic regression model is suitable for deployment with its current configuration for general credit risk prediction.
* If prioritizing the identification of high-risk loans, additional model tuning and exploration of techniques to handle class imbalance are recommended.