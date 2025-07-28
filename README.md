# Sales-Price-Prediction-using-ML
Capstone Project Instructions

Project Title: Sales Price Prediction using Machine Learning Regression Analysis

Objective:The goal of this project is to predict Sales_Price based on multiple independent factors such as Advertising, Discount, Store Size, Competitor Price, Seasonality, Online Presence, and Economic Index using regression techniques. Learners will also explore and evaluate the impact of regularization (L1 & L2) and model validation techniques.

Dataset:

Download the dataset.

Tasks to be Completed:

Part 1: Data Exploration & EDA

Load the dataset and inspect: Data types, shape, missing values, statistical summary.
Perform EDA: Histograms, Boxplots, Pairplots, Correlation heatmap.
Identify whether the dataset is suitable for linear or non-linear regression using scatter plots.
Part 2: Data Preprocessing

Split the dataset into features (X) and target (y).
Apply Standard Scaling.
Perform Train-Test Split (80-20).
Part 3: Model Building

Implement Multiple Linear Regression model and name it as sales_predict.
Evaluate using R², RMSE, and Adjusted R².
Perform K-Fold Cross Validation (k=5 or 10).
Part 4: Regularization

Implement Ridge Regression (L2 Regularization) and Lasso Regression (L1 Regularization).
Use GridSearchCV for tuning alpha parameter.
Compare R² and RMSE for all models.
Part 5: Visualizations

Correlation Matrix Heatmap.
Scatter plots for linearity check.
Actual vs Predicted graph for all three models (Linear, Ridge, Lasso).
Residual plots (optional).
Part 6: Prediction on New Data

Create a sample input and predict Sales_Price using the best-performing model.
Deliverables:

Jupyter Notebook (.ipynb) with code, outputs, and explanations.
Visualization Report (PDF or within notebook).
Short Write-up of key findings and best model details.
