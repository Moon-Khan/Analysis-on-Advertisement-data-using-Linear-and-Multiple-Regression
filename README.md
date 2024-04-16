# Analysis on Advertisement Data using Linear and Multiple Regression

## Introduction

This repository contains code for analyzing advertisement data using linear regression and multiple regression techniques. The analysis focuses on predicting sales based on advertising expenditures in different mediums such as TV, radio, and newspaper.

## Installation

To run the analysis code, follow these steps:

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/your-username/Analysis-on-Advertisement-data-using-Linear-and-Multiple-Regression.git
    ```

2. Install the required Python libraries:

    ```
    pip install pandas numpy scikit-learn matplotlib statsmodels
    ```

3. Ensure that you have the provided advertisement data CSV file (`Advertising.csv`) in the repository directory.

## Code Overview

The analysis is divided into two main sections:

### 1. Linear Regression

In this section, we perform linear regression to predict sales based on advertising expenditures in different mediums. The steps include:

- Loading the advertising data.
- Separating features (TV, radio, newspaper) and the target variable (sales).
- Splitting the data into training and testing sets.
- Training a linear regression model.
- Predicting sales using the trained model.
- Visualizing actual vs predicted sales for evaluation.

### 2. Multiple Regression

In this section, we extend the analysis to multiple regression, including R^2, t-statistics, and p-values calculation. The steps include:

- Loading the advertising data.
- Separating features (TV, radio, newspaper) and the target variable (sales).
- Adding a constant term for multiple regression with statsmodels.
- Splitting the data into training and testing sets.
- Training a linear regression model with sklearn.
- Predicting sales using the trained model.
- Calculating R-squared for evaluation.
- Getting summary statistics for multiple regression with statsmodels.
- Obtaining t-statistics and p-values for further analysis.

## Conclusion

Both linear and multiple regression techniques provide insights into the relationship between advertising expenditures and sales. Linear regression offers a simple yet effective approach, while multiple regression enhances the analysis by considering additional factors and providing statistical insights.

Feel free to explore the code and documentation provided in this repository. If you have any questions or suggestions, please don't hesitate to reach out!
