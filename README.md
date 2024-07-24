# Sleep
# Sleep Data Analysis and Sleep Duration Prediction

This project involves analyzing sleep data and building machine learning models to predict sleep duration. It includes two main components: data analysis and machine learning model training.

## Table of Contents
- [Installation](#installation)
- [Data Analysis](#data-analysis)
- [Machine Learning Model](#machine-learning-model)
- [Results](#results)

## Installation

To run the notebooks and reproduce the results, you need to install the required dependencies. You can install them using the following commands:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost xgboost
```

## Data Analysis
The Sleep data analysis.ipynb notebook performs the following steps:

- Data Loading: Reads the sleep data from a CSV file.
- Data Cleaning: Handles missing values, identifies and removes duplicates, and replaces specific values.
- Exploratory Data Analysis (EDA): Displays data head and descriptive statistics, identifies numerical and categorical features, and analyzes unique values in specific columns.
- Data Visualization: Creates plots to visualize the distribution of sleep duration and other variables.

## Machine Learning Model
The ML model to predict sleep duration.ipynb notebook performs the following steps:

- Libraries and Dependencies: Installs and imports necessary libraries.
- Data Loading: Reads the cleaned sleep data from a CSV file.
- Exploratory Data Analysis (EDA): Displays data head, identifies numerical and categorical features, and analyzes unique values in specific columns.
- Data Preprocessing: Separates the target variable (Sleep Duration) from features, creates column transformers for numerical and categorical features, and scales/encodes them.
- Model Training: Trains various regression models including K-Nearest Neighbors, Decision Tree, Random Forest, AdaBoost, Support Vector Regressor, Linear Regression, Ridge, Lasso, CatBoost, and XGBoost.
- Model Evaluation: Evaluates models using metrics such as R-squared, Mean Absolute Error, and Mean Squared Error.

## Results
The results of the analysis and model training are documented in the respective notebooks. The models are evaluated based on their performance metrics, and the best performing model is selected for predicting sleep duration.
