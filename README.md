# Startup Profit Prediction | Multiple Linear Regression

Predicting Startup Profits Based on R&D, Marketing, and Administrative Expenses

# Overview

This project uses Multiple Linear Regression to predict the profit of startups based on key financial metrics:

* R&D Spending

* Administration Costs

*Marketing Expenditure

* Location (State)

The dataset is a classic case study for regression analysis, helping understand how different factors contribute to a startup's financial success.

# Dataset
The dataset contains the following features:

Feature	 Description
R&D Spend	Research and Development budget ($)
Administration	Administrative expenses ($)
Marketing Spend	Marketing budget ($)
State	Location of the startup (Categorical)
Profit	Target variable (Profit in $)

# Steps
Exploratory Data Analysis (EDA)

Statistical summaries, correlation heatmaps, and visualizations.

Data Preprocessing

Handling categorical data (One-Hot Encoding for State).

Train-test split (test_size=0.2).

Model Training

Multiple Linear Regression (sklearn.linear_model.LinearRegression).

Evaluation

Metrics: R² Score, Mean Squared Error (MSE), Residual Analysis.

# Key Insights
R&D Spend has the strongest positive correlation with profit.

Marketing Spend also contributes significantly.

Administration costs show weaker impact.
