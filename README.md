# House Sale Price Prediction

## Project Overview

This project aims to build a multiple linear regression model to predict house sale prices. The dataset contains various features about houses, such as their size, location, and quality. By leveraging this information, the model will predict the sale price of the houses.

## Dataset Information

The dataset contains the following key features:
- **MSSubClass**: The building class.
- **LotArea**: Lot size in square feet.
- **OverallQual**: Overall material and finish quality.
- **YearBuilt**: Original construction date.
- **GrLivArea**: Above grade (ground) living area square feet.
- **SalePrice**: The property's sale price (target variable).

## Key Features of the Project

- **Data Cleaning & Preprocessing**:
  - Handle missing data and convert categorical variables using techniques like target encoding.
  - Remove features with high multicollinearity (using VIF).
  
- **Exploratory Data Analysis (EDA)**:
  - Visualize the relationships between features and sale price.
  - Identify the most important features affecting house prices.

- **Model Building**:
  - Construct a multiple linear regression model to predict house prices.
  - Feature selection based on Variance Inflation Factor (VIF).
  
- **Model Evaluation**:
  - Use metrics like Mean Squared Error (MSE) and R-squared to evaluate model performance.

## Installation & Requirements

To run this project, you will need Python and the following libraries:

- **Pandas**: For data manipulation.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For model building and evaluation.
- **Statsmodels**: For regression analysis and VIF calculations.
