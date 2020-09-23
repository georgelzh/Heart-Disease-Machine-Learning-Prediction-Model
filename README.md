# Heart-Disease-Machine-Learning-Prediction-Model Intro
Zhihong (George)Li zhihongli@bennington.edu

This project intends to find the one of the best ML models for predicting whether a patient has heart disease. 
If the patient has heart disease, the model will retuen 1, if the patient does not have heart disease, the model will return 0. This project has two parts. 

# Part 1: Heart_Disease_Machine_Learning_Prediction_Model:
This file intends to test many kinds of ML models for predicting whether a patient has heart disease.
If the patient has heart disease, the model will retuen 1, if the patient does not have heart disease,
the model will return 0.

The other jupyter file named "Shuffle_Data_Ten_Times_and_Evaluate_Model", 
continues to evaluate a high potential ML model that we tested here for heart disease prediction.

Dataset comes from Kaggle https://www.kaggle.com/nyjoey/heart-disease

# Part 2: Shuffle_Data_Ten_Times_and_Evaluate_Model. 
This program takes the heart.csv, shuffle it and split the train and test data.
Then it trains with Logistic Regression Model. Using test data to predict the output(whether patient has heart disease or not).
Then it evaluates the predictions by calculating the mean precision and precision std.
