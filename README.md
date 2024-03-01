# Predicting Ride Hailing Platform Fares
## Introduction
In the modern era of transportation dominated by ride-sharing services such as Uber and Lyft, an accurate understanding of the factors that influence the price of a ride is crucial for both users and providers of these services. As a data scientist, developing a Machine Learning model to predict Uber and Lyft prices based on a dataset from Kaggle about these two services in Boston, MA, was a strategic step taken to answer increasing market needs. 

The main goal of this project is to analyze and predict the prices of rides offered by two leading ride-hailing services, Uber and Lyft, using a machine learning approach. This analysis includes in-depth data exploration and feature engineering to understand the factors that influence prices and build models that can accurately predict prices.

## Main feature
This project offers several critical analysis and prediction features, including:

- **Price Comparison Analysis:** Compare prices between Uber and Lyft for the different types of services they offer.
- **Price Trend Exploration:** Analyze how prices fluctuate based on time of day, service type, and destination.
- **Feature Engineering:** Identifying and processing the most relevant features for use in prediction models.

## Methodology
The project methodology is divided into several main stages:

1. **Exploratory Data Analysis (EDA):** This stage involves data visualization and statistical analysis to understand the distribution, trends, and relationships between variables in the dataset.
2. **Feature Engineering:** This process involves selecting, transforming, and creating new features to improve the predictive capabilities of the model.
3. **Machine Learning Model Training:** Using linear regression as the main model to predict travel prices. This model was chosen because of its ability to handle linear prediction problems.

## Results
The developed model successfully predicts trip prices with a good degree of accuracy, as indicated by the evaluation metrics used (e.g., MAE, RMSE, and R^2). These results demonstrate the effectiveness of the approach used in analyzing and predicting prices in the context of ride-hailing services.

## File Descriptions

- Predicting_Ride_Hailing_Platform_Fares.ipynb: Main notebook containing the analysis and modeling process.
- Predicting_Ride_Hailing_Platform_Fares_Inference.ipynb: Additional notebook focusing on further model insights.
- encoder.pkl: Encoding method used in Linear Regression machine learning models.
- scaler.pkl: Scalling method used in Linear Regression machine learning models.
- list_cat_cols.txt: Categorical columns used as features in machine learning models
- list_num_cols.txt: Numerical columns used as features in machine learning models
- model_lin_reg: Linear regression machine learning model created in this project

## References

Dataset     : <a href="https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma">Uber and Lyft Dataset Boston, MA.</a>.  