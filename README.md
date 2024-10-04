# Final-Project_1
Credit Card Fraud Detection
INTRODUCTION:
Credit card fraud detetction is the crucial application of machine learning in financial systems.

OBJECTIVES:

Detecting fraudulent transactions from credit card data.
Handling the issue of data imbalance.
Compare model performance and select the best approach.

DATASET:
The dataset used for this project contains transactions made by credit cards including highly imbalanced observations.

FEATURES:

V1-V28: Principal components obtained via PCA.
Amount: Transaction amount.
Time: Time elapsed from the first transaction.
Class: Fraud status (0 for non-fraud, 1 for fraud).

EXPLORATORY DATA ANALYSIS:
Plotting the distribution of features.
Visualizing  imbalance in the Class variable.
Investigate correlations between features.

HANDLING IMBALANCED DATA:
Oversampling: Synthetic Minority Oversampling Technique (SMOTE).
Undersampling: Random undersampling.

EVALUATION METRICS:

Accuracy may not be suitable for imbalanced data. 
Used Precision, Recall, F1-score, and ROC-AUC.

MODELLING AND EVALUATION:
Machine learning models applied:

Logistic Regression
Decision Tree
Random Forest

For each model:

Train on the imbalanced dataset and again on resampled dataset.
Evaluate performance using confusion matrices.
Compare results based on evaluation metrics.

SAVE THE TRAINED MODEL:
After training and evaluating the machine learning models, it is crucial to save them for future use. This allows you to avoid retraining the models every time you need to make predictions and facilitates easy deployment.

Save the trained models using Python's joblib library. This will enable us to load and use the models later without needing to retrain them.

Here. saved the model for RandomForestClassifier
