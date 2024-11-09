# Multiclass-Classification-Disease-Prediction

This code performs an exploratory analysis of a medical dataset containing information on diseases and associated symptoms. The objective is to preprocess and analyze symptom data, map symptoms to diseases, and create a model for disease prediction based on symptoms.
The code handles data cleaning, transformation, and exploratory data analysis (EDA). Initially, it loads symptom and disease data and cleans up symptom names. Afterward, it structures the dataset for machine learning by preparing features and target labels. Logistic regression is applied for predictive modeling, using symptoms to predict diseases, while metrics like accuracy score and confusion matrix are generated to evaluate model performance.

# Dataset Description :-

The dataset comprises a list of diseases and associated symptoms:

•	Symptom-severity.csv: Contains severity ratings for each symptom.

•	Dataset1.csv: Contains multiple rows, each representing a disease with up to 17 symptoms, stored in columns (Symptom_1, Symptom_2, ...). Each row has a "Disease" column identifying the disease and subsequent columns specifying associated symptoms.
