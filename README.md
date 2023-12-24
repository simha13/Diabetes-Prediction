# Diabetes-Prediction

# Overview
A personal Machine Learning model that predicts the likelihood of diabetes based on various features extracted from health data

This repository contains a machine learning model for predicting the likelihood of diabetes based on various health-related features. The model is designed to assist healthcare professionals in early diagnosis and intervention.

# Features
*Datasets:* The model has been trained on two different datasets:
1) PIMA Indians Diabetes Dataset (originally from the National Institute of Diabetes and Digestive and Kidney Diseases, under the CC0 : Public Domain License)
2) Diabetes Prediction Dataset (taken from https://www.kaggle.com/iammustafatz)

*Algorithms:* The model has been trained on various state-of-the-algorithms (such as Logistic Regression, K-Nearest Neighbour, Gaussian Naïve Bayes) for the two aforementioned datasets with varying results.

*Evaluation:* The model's performance has been evaluated using the Accuracy Score and each alogorithm shows slightly differing accuracies, thus showing the needs of different datasets.

# Results
1) For the PIMA dataset, it is observed that Gaussian Naive Bayes Classifier obtains the best accuracy score of a moderate 77%.
2) For the other diabetes dataset however, one can notice massive improvements in accuracy with Random Forest, Extra Tree, Adaboost, Gradient Boosting, Bagging Classifiers, all achieving the maximum accuracy score of 97% on testing dataset.
