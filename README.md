# Project Overview

The goal for this project is to identify the  fraudulent activity within the bank transaction.The pipeline includes steps such as exploratory data analysis (EDA), data cleaning, model creation, hyperparameter tuning, and model evaluation.
Project Structure

The project follows a structured approach with the following notebooks:

# Initial EDA:

Conduct univariate, bivariate, and multivariate exploratory analysis.
Formulate hypotheses based on insights gained from the analysis.
Explore relationships between predictors and the target variable.
Data Cleaning and Pre-processing:

Clean and wrangle the dataset.
Handle missing values, outliers, and incorrectly formatted data.
Drop unnecessary columns based on EDA findings.
Save the pre-processed dataset for further analysis.
Model Creation and Evaluation:

Split the pre-processed dataset into training and testing sets.
Implement a RandomForestClassifier or GradientBoostingClassifier.
Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
Evaluate the model's performance using metrics such as accuracy and F1 score.
Report:

Answer specific questions related to the project in a separate document.
Summarize insights gained from EDA.
Explain the criteria for selecting columns to drop or keep.
Describe the hyperparameter tuning strategy used and its impact on model performance.
Present the final F1 score achieved by the model.
Progress Summary

EDA Highlights:
No missing values was found 
we drop "step" and "isflaggedFraud" column because there is no transactions we can analysis.
Non - Fraud transaction has the highest number of non-fraud transaction in the datasets.
This diagram indicates that 'cash out' transactions are the most frequent, while 'debit' transactions are the least common.

# Model Evaluation Result

Based on the report, we can conclude that:

For class 0 (Non fraud): The F1 score is 1.00.
For class 1 (fraud): The F1 score is 0.69.
Overall Model performance: The model is really good at identifying class 0 but needs to get better at recognizing class 1. The performance between the two classes might suggest the need for further tuning specific to class 1
