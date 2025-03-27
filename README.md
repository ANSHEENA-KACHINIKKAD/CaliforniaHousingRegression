# California Housing Regression

This repository contains the code and analysis for Machine Learning Assignment, which focuses on regression techniques applied to the California Housing dataset.

## Project Objective

The objective of this assignment is to evaluate the understanding of regression techniques in supervised learning by applying them to a real-world dataset.

## Dataset

The dataset used is the California Housing dataset, available from the `sklearn` library. It contains information about various features of houses in California and their respective median prices.

## Key Components Fulfilled

* **Loading and Preprocessing:**
    * Loaded the California Housing dataset using `fetch_california_housing` from `sklearn`.
    * Converted the dataset into a pandas DataFrame.
    * Handled missing values (if any) and performed necessary feature scaling (standardization).
    * Provided explanations and justifications for the preprocessing steps.
* **Regression Algorithm Implementation:**
    * Implemented the following regression algorithms:
        * Linear Regression
        * Decision Tree Regressor
        * Random Forest Regressor
        * Gradient Boosting Regressor
        * Support Vector Regressor (SVR)
    * Provided brief explanations of how each algorithm works and why it might be suitable for this dataset.
* **Model Evaluation and Comparison:**
    * Evaluated the performance of each algorithm using:
        * Mean Squared Error (MSE)
        * Mean Absolute Error (MAE)
        * R-squared Score (R²)
    * Compared the results of all models and identified the best-performing algorithm with justification.

## Files

* `California_houseprice_regression.ipynb`: Jupyter Notebook containing the code and analysis.
* `README.md`: This file, providing an overview of the project.

## Dependencies

* `numpy`
* `pandas`
* `scikit-learn (sklearn)`
