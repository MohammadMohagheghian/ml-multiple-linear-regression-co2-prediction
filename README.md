# Multiple Linear Regression - CO2 Emission Prediction

## Project Overview

This project applies Multiple Linear Regression to predict vehicle CO2 emissions using engine and fuel-related features.

The complete workflow, including data exploration, feature selection, model training, evaluation, model comparison, and residual analysis, is available inside the Jupyter Notebook.

## Features Used

The final model uses:

- ENGINESIZE
- CYLINDERS
- FUELCONSUMPTION_COMB

## Machine Learning Workflow

The notebook covers:

1. Loading and exploring the dataset
2. Checking data structure and missing values
3. Correlation analysis
4. Selecting relevant features
5. Splitting data into training and testing sets
6. Training a Multiple Linear Regression model
7. Interpreting model coefficients
8. Comparing different feature combinations
9. Evaluating model performance
10. Visualizing predictions and analyzing residuals

## Model Performance

Final Multiple Linear Regression model:

- MAE: 16.72
- MSE: 512.85
- R² Score: 0.876

The notebook also compares simpler models and shows how adding informative features improves prediction performance.

## Visual Analysis

The notebook includes visual analysis of:

- Actual vs Predicted CO2 emissions
- Residual distribution and prediction errors

These visualizations are generated directly when the notebook is executed.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Install required libraries:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```text
notebooks/multiple_linear_regression_co2.ipynb
```

3. Run the cells to reproduce the analysis and results.
