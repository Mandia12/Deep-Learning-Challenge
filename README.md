# Alphabet Soup Charity Success Predictor

## Overview

This project focuses on predicting the success of charitable donations using a deep learning model. The dataset includes various features about the funding applications made by different organizations, and the goal is to predict whether or not a applicant is likely to succeed in their venture. An original model was created in the file named [Alphabet_Soup_Charity.ipynb](Alphabet_Soup_Charity.ipynb). In the file, [Alphabet_Soup_Charity_Optimization.ipynb](Alphabet_Soup_Charity_Optimization.ipynb), three more models were configured with the last being the most accurate model.

## Dataset

The project leverages data that includes features such as:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

These features are used to predict whether an organization's campaign will be successful.

## Steps

### Data Preprocessing

- Feature selection and engineering
- Encoded categorical variables and scaled numerical features to prepare the dataset for training.
- Split the dataset into training and testing sets to evaluate the model's performance.

### Model Development and Optimization

- Built a neural network model using TensorFlow and Keras.
- Tuned hyperparameters such as the number of layers, activation functions, and optimizer to improve model performance.
- Trained the model on the preprocessed data to classify success.
- Exported the trained model in HDF5

### Results

The final model found in [AlphabetSoupCharity_Optimization.h5](Models/AlphabetSoupCharity_Optimization.h5) surpassed the target predictive accuracy goal of 75% percent, reaching 80.1%.
