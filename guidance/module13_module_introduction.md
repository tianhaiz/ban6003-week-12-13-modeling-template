# Module 13 Introduction: Classification Models

Module 12 focused on regression, where the target variable is a continuous number. This week, we move to classification, where the target is a category or class. Instead of predicting exactly how many minutes late a flight will be, for example, we may predict whether a flight will be late or not late.

This module introduces two basic classification models: logistic regression and decision trees. The goal is to understand the classification workflow and interpret model results carefully, not to build the most advanced classifier.

## This Week You Will

- distinguish regression problems from classification problems;
- create and explain a binary target variable;
- check class balance;
- fit a logistic regression model;
- fit a basic decision tree classifier;
- generate predictions;
- create a confusion matrix;
- calculate accuracy, precision, and recall;
- compare model suitability and interpretability.

## Lab Focus

The lab continues with `nycflights13`. You will create a binary target for late arrival, fit logistic regression and decision tree models, evaluate both models, and compare what each model offers.

## Why Metrics Need Context

Accuracy, precision, and recall answer different business questions. A false alarm and a missed case may have very different consequences. The best metric depends on the decision context and the cost of different errors.

## Project Connection

Project Milestone 3 is due around this module. Your milestone should connect your prepared dataset, draft documentation, methodology, and initial model application. If classification fits your project target, use this module as a guide.
