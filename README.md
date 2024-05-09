# Computational Mathematics Exploration

## Overview
This repository contains my submission for an exploration in computational mathematics, specifically through participating in the [House Prices: Advanced Regression Techniques competition on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). This README details the approach taken, including data analysis, probability calculations, statistical testing, linear algebra operations, and modeling.

## Objective
The goal of this project is to demonstrate an understanding of key concepts from computational mathematics by analyzing the "House Prices" dataset from Kaggle. The project tasks include selecting variables, calculating probabilities, conducting statistical tests, and building regression models.

## Data Analysis
### Selection of Variables
- **Independent Variable (X):** Selected a quantitative variable from the training dataset that is skewed to the right.
- **Dependent Variable (Y):** The price of the house, which is the main variable we aim to predict.

### Probability Calculations
I calculated the following probabilities, interpreting each one:
- **P(X>x | Y>y)**
- **P(X>x, Y>y)**
- **P(X<x | Y>y)**

Additionally, a table of counts was created to better understand the distribution and relationship between X and Y.

### Statistical Independence Check
By defining new variables based on quartiles, I checked the independence of splits in the training data using a Chi-Square test for association.

## Statistical Analysis
### Descriptive and Inferential Statistics
Provided univariate descriptive statistics and visualizations for the training dataset. Conducted the following analyses:
- Scatterplot of X vs. Y.
- 95% Confidence Interval for the difference in mean values.
- Correlation matrix for selected quantitative variables, including hypothesis testing for correlation.

### Linear Algebra and Correlation
- Inverted the correlation matrix to obtain the precision matrix.
- Conducted operations on the correlation and precision matrices to validate their properties.
- Performed principal component analysis and discussed the findings.

## Calculus-Based Probability & Statistics
For the variable X, fitted an exponential distribution after ensuring all values were positive. Key analyses included:
- Histograms of the original and sampled data from the fitted distribution.
- Calculation of 5th and 95th percentiles from the exponential distribution.
- Empirical 5th and 95th percentiles.

## Modeling
Built a regression model and submitted the results to the Kaggle competition board. Included a complete model summary and analysis:
- Kaggle Username: [Tilon Bobb]
- Kaggle Score: [0.41014]

## Conclusion
This exploration demonstrates the practical application of computational mathematics concepts in analyzing real-world data and building predictive models. Insights gained from this project are discussed in relation to each section of analysis.

## How to Run

To run the analysis presented in this project, follow these steps:

1. Visit the notebook on Kaggle at [this link](https://www.kaggle.com/code/tilonbobb/house-prices-submission).
2. If you are not already signed into Kaggle, you will need to create an account or log in.
3. Once you are viewing the notebook, you can run the code cells sequentially to reproduce the analysis:
   - Click on the "Copy and Edit" button to create a personal editable copy of the notebook.
   - In your copy of the notebook, use the "Run All" option to execute all the cells automatically, or run each cell individually by clicking the "play" button in each cell.
4. To modify the analysis or test different variables, you can edit the code cells and rerun them as needed.

Ensure that you have the necessary Kaggle API permissions and access to datasets, as these are required to fetch data and submit predictions directly through the Kaggle notebook interface.


