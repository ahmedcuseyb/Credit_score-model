Credit Scoring Model
Overview
This project builds and evaluates machine learning models to predict the likelihood of a customer defaulting on credit obligations.
The dataset contains both numerical and categorical features related to customer credit behavior, with a significant class imbalance (non-defaults are much more common).

Objective
Predict DEFAULT (1) vs NON-DEFAULT (0).

Handle class imbalance.

Optimize for the best trade-off between precision (minimize false alarms) and recall (catch more defaults).

Workflow
Data Preparation

Split into training and test sets (train_test_split, stratified by target).

Feature scaling with StandardScaler for models that require it.

Handle imbalance using SMOTE oversampling.

Models Tested

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Evaluation Metrics

Precision, Recall, F1-score

Confusion Matrix

ROC-AUC score

Precision-Recall curve for threshold tuning.
