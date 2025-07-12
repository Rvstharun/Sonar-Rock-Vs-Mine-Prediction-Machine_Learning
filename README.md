# Sonar-Rock-Vs-Mine-Prediction-Machine_Learning

Rock vs Mine Classification using Logistic Regression
This project uses Logistic Regression to classify objects detected by sonar as either rock or mine, based on sonar frequency response data. It demonstrates how a simple yet powerful machine learning algorithm can solve real-world binary classification problems.

📌 Problem Statement
Given 60 features extracted from sonar signals bounced off underwater objects, the goal is to predict whether the object is a Rock (R) or a Mine (M) using a logistic regression classifier.

📊 Dataset Summary
Source: UCI Machine Learning Repository

Total Samples: 208

Features: 60 numerical attributes (energy values across frequencies)

Target Classes:

R → Rock

M → Mine

Each row represents sonar energy measurements reflected back from an object.

🧠 Model Used
Algorithm: Logistic Regression

Why Logistic Regression?
It's a simple and interpretable linear model ideal for binary classification tasks like this. It models the probability of an object being a rock or a mine based on sonar signal patterns.

🛠️ Technologies & Libraries
Python

Pandas & NumPy

Scikit-learn

Matplotlib

📈 Model Evaluation
Data split: 83% training / 76% testing

Evaluation Metrics:
Accuracy Score

The model was trained and tested, and performance was visualized to confirm accuracy and reliability.
