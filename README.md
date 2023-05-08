# Lab_AI_Fraud_Detection
Laboratory AI at ECAM 2022/2023
During this laboratory, we will work on fraud detection using machine learning.
Supervisor :  HASSELMANN Ken 

## Description
We work on the Xente fraud detection challenge. The goal is to predict whether a transaction is fraudulent or not.
More information about the challenge can be found here:
https://zindi.africa/competitions/xente-fraud-detection-challenge

We use the following models:
- EasyEnsembleClassifier -> AdaBoostClassifier
- EasyEnsembleClassifier -> RandomForestClassifier
- EasyEnsembleClassifier -> GradientBoostingClassifier

- RandomUnderSampler + SMOTENC -> RandomForestClassifier


## Data 
We dont provide the data in this repository due to proprietary reasons. You can download the data from the following link:
https://zindi.africa/competitions/xente-fraud-detection-challenge/data

## Path 
The report is in the directory `Report`, file `Lab_AI_Fraud_Detection.pdf` and the code is in the directory `Program`, the code is divided in several files: 
- `Data_exploration.ipynb` -> explore the data to understand it
- `Setp1.ipynb` -> First sight at Features importance
- `data_prep.ipynb` -> prepare the data for the models
- `model.ipynb` -> train and test the models

## Authors
DaveTheDudeFromECAM
LeTouristeDeLECAM

## Sources

https://medium.com/coinmonks/handling-imbalanced-datasets-predicting-credit-card-fraud-544f5e74e0fd
https://towardsdatascience.com/methods-for-dealing-with-imbalanced-data-5b761be45a18
https://pub.towardsai.net/fraud-detection-using-machine-learning-eae93f6c1bec
https://imbalanced-learn.org/stable/introduction.html



