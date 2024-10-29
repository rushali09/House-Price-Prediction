# House-Price-Prediction

## Overview
House prices are influenced by various factors such as location, size, number of rooms, amenities, and market trends. This project leverages data science techniques to predict house prices based on these factors. It includes a detailed pipeline, from data preprocessing and feature engineering to model selection and evaluation, to find the best predictive model.

## Dataset
The dataset used contains several attributes related to houses, such as square footage, neighborhood, number of bedrooms and bathrooms, and year built. The target variable is the price of the house 
[Kaggle dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Installation
To run this project, ensure you have the following libraries installed:
``` git
pip install pandas numpy scikit-learn matplotlib seaborn
```
Clone this repository and navigate to the project directory:
``` git
git clone https://github.com/yourusername/House_Price_Prediction.git
cd House_Price_Prediction
```
## Exploratory Data Analysis

In this step, we explored the data to identify key patterns and relationships:

1. Descriptive Statistics: Summarized data distribution and identified key statistics like mean, median, and standard deviation.
2. Visualization: Plots such as histograms, scatter plots, and heatmaps helped visualize relationships between features and the target variable.
3. Insights: Identified correlations, important features, and potential outliers, which informed the feature engineering processes.


## Data Preprocessing

Data preprocessing steps included:

Handling Missing Values: Imputed missing values to avoid data loss or model biases.
Feature Engineering: Converted categorical variables to numerical, created new features, and performed scaling where necessary.
Data Transformation: Techniques like standardization and normalization improved model performance.

## Modeling
We implemented various machine learning models to predict house prices:

1. Linear Regression
2. Random Forest Regressor

## Evaluation 

Linear Regression:

Training Score: 0.6258
Test Score: 0.6207

Random Forest (Best Model):

Training Score: 0.9731
Test Score: 0.7995

The Random Forest model performed better than Linear Regression, especially in predicting on unseen data, with a higher test score indicating improved predictive capability
