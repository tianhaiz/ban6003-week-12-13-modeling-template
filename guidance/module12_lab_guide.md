# Module 12 Lab Guide: Introduction to Predictive Modeling with Linear Regression

**BAN 6003: Data Management and Analytics Integration**

This module introduces the basic supervised modeling workflow with linear regression. You will use a flight-level ABT and predict a continuous outcome.

## Lab File

Complete:

`module12_linear_regression_guided_lab.ipynb`

## GitHub Classroom Assignment Link

Canvas will provide the GitHub Classroom invitation link for this Module 12-13 assignment package:

**GitHub Classroom invitation link:** [to be added]

Click the invitation link, sign in to GitHub, and accept the assignment. If this is your first GitHub Classroom assignment for the course, GitHub may ask you to authorize GitHub Classroom and match your GitHub account to the course roster. Choose your own name or identifier carefully.

After you accept, wait for GitHub Classroom to create your personal assignment repository. Open the repository link shown on the confirmation page. If you see a repository access message, check the GitHub notifications inbox in the upper-right corner of GitHub, or go to `https://github.com/notifications`, and accept any pending repository or organization invitation from GitHub Classroom. You may also receive an email from GitHub with the same invitation.

Once you can see your personal assignment repository, open it in Codespaces with **Code > Codespaces > Create codespace on main**.

## What You Will Practice

You will practice loading an ABT, choosing a numeric target, selecting feature variables, checking missing values, splitting data into training and testing sets, fitting `LinearRegression`, generating predictions, calculating MAE, RMSE, and R-squared, and interpreting coefficients cautiously.

## Recommended Workflow

1. Open the notebook in GitHub Codespaces.
2. Run the setup cells.
3. Load the flight-level ABT.
4. Define the target and features.
5. Create a train/test split.
6. Fit the linear regression model.
7. Generate predictions and calculate metrics.
8. Complete the final practice and reflection.
9. Save, commit, and push your work.

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
