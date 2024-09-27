# Income-classifier-model

This repository contains a machine learning project that predicts whether an individual's income exceeds $50K per year based on various features such as age, workclass, education, and more. The project uses different classification algorithms to build predictive models.

# Table of Contents
1) Project Overview
2) Data
3) Models Used
4) Installation
5) Usage
6) Results
7) Contributing
8) License
# Project Overview
The goal of this project is to classify whether a person makes more than $50K per year based on census data. Various supervised learning models are used to achieve this classification task, and their performance is compared to determine the most accurate model.

# Algorithms Implemented
1) Decision Tree
2) Random Forest
3) Logistic Regression
4) K-Nearest Neighbors (KNN)

# Data
The dataset contains demographic information and income levels. Below are the features used:

1) Age
2) Workclass
3) Fnlwgt
4) Education
5) Education_num
6) Marital_status
7) Occupation
8) Relationship
9) Race
10) Sex
11) Capital_gain
12) Capital_loss
13) Hours_per_week
14) Native_country
15) Income (Target)
The Income feature is the target variable, which takes two values: <=50K and >50K.

# Models Used
1) Decision Tree Classifier
2) Random Forest Classifier
3) Logistic Regression
4) KNN Classifier

   
Each model is evaluated on the test data to calculate performance metrics such as accuracy, precision, recall, F1-score, and misclassification rate. Confusion matrices and classification reports are generated for each model.

# Usage
1) Preprocess the data by handling missing values (if any) and splitting it into training and test datasets.

2) Run the classification models

3) Each model will generate the outputs

# Results
Each model is evaluated using several metrics:
1) Accuracy
2) Precision
3) Recall
4) F1-score
5) Misclassification Rate
   
The performance of each model is compared to determine the best classifier for predicting income.

     
