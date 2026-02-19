Carbon Emission Prediction
Project Overview

This project predicts individual carbon emissions using various features related to lifestyle, transportation, and energy consumption. The goal is to provide insights into factors affecting carbon footprint and enable actionable recommendations.

Dataset

Source:https://www.kaggle.com/datasets/dumanmesut/individual-carbon-footprint-calculation

Features include:

Vehicle monthly distance (km)

Weekly waste bag count

Daily TV/PC usage hours

Daily internet usage hours

Heating energy source

Vehicle type

Frequency of air travel

Exploratory Data Analysis (EDA)

Analyzed feature distributions and relationships.

Identified missing values and handled them.

Visualized correlations between features and carbon emissions.

Highlighted significant contributors to carbon footprint.

Feature Engineering & Preprocessing

Encoded categorical variables (one-hot encoding).

Handled missing or anomalous data.

Models Implemented

Linear Regression – baseline model for carbon emission prediction.

Other models tested: Random forest regressor, ridge and lasso regression model

Evaluation metrics: R² score, Mean Squared Error (MSE).

Best performing model: Linear regression

Results

Linear Regression achieved R² = 0.6742, MSE = 338657.5125260684

Comparative analysis of all tested models.
