# Module 12 Introduction: Predictive Modeling with Linear Regression

After checking and documenting the ABT, we now begin applying analytics. This module introduces predictive modeling using linear regression. The modeling is intentionally simple and practical. The goal is not to build the best possible model, but to understand the basic supervised learning workflow.

Predictive modeling uses known information to estimate an outcome of interest. In this module, the outcome is numeric, so the task is regression. You will use a prepared flight-level ABT, define a target variable, choose feature variables, split the data, fit a model, evaluate predictions, and write a cautious interpretation.

## This Week You Will

- explain the purpose of supervised predictive modeling;
- distinguish features from the target variable;
- create training and testing datasets;
- fit a basic `LinearRegression` model with Scikit-learn;
- generate predictions;
- calculate MAE, RMSE, and R-squared;
- interpret coefficients and metrics cautiously.

## Lab Focus

The lab uses a flight-level ABT from `nycflights13` to predict arrival delay. You will define `X` and `y`, use `train_test_split`, fit a model, evaluate performance, and connect metrics back to business meaning.

## Important Modeling Note

Prediction is not the same as explanation. A model may use patterns to predict an outcome without proving cause and effect. Also ask whether each feature would be available at the time of prediction; otherwise, the model may contain data leakage.

## Project Connection

If your project has a numeric target, this module provides a basic modeling template. If your target is categorical, the next module may fit better.
