**House Price Prediction Model**
**Overview**
This document outlines the process and findings related to the development of a predictive model for house prices for Surprise Housing, a US-based housing company entering the Australian market. The model aims to predict the actual value of prospective properties and inform investment decisions.

**Data Description**
The dataset contains information on various aspects of houses sold in Australia, including zoning classification, lot size, type of road access, building type, and many other features that are potentially influential in predicting house prices.

**Modeling Approach**
**Data Preparation:** Data cleaning, handling missing values, and exploratory data analysis were conducted to understand the dataset.
**Feature Engineering:** Categorical variables were encoded, and relevant features were selected for the model.
**Model Selection:** Regularized regression techniques, Ridge and Lasso, were used to build predictive models.
**Model Evaluation:** Models were evaluated based on R-squared and Mean Squared Error (MSE) using cross-validation.
**Hyperparameter Tuning:** Grid search was used to find the optimal lambda for both Ridge and Lasso regression.
**Key Findings**
The optimal lambda for both Ridge and Lasso was found to be 20.
After doubling the lambda, Ridge Regression still performed slightly better than Lasso Regression.
Model robustness and generalizability were ensured through cross-validation, regularization, and hyperparameter tuning.
