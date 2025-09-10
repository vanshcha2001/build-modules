# build-modules

Overview : 

This project predicts customer responses to a marketing campaign using machine learning.
The main goal is to identify which customer attributes (features) most strongly influence a positive response.

Steps Done : 

Data Exploration – Checked shape, datatypes, missing values, distributions.
Data Cleaning – Handled nulls, duplicates, and outliers.
Transformation – Encoded categorical variables, scaled numeric features.
Feature Engineering – Created age groups, duration buckets, balance ratios.
Feature Selection – Applied chi-square, and feature importance.
Modeling – Trained Logistic Regression, Random Forest, XGBoost.
Evaluation – Compared models with Accuracy, Precision, Recall, F1, and MSE
Testing – Finaly applied training and testing on dataset.

Result : 

Best Model: ExtraTreesClassifier
Key Features: duration, housing, contact, month, poutcome.



Steps to Download Dataset : 

1.Go to the dataset file in this repository on GitHub.
2.Click on the file (bank-marketing.csv).
3.On the file page, click Download raw (or right-click → Save link as).
4.The file will be downloaded to your Downloads folder by default.
5.Move the CSV file to your project folder and update the path in your code accordingly.