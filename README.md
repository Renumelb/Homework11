# Homework11

In this assignment you will build and evaluate several machine learning models to predict credit risk using data you would typically see from peer-to-peer lending services. This assignment is divided into two sections- Resampling and Ensemble Learning.

# Section 1: Resampling
You will run a simple logistic regression and perform required calculations to answer the below questions. 
Steps:
- Import the data
- Oversample the data using the Naive Random Oversampler and SMOTE algorithms.
- Undersample the data using the Cluster Centroids algorithm.
- Over and undersample using a combination SMOTEENN algorithm.
- Calculate the balanced accuracy score for each.
- Display the confusion matrix for each.
- Generate a classification report using the imbalanced_classification_report for each.

## Final Questions

1. Which model had the best balanced accuracy score?

Three models have the same and the best balanced score of 0.9934649587814939- Naive random oversampling, SMOTE oversampling and Combination sampling- SMOTEENN.   

2. Which model had the best recall score?

All models have the same average recall score though the Simple Logistic Regression has a a miniscule difference in the high_rsik recall.

3. Which model had the best geometric mean score?

All models had the same geometric mean score.


# Section 2: Ensemble Learning
In this section, you will train and compare two different ensemble classifiers to predict loan risk and evaluate each model. The two models that will be used are Balanced Random Forest Classifier and the Easy Ensemble Classifier. 

Complete the following steps for each model to answer the below questions:
- Import the data.
- Calculate the balanced accuracy score.
- Display the confusion matrix.
- Generate a classification report using the imbalanced_classification_report.
- For the balanced random forest classifier only, print the feature importance sorted in descending order (most important feature to least important) along with the feature score.


## Final Questions

1. Which model had the best balanced accuracy score?

The Easy Ensemble Classifier had a higher balanced accuracy score of 0.931601605553446 as compared to Balanced Random Forest Classifier which had a score of 0.7887512850910909.

2. Which model had the best recall score?

The Easy Ensemble Classifier had a higher recall score.

3. Which model had the best geometric mean score?

The Easy Ensemble Classifier had a higher recall score.

4. What are the top three features?

The top 3 features are:
- total_rec_prncp
- total_pymnt
- total_pymnt_inv