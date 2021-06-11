# CASE STUDY ON SEOUL BIKE DATA PREDICTION

# Problem Statement

The aim of our model is to predict the number of bikes that will be required each hour for rental.

![123](https://user-images.githubusercontent.com/85668824/121725327-c0cf8580-cb06-11eb-8def-298198505634.gif)

# Dataset Information

Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour, and date information.

# Attribute Information

**Date** : day-month-year

**Rented Bike count** : Count of bikes rented at each hour

**Hour** : Hour of the day

**Temperature** : Temperature in Celsius

**Humidity** : Humidity in Percentage

**Windspeed** : Windspeed in m/s

**Visibility (10m)** : Visibility in metres

**Dew point temperature** : in Celsius

**Solar radiation** : MJ/m2

**Rainfall** : mm

**Snowfall** : cm

**Seasons** : Winter, Spring, Summer, Autumn

**Holiday** : Holiday/No holiday

**Functional Day - No(Non Functional Hours), Yes(Functional hours)**

# Task Completed:

Import Required Libraries

Data Summary

Outlier Analysis

Correlation Analysis

Variance Inflation Factor

Data Visualization

Feature Engineering

**Model-1**

Different Feature Selection Methods

1. Forward Selection
2. Backward Elimination

Recursive Feature Elimination

Cross Validation

1. K-Fold Cross Validation
2. Leave One Out Cross Validation

**Model-2 (after transformation of dependent variable)**

Assumptions After MLR Model

Random Forest Regressor


# Conclusions 

We have used Simple Linear Regression technique to build our prediction model.

We found that the adjusted R squared value is almost equal to the score of K Fold Validation technique.

We can conclude that the model performance is consistent across the train and test datasets.

We have tried using the Random Forest technique and got a good train score.

In future, we would like to use Non Linear regression techniques to improve prediction.

<h4>DATASET FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_ML_REGRESSION_ANALYSIS/blob/main/SeoulBikeData.csv'>Seoul Bike Data</a></h4>


<h4>CASE STUDY FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_ML_REGRESSION_ANALYSIS/blob/main/Seoul_Bike_Rental_Prediction.ipynb'>CASE_STUDY_STAR_TYPE_CLASSIFICATION_PROBlEM</a></h4>
