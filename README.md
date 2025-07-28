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

<H1>Short Write-up of key findings and best model details.
      
***1. Data Exploration and EDA Findings***

      There were no missing values in the dataset.

      Most of the sales values are between 0 and 20,000.

      Some values are outliers, especially those greater than 40,000 and less than -20,000.

      Store_Size showed the strongest positive correlation with Sales_Price.

      Scatter plots between features and target showed a lot of spread and no clear linear relationship.

      Based on scatter plots, the data does not strongly support a linear model.

***2. Model Building and Evaluation***

      Linear Regression gave an R² score of around 0.0818 and RMSE of around 9964.

      K-Fold Cross Validation showed R² scores between 0.075 and 0.082 with an average of 0.0795.

      Ridge Regression gave similar results with a best alpha value of 100.

      Lasso Regression also gave similar results with a best alpha value of 0.001.

      All three models had almost the same performance.

      The R² score for all models was very low, indicating they explain only 8 percent of the variance in Sales_Price.

      The RMSE values were high, meaning the prediction errors are large.

***3. Model Comparison and Interpretation***


      Regularization (Ridge and Lasso) did not improve the model significantly.

      This suggests that the input features are not strong predictors of the target variable.

      The residual plots formed a circular scattered pattern, which indicates a poor fit.

      Actual vs Predicted graphs showed large differences, especially at extreme values.

***4. Best Model Selection***

      Since all three models performed equally, Linear Regression is selected as the best model as it was marginally better.

      It is the simplest and gave the same accuracy as Ridge and Lasso.

***5. Conclusion***

      The current features are not sufficient to accurately predict Sales_Price.

      Model performance is poor due to low explanatory power of the variables.

      To improve predictions, we need to add new features or transform existing ones.

      Possible improvements include feature engineering, adding external variables, or trying non-linear models.




