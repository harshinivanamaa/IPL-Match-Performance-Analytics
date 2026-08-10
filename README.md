# IPL Match Performance Analytics

## Project Overview

This project analyzes historical Indian Premier League (IPL) match data and uses Machine Learning to predict the winning team.

The main aim of the project is to understand the factors that influence IPL match results and use those factors to build a prediction model.

## Objectives

- Analyze historical IPL match data.
- Perform data preprocessing and feature engineering.
- Understand match trends using Exploratory Data Analysis (EDA).
- Identify important features affecting match outcomes.
- Build a Machine Learning model to predict the match winner.
- Evaluate the performance of the model.

## Dataset

The project uses IPL match data from Kaggle.

The main datasets used are:

- `matches.csv`
- `deliveries.csv`

The datasets contain information about teams, venues, toss results, scores, wickets, overs and match results.

## Project Steps

1. Data Collection
2. Data Preprocessing
3. Merging the datasets
4. Handling missing values
5. Feature Engineering
6. Exploratory Data Analysis (EDA)
7. Label Encoding
8. Feature Selection
9. Train-Test Split
10. XGBoost Model Building
11. Model Prediction
12. Model Evaluation
13. Feature Importance Analysis

## Features Used

Some of the important features used in the model are:

- Team 1
- Team 2
- Toss Winner
- Toss Decision
- Venue
- Season
- Target Runs
- Target Overs
- Match Total Runs
- Match Total Wickets

## Exploratory Data Analysis

EDA was performed to understand different patterns in IPL matches.

The analysis included:

- Team performance analysis
- Toss analysis
- Venue analysis
- Run distribution
- Correlation analysis
- Different graphs and visualizations

## Machine Learning Model

The **XGBoost Classifier** was used for predicting the winning team.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

Categorical features were converted into numerical values using Label Encoding before training the model.

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model achieved approximately **86.32% accuracy** on the test data.

## Feature Importance

Feature importance was also analyzed to understand which features contributed more to the prediction.

The most important features included:

- Match Total Wickets
- Target Runs
- Match Total Runs
- Target Overs
- Season
- Team information
- Toss information
- Venue

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

## Project File

`IPL_CasestudyCol.ipynb` contains the complete implementation of the project, including preprocessing, EDA, model building, prediction and evaluation.

## Conclusion

This project shows how historical IPL data can be analyzed using Machine Learning to predict match winners. The XGBoost model achieved approximately 86.32% accuracy and helped identify important factors related to IPL match outcomes.
