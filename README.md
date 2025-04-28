# Project Overview
This project focuses on predicting loan defaults using advanced machine learning techniques. It provides financial institutions with a robust, data-driven tool for assessing the risk of borrowers defaulting on loans, thus helping to reduce financial losses and enhance risk management strategies.

We got the dataset from a GitHub repository of a Coursera course: https://github.com/MitraKin/Loan-Default-Prediction.  The dataset includes 17 features, a unique loanID, and a binary target variable indicating whether the loan defaults. There are three main phases to the project: 
(Note each phases is handle exclusively by one person so there will be differences inthe  data preprocessing pipeline for each model)
  1. Probability of Default prediction: train data went through pre-processing and was used to train a classification model whose primary goal is to generate the Probability of how likely an individual loan defaults.(there are multiple iteration of this phase)
  2. Loan Clustering: Cluster loans into 3 groups based on the top feature result from the decision tree (Cluster labels added at the final column of the output test file )
  3. Financial simulation 

# Machince Learning  Techniques Used
1. XGBoost
2. SHAP Values
3. Logistic regression
4. Random forest
5. Decision Tree

# Future Plans
1. Develop a robust stress testing framework
2. Incorporating advance machine learning model
3. Quantifying risk transfer mechanism through swap pricing and risk 
