# Air Quality Regression Analysis

This repository contains the implementation of linear and logistic regression models from scratch to assess air quality. The goal was to predict Carbon Monoxide (CO) levels based on various features such as Non Metanic Hydrocarbons concentration, Benzene concentration, NOx concentration, temperature, humidity, and sensor responses.

## Data Processing

- Downloaded and read the training and test data using pandas library.
- Checked for missing values and dropped rows with missing data.
- Extracted features and labels from the data.

## Exploratory Data Analysis (EDA)

- Plotted histograms of all features to visualize distributions and identify outliers.
- Created scatter plots to illustrate correlations between pairs of features.
- Computed Pearson’s correlation between all pairs of variables and visualized the correlation matrix using a heatmap.

## Linear Regression Implementation

- Implemented a linear regression model from scratch to predict CO levels.
- Conducted 5-fold cross-validation and computed Root Mean Squared Error (RMSE) for each fold.
- Analyzed coefficients to identify the most informative features.

## Logistic Regression Implementation

- Created a binary label for CO levels where values above 1000 correspond to label 1 and values below or equal to 1000 correspond to label 0.
- Implemented logistic regression model from scratch to predict the binary label.
- Conducted 5-fold cross-validation and computed accuracy, precision, recall, and F1 score for each fold.

## ROC Curve Analysis

- Utilized logistic regression model from scikit-learn for comparison.
- Plotted ROC curves for each fold and computed the area under the curve (AUC).

