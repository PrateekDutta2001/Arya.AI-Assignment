# Arya.AI-Assignment

This is the Assignment for the post of Data Scientist at Arya.AI Pvt. Ltd., Mumbai, India

Objective - To carry out binary classification on provided data

General Approach

Data collection
Data preprocessing
Feature engineering
Scaling/Normalization
Model selection
Training
Validation
Testing
Deployment
Thought process -

Load the training dataset from csv file and figure out what kind of information is present in it.
Divide the dataset in features and classes dataframe
Check for missing data and handle it
Perform EDA
Find out the correlation between multiple features present in dataset
Feature selection using suitable technique
Scaling/Normalization of training data
Dimension reduction if required
Selection of classifier
Training and cross validation of classifier
Performance metrics of trained model
Prediction on test dataset
Pipeline

First run 'feature_selection.ipynb' notebook to check whether some features are needed to be removed
To check if dimension reduction is required or not run 'dimension_reduction.ipynb' notebook
Finally, to carry out complete machine learning pipeline run 'complete_pipeline.ipynb' notebook
After successful execution of above steps 'output.csv' file will be generated with predictions on test dataset
Requirements

Python >= 3.7
python library information is available in 'requirements.txt'
