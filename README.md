# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to apply machine learning skills to evaluate models with unbalanced classes in credit. Due to fact that credit risk is inherently an unbalanced classification problem, different techniques were needed to train and evaluate models with unbalanced classes. 

## Results
Preprocessing steps:

    -Acquire the dataset

Transformational steps:

    -Identifying and handling the missing values (None)
    -Encoding categorical variables with a mix of Pandas and Scikit Learn's 'LabelEncoder'

Splitting the data set:

    -Feature scaling with StandardScaler
    -Normalization

Implement machine learning models:

    -Logistic Regression
    -Decision Tree
    -Random Forest
    -Support Vector Machine
    -Gradient Boosting for classification

Use re-sampling to attempt to address class imbalance:

    -Combination Sampling with imblearn's SMOTEENN

Evaluate the performance of machine learning models:

    -Model evaluation and the calculating with the confusion matrix.

You want to use pipelining with scikit learn from an API or flatfile. A pipeline is one object that does all of your preprocessing work (feature selection, imputation, etc.)

Two evaluation methods: ensemble learning and re-sampling
Easy Ensemble AdaBoost Classifier performs the best with our steps & dataset; therefore, we would move forward with this estimator for further predictions.

The oversampling recall score (with SMOTE) has the highest score for predicting both low-risk and high risk loan statuses. We would put forward that this is the best model considering the financial cost risk associated with False Negatives.

Naive Random Oversampler
SMOTE
Cluster Centroids
SMOTEENN
Balanced Random Forest Classifier
Easy Ensemble AdaBoost Classifier

## Summary 

Building and evaluating several machine learning models in the branch of Supervised Learning to predict credit risk. Being able to predict credit risk with machine learning algorithms can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud.

With our data, the Easy Ensemble Model performed the most accurately. This is the model type that should be used going forward.
