# Loan-Prediction-System

A Loan Prediction System helps financial institutions assess the eligibility of applicants for home loans. This system utilizes machine learning to evaluate applicants based on various criteria, identifying which customers are eligible for loans and providing insights into factors preventing other applicants from qualifying. This approach allows banks to streamline loan approval processes while guiding non-qualifying applicants on ways to improve their eligibility for future applications.

## Project Objective

The main objective of this Loan Prediction System is twofold:

1. **Predict Loan Eligibility:** Determine whether an applicant is eligible for a loan based on multiple personal and financial features.
2. **Identify Eligibility Gaps:** Highlight the missing or insufficient criteria that may disqualify an applicant, giving them actionable insights to improve their eligibility in the future.

## Steps Involved

1. **Gathering Data:** Collecting and compiling relevant information about applicants and their financial profiles.
2. **Feature Engineering:** Creating new variables or modifying existing ones to better capture patterns for loan eligibility.
3. **Data Cleaning:** Handling missing values, outliers, and inconsistent data entries to ensure data quality.
4. **Exploratory Data Analysis:** Analyzing data to understand the relationships between variables and their impact on loan eligibility.
5. **Data Preprocessing:** Transforming data into a format suitable for machine learning, including encoding categorical features and scaling numerical data.
6. **Machine Learning Model Selection:** Choosing the most appropriate model for predicting loan eligibility based on the data's characteristics.
7. **Hyperparameter Tuning:** Optimizing model parameters to improve accuracy and robustness.
8. **Model Evaluation:** Testing the model's performance to ensure reliable and accurate predictions.

## Dataset Key Information

| Column Name             | Description                                               |
|-------------------------|-----------------------------------------------------------|
| `loan_id`               | Unique loan ID                                            |
| `no_of_dependents`      | Number of dependents of the applicant                     |
| `education`             | Education level of the applicant                          |
| `self_employed`         | Whether the applicant is self-employed                    |
| `income_annum`          | Annual income of the applicant                            |
| `loan_amount`           | Loan amount requested by the applicant                    |
| `loan_tenure`           | Tenure of the loan requested by the applicant (in Years)  |
| `cibil_score`           | CIBIL score of the applicant                              |
| `residential_asset_value` | Value of the residential asset of the applicant        |
| `commercial_asset_value` | Value of the commercial asset of the applicant          |
| `luxury_asset_value`    | Value of the luxury asset of the applicant                |
| `bank_assets_value`     | Value of the bank asset of the applicant                  |
| `loan_status`           | Status of the loan (Approved/Rejected)                    |

This system leverages these data attributes to analyze applicants' profiles and make informed predictions, enabling efficient and fair decision-making in loan approval.

## Conclusion

The Loan Prediction System achieves high accuracy, with the Decision Tree and Random Forest models both reaching 98% accuracy. These models provide reliable predictions for loan eligibility, streamlining the approval process and offering valuable insights to help applicants improve their chances of qualifying in the future.
