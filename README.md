# Heart-Analysis-using-ECG-and-Heart-Failure-Prediction

## Introduction
Heart diseases are the leading cause of death globally. Each year, over a million deaths occur worldwide. One third of these deaths occur below the age of 70.  A lot of effort is provided by researchers all over the world to provide prevention, help, relieve, and hopefully one day cure heart diseases. 
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.
Adding on, ECG is widely used by cardiologists and medical practitioners for monitoring the cardiac health. The main problem with manual analysis of ECG signals, similar to many other time-series data, lies in difficulty of detecting and categorizing different waveforms and morphologies in the signal. For a human, this task is both extensively time-consuming and prone to errors. 


This project is an analytical study to predict the risk of having a heart failure. Various data analysis techniques have been used to observe trends between various risk factors for heart diseases. Based on the features, different machine learning models were then implemented to predict whether a person has heart disease.
We also study the ECG of patients and classify them into 5 different categories. To address the problems raised with the manual analysis of ECG signals, many studies in the literature explored using machine learning techniques to accurately detect the anomalies in the signal. We have implemented 3 different implementations for classifying the ECG signals. 

## Modules:
1. Heart Failure Prediction
2. ECG HeartBeat Classification 



### Heart Failure Prediction

Models implemented:
 - Extra trees classifier
 - Gradient Boosting Classifier
 - Random Forest Classifier
 - CatBoost Classifier
 - Light Gradient Boosting Machine
 - Decision Tree Classifier
 
Best performing model : Ensemble of the models implemented (except Decision tree) with Soft Voting.

Final model : Calibrated version of the best model using pycaret


### ECG Heartbeat Classification
Algorithms:
 - Logistic Regression
 - Random Forest
 - XgBoost 

Performed Minority Sampling using SMOTE technique as data had imbalance.

Best performing model - Random Forest (in both ases with and without SMOTE).




