# Predicting-the-Spanish-Power-Shortfall

## Overview
This is a team project at EXPLORE AI Academy were **Buhari Shehu, Rogers Mugambi, Junaidu Ibrahim, Izunna Eneude, Cephars Kefa and Peter Sumanu** worked together to build and evaluate various machine learning models to predict energy shortfall between renewable energy resource and the conventional fossil fuel source using the Spanish Power Shortfall Kaggle dataset

The government of Spain is considering an expansion of it's renewable energy resource infrastructure investments. As such, they require information on the trends and patterns of the countries renewable sources and fossil fuel energy generation. Thus we

- analyse the supplied data;
- identify potential errors in the data and clean the existing data set;
- determine if additional features can be added to enrich the data set;
- build a model that is capable of forecasting the three hourly demand shortfalls;
- evaluate the accuracy of the best machine learning model;
- determine what features were most important in the model’s prediction decision, and
- explain the inner working of the model to a non-technical audience.

## Data Wrangling
We wrangled the data to make it suitable for exploration and analysis. Thus, we:
- converted the time column to datetime
- imputed the missing values 
- replaced the outliers in barcelona pressure with the mean

## EDA
We carried out multiple exploratory data analyses to objectively understand the features in the dataset. 

## Modelling
We built  Multiple Linear Regression (MLR) model, RIDGE model, LASSO model, and Random Forest model. We evaluated these models by using accuracy and RMSE values and found out that Random Forest model best predict the power shortfall due to its lowest RMSE value.

## Conclusion
In conclusion we were able to built and evaluated various ML models to predict Spanish Power Shortfall and found out Random Forest model performs best with RMSE value of 1967.