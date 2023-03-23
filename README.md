# Predicting-Loan-Default---Lending-Club---Keras

This project aims to develop a predictive model based on past loan data, including information on borrower default (charge-off), to determine the likelihood of a borrower repaying their loan. The goal is to use this model to evaluate new loan applicants and determine their probability of paying back the loan.

## Data Overview

The data used in this project is from LendingClub, the world's largest peer-to-peer lending platform. It contains information such as loan amount, loan grade, employment length, annual income, and loan status, among others.

## Section 1: Exploratory Data Analysis

In this section, we explore the data to understand which variables are important, view summary statistics, and visualize the data. We create various visualizations, including countplots, histograms, and boxplots, to gain insights into the data and its relationships.

## Section 2: Data PreProcessing

In this section, we preprocess the data by removing or filling any missing data, removing unnecessary or repetitive features, and converting categorical string features to dummy variables. We then build a sequential model to be trained on the data, which includes Dropout layers.

## Section 3: Evaluating Model Performance

In this section, we evaluate the model's performance by comparing the validation loss versus the training loss. We also make predictions from the X_test set and provide a classification report and confusion matrix for the X_test set. Finally, we test the model with random samples.

Overall, this project aims to develop a predictive model that can accurately evaluate loan applicants and determine their likelihood of paying back their loan. The insights gained from the exploratory data analysis help us to understand which variables are important and how they relate to each other, while the data preprocessing and model building steps ensure that we have a robust and accurate model.
