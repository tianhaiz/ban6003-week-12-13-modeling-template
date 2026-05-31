# Module 12 Lab Guide: Introduction to Predictive Modeling with Linear Regression

**BAN 6003: Data Management and Analytics Integration**

This module introduces the basic supervised modeling workflow with linear regression. You will use a flight-level ABT and predict a continuous outcome.

## Lab File

Complete:

`module12_linear_regression_guided_lab.ipynb`


## GitHub Repository and Running Environment

Start from this public template repository:

https://github.com/tianhaiz/ban6003-week-12-13-modeling-template

Create your own GitHub repository from the template with **Use this template > Create a new repository**. I recommend making your repository public so the instructor can inspect your submission. If you use a private repository, invite the instructor GitHub account `zzz1990771` or the email `zzz1990771@gmail.com` as a collaborator.

You may run the lab in either environment:

- **Recommended for beginners:** GitHub Codespaces from your own repository.
- **Local option:** clone your own repository, activate the `ban6003` conda environment, install `requirements.txt`, and run JupyterLab locally.

Submit your GitHub repository link or a completed ZIP through Canvas.

## What You Will Practice

You will practice loading an ABT, choosing a numeric target, selecting feature variables, checking missing values, splitting data into training and testing sets, fitting `LinearRegression`, generating predictions, calculating MAE, RMSE, and R-squared, and interpreting coefficients cautiously.

## Recommended Workflow

1. Open the notebook in Codespaces or local Jupyter.
2. Run the setup cells.
3. Load the flight-level ABT.
4. Define the target and features.
5. Create a train/test split.
6. Fit the linear regression model.
7. Generate predictions and calculate metrics.
8. Complete the final practice and reflection.
9. Save your work, then commit and push if using GitHub.

## Modeling Note

This is a teaching example. In a real project, always ask when each feature would be available. Using information that would not be known at prediction time can create data leakage.

## Minimum Completion Checklist

Before submitting, make sure:

- You loaded the data successfully.
- You defined `X` and `y`.
- You created a train/test split.
- You fitted a linear regression model.
- You generated predictions.
- You calculated MAE and RMSE.
- You interpreted results cautiously.
- You completed the reflection.
