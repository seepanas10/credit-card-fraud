# Credit Card Fraud Detection

# Dataset

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Approach

The following steps would be followed in this study

1. Exploratory Data Analysis
2. Preparing Data (scaling the variables; applying synthetic minority oversampling technique to handle the imbalanced dataset, removing extreme outliers)
3. Model Implementation (Logistic Regression, KNN, and Decision Tree classifiers)
4. Using Anomaly Detection Algorithms - Local Outlier Factor and Isolation Forest 

# Results

Achieved final average ROC AUC score of 0.974 by employing above mentioned classifiers
