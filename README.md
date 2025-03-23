# Heart Disease Prediction using Machine Learning
 #Project Overview

This project aims to predict whether a person has heart disease based on various medical parameters. The dataset consists of key health indicators such as age, cholesterol levels, blood pressure, and more. We implemented Decision Tree and Logistic Regression models to classify patients as having heart disease or not.

 #Dataset Description : The dataset contains the following columns:
 age of patients
sex - 1 for male ,0 for female
cp-chest pain (agnia probelm)
trestbps-resting blood pressure
chol-cholestrol
fbs- fasting blood sugar (1-high blood sugar,0-low blood sugar)
restecg- heart activity while resting
thalach-max heart rate
exang- does excercise induce agnia (1-yes,0-no)
oldpeak-measures heart electrical activity
slope-upslope(less risky-0),moderate/average-1,downsloping-(risky 2)
ca-whether there is a blockage of vessel or not (0-3)
thal-thallium test result(0-permanent damage,3-healthy heart)
target-whether a person has heart disease present (0-no ,1-yes)

#Machine Learning Models Used:
We experimented with two classification models:

1.Decision Tree Classifier

2.Logistic Regression

#Model Performance:

After evaluating both models using classification metrics (accuracy, precision, recall, and F1-score), we found that Logistic Regression outperformed Decision Tree in classifying heart disease presence.
