Fake Job Posting Detection using Machine Learning


 Project Overview
Fake job advertisements have become a major issue across online hiring platforms. Many fraudulent recruiters post fake opportunities to collect personal information, charge money, or scam job seekers. This project focuses on building a Machine Learning based classification system that can automatically detect whether a job posting is Real or Fake. The solution uses real-world job posting data and applies preprocessing, feature engineering, exploratory data analysis, and multiple classification models. This project demonstrates practical machine learning skills and solves a socially relevant fraud detection problem.
 Problem Statement
0 = Real Job Posting
1 = Fake Job Posting
The system helps job seekers and hiring platforms identify suspicious listings and improve trust in online recruitment.
 Dataset Information
Dataset Used: Fake Job Postings Dataset (Kaggle)
Dataset Size: 17,880 Rows | 18 Features
Feature	Description
title	Job title
location	Job location
department	Hiring department
company_profile	Company details
description	Job description
requirements	Skills required
benefits	Benefits offered
telecommuting	Remote work allowed
fraudulent	Target variable
 Complete Project Pipeline
Data Collection
Data Reading
Data Cleaning
Null Value Handling
Feature Engineering
Exploratory Data Analysis
Train-Test Split
Model Training
Model Evaluation
Model Comparison
Final Prediction System
 Data Preprocessing
The raw dataset was imported using pandas and inspected carefully. Missing values in text columns were handled using empty strings. Duplicate rows were removed to improve quality. Important features were selected for training while noisy columns were excluded. Text data was cleaned and useful columns were combined for better learning.
 Exploratory Data Analysis (EDA)
EDA was performed to understand fraud patterns in the dataset. Countplots, pie charts, histograms, boxplots, and correlation heatmaps were used to analyze class distribution and feature behavior.
 Feature Engineering
Useful features such as description length and combined text columns were created. Binary columns were retained as numeric features for model training.
 Train-Test Split
80% data was used for training and 20% data was used for testing.
 Models Used
1. Logistic Regression
2. Naive Bayes
3. Support Vector Machine (SVM)
4. Random Forest
 Model Evaluation Metrics
Accuracy Score = (TP + TN) / (TP + TN + FP + FN)
Precision = Correct Fake Predictions / Total Fake Predictions
Recall = Correct Fake Predictions / Actual Fake Jobs
F1 Score = Harmonic Mean of Precision and Recall
 Confusion Matrix
Used to compare True Positives, True Negatives, False Positives, and False Negatives.
 Model Comparison
All models were compared using evaluation metrics. The best model was selected based on accuracy, precision, recall, and F1-score.
 Final Outcome
Successfully built a machine learning classification system that predicts whether a job posting is real or fake using practical ML techniques.
