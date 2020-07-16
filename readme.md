
# Fraud Detection with Auto ML Overview

Fraud detection is a common issue for any company that issues credit or loans. Detecting these instances of fraud has the potential to save the company millions in addition to improving its image and reliability among stakeholders and customers. Therefore, it is often an exemplar case study for students new to data science, allowing them to test multiple classifier algorithms for statistical scores like accuracy, recall, or F1. 

This particular investigation will demonstrate how to automatically build models with AutoML using H2O's AutoML package. While time intensive, this can be an extremely efficient way of generating effective models.

## Table of Contents

**Fraud Detection with AutoML** - upyter notebook OSEMN walkthrough of cleaning the data and feeding it to AutoML systems. 

**sample_1.csv** - data of credit card activity containing 30000 entries, which is a subset of the original*

**fraud_csv** - dataset containing only fraudulent transactions used to balance target groups and compared with oersampling and also used as a test set.

*for full data set, please visit this [link](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Methodology

1. Extract 30000 entries as a training set
2. Label data and balanced classes with remaining data
3. Create a test set for final scoring with remaining data
4. Run AutoML to create best model
5. Create Random Forest and SVM models for comparison
6. Predict and score based on accuracy, recall, and F1


