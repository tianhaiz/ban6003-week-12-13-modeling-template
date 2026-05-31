# Module 13 Lab Guide: Classification Models

**BAN 6003: Data Management and Analytics Integration**

This module introduces classification modeling. In Module 12, you predicted a continuous outcome. Here, you will predict a category: whether a flight arrives late.

## Lab File

Complete:

`module13_classification_guided_lab.ipynb`


## GitHub Repository and Running Environment

This module is part of the Module 12-13 package. Use the same repository you created from this public template repository:

https://github.com/tianhaiz/ban6003-week-12-13-modeling-template

Continue working in your own repository, not the instructor template. Use Codespaces as the main path, or use your local conda/Jupyter environment if you are comfortable managing it. Make sure your repository is public, or invite `zzz1990771` / `zzz1990771@gmail.com` if it is private. Submit your GitHub repository link through Canvas.

## What You Will Practice

You will practice creating a binary target variable, checking class balance, fitting logistic regression, fitting a decision tree classifier, generating predictions, creating a confusion matrix, calculating accuracy, precision, and recall, and comparing model usefulness.

## Recommended Workflow

1. Open the notebook in Codespaces, or in local Jupyter if you are using the optional local path.
2. Run the setup cells.
3. Create the binary target.
4. Check class balance.
5. Define features and target.
6. Split data into training and testing sets.
7. Fit and evaluate logistic regression.
8. Fit and evaluate a decision tree.
9. Compare the models.
10. Complete the final practice and reflection.
11. Save your work, then commit and push if using GitHub.

## Modeling Note

Classification performance depends on both model quality and the cost of different mistakes. Accuracy alone may not be enough if false positives and false negatives have different business consequences.

## Minimum Completion Checklist

Before submitting, make sure:

- You created a binary classification target.
- You checked class balance.
- You created a train/test split.
- You fitted logistic regression and a decision tree.
- You calculated classification metrics.
- You compared the models.
- You completed the final reflection.
