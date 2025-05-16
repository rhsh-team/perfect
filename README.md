# House Price Prediction

## Project Description
This project focuses on predicting house prices based on various factors like area, number of bedrooms, bathrooms, location, and other features. The dataset used contains information about various real estate properties and their prices, enabling a predictive model to estimate property values.

## Dataset Description
The dataset used in this project contains information about various real estate properties. It includes the following columns:
- **Id**: Unique identifier for each property.
- **Area**: The size of the property in square feet.
- **Bedrooms**: Number of bedrooms in the property.
- **Bathrooms**: Number of bathrooms in the property.
- **Floors**: Number of floors in the property.
- **YearBuilt**: Year the property was built.
- **Location**: Location of the property (e.g., urban, suburban, rural).
- **Condition**: The condition of the property (e.g., excellent, fair, poor).
- **Garage**: Whether the property has a garage.
- **Price**: The market price of the property.

## Data Overview
The dataset contains 2,000 records and 10 columns. It covers a wide range of property types, from rural to urban areas, and includes various property features. The price column ranges from $50,000 to nearly $1 million.

## Data Preprocessing and Exploration
The dataset has been cleaned and preprocessed, with null values handled, outliers detected and removed, and categorical variables encoded for analysis. Visualizations, such as histograms and box plots, have been used to explore the distribution of features like area, bedrooms, and price.

## Modeling and Evaluation
In this project, various machine learning models such as linear regression, decision trees, and random forests were applied to predict house prices. The models were evaluated using metrics like Mean Absolute Error (MAE) and R-squared to assess their accuracy.
