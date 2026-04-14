## House Prices: Advanced Regression Techniques

-----
 Overview

This project is Advanced Regression Techniques, where the goal is to analyse the distribution of features and final sale price of residential homes in Ames, Iowa using advanced regression techniques and feature engineering.

The dataset includes a rich variety of numerical, categorical, and ordinal features, making it ideal for exploring data cleaning, feature engineering, and machine learning pipelines.
-------
Objective

The goal of this project is to analyze housing data and understand the factors that influence house prices. The focus is on:

- Exploratory Data Analysis
- Feature Engineering
- Data Preprocessing

This project does NOT include model training and evaluation.
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
bootcamp/
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
