House Prices: Advanced Regression Techniques

-----
 Overview

This project is based on the Kaggle competition House Prices: Advanced Regression Techniques, where the goal is to predict the final sale price of residential homes in Ames, Iowa using advanced regression techniques and feature engineering.

The dataset includes a rich variety of numerical, categorical, and ordinal features, making it ideal for exploring data cleaning, feature engineering, and machine learning pipelines.
-------
Objective

Build a regression model that accurately predicts house prices based on 79 explanatory variables describing almost every aspect of residential homes.

The target variable is: SalePrice → the final price of each house (in USD)
------
**Dataset Description**

The dataset consists of: Train Dataset 1460 rows and 81 columns
Feature Types
Numerical features (e.g., LotArea, GrLivArea)
Categorical features (e.g., Neighborhood, MSZoning)
Ordinal features (e.g., ExterQual, BsmtQual)
-----
Workflow

1. Data Understanding
- Explore dataset structure
- Identify feature types
- Understand missing values

2. Data Cleaning
- Handle missing values
- Fix inconsistencies
- Remove or treat outliers

3. Exploratory Data Analysis (EDA)
- Univariate and multivariate analysis
- Correlation analysis
- Distribution of target variable

4. Feature Engineering
- Log transformation of skewed features
- Encoding categorical variables
- Creating derived features (e.g., total area, house age)
- Handling ordinal mappings
-----
Project structure
```
bootcamp\
|
├──Final-project/
     ├──house-price.csv
     ├──house-price-prediction.ipynb
     └── README.md
```
-----
How to Run

```
# Clone repository
git clone < https://github.com/abdulkadr53/bootcamp.git>

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```