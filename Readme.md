# USAHousePricePredictionML
USA house price prediction Machine Learning model


## Overview

This project aims to predict house prices in the USA using various machine learning techniques.<br />
The dataset includes a wide range of features related to properties and their locations.<br />
The goal is to build a model that accurately estimates the price of a house based on its characteristics.<br />

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Modeling](#modeling)
- [Results](#results)

## Introduction

House prices in the USA vary significantly based on various factors such as location, size, and amenities. This project utilizes a dataset of housing information to train a machine learning model that can predict the price of a house based on its features.

## Data

The dataset used for this project includes the following features:

- **Date:** The date when the property was sold. This feature helps in understanding the temporal trends in property prices.
- **Price:** The sale price of the property in USD. This is the target variable we aim to predict.
- **Bedrooms:** The number of bedrooms in the property. Generally, properties with more bedrooms tend to have higher prices.
- **Bathrooms:** The number of bathrooms in the property. Similar to bedrooms, more bathrooms can increase a property’s value.
- **Sqft Living:** The size of the living area in square feet. Larger living areas are typically associated with higher property values.
- **Sqft Lot:** The size of the lot in square feet. Larger lots may increase a property’s desirability and value.
- **Floors:** The number of floors in the property. Properties with multiple floors may offer more living space and appeal.
- **Waterfront:** A binary indicator (1 if the property has a waterfront view, 0 other-wise). Properties with waterfront views are often valued higher.
- **View:** An index from 0 to 4 indicating the quality of the property’s view. Better views are likely to enhance a property’s value.
- **Condition:** An index from 1 to 5 rating the condition of the property. Properties in better condition are typically worth more.
- **Sqft Above:** The square footage of the property above the basement. This can help isolate the value contribution of above-ground space.
- **Sqft Basement:** The square footage of the basement. Basements may add value depending on their usability.
- **Yr Built:** The year the property was built. Older properties may have historical value, while newer ones may offer modern amenities.
- **Yr Renovated:** The year the property was last renovated. Recent renovations can increase a property’s appeal and value.
- **Street:** The street address of the property. This feature can be used to analyze location-specific price trends.
- **City:** The city where the property is located. Different cities have distinct market dynamics.
- **Statezip:** The state and zip code of the property. This feature provides regional context for the property.
- **Country:** The country where the property is located, this feature is included for completeness.

### Data Source

The dataset is sourced from Kaggle and is available for download [here](https://www.kaggle.com/datasets/fratzcan/usa-house-prices).

## Installation

To run this project locally, you'll need to have Python installed, along with the necessary libraries. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Modeling

The following machine learning algorithms were implemented and evaluated:

- **Linear Regression**
- **Decision Trees**
- **Random Forest**
- **Gradient Boosting**
- **XGBoost**

### Model Selection

The best-performing model was chosen based on metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared score.

### Results

- **Best Model:**
- **MAE:**
- **RMSE:**
- **R-squared:**

