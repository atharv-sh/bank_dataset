
# Bank Marketing Dataset Analysis and Prediction

This repository contains a Jupyter Notebook for analyzing and predicting customer subscription success in a bank marketing campaign.  The dataset used for this analysis is the "bank.csv" file.

## Project Overview

This project aims to build a predictive model to determine whether a customer will subscribe to a term deposit.  The analysis involves data exploration, preprocessing, model training, evaluation, and model persistence.

## Data

The dataset consists of several customer attributes, including demographics, financial information, and contact details.  The target variable 'y' indicates whether the client subscribed to a term deposit ('yes' or 'no').

## Analysis and Modeling

1. **Exploratory Data Analysis (EDA):** The notebook includes several visualizations to understand the distribution of key features and identify potential correlations.  This includes:
    - Countplots
    - Boxplots
    - Violinplots
    - Heatmaps
    - Pairplots
    - Jointplots
    - Interactive visualizations using Plotly Express (scatter plots, histograms, bar charts)

2. **Data Preprocessing:**  The dataset is preprocessed to prepare it for machine learning models. This includes:
    - Handling numerical features: Scaling using StandardScaler.
    - Handling categorical features: Encoding using OneHotEncoder.
    - Splitting the data into training and testing sets.

3. **Model Training and Evaluation:**  Multiple classification models are trained and evaluated using accuracy and classification reports. The models include:
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - Gradient Boosting
    - Support Vector Machine (SVM)
    - K-Nearest Neighbors (KNN)
    - Naive Bayes

The model with the highest accuracy is selected as the best model.
