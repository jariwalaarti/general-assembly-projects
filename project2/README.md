# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Data & Kaggle Challenge



### Problem Statement


The aim of this project is to create and evaluate regression model for predicting the price of a house in Ames city at the time of sale. We also would like to get a better understanding of the features which has prominent impact in increase or
decrease of the sale price.


### Executive Summary


Property is one of the most expensive investment for most of us. It is very crucial for seller or buyer to get a good deal out of it and maintain the property market.

This project is to predict as accurately as possible, the selling price of a house in Ames based on features of the house provided as data. Along with predicting, we would also like to get better understanding for which features/factor highly impact the price. This may help the seller to estimate the price for which he can sell his house by not under pricing and losing the profit. Similarly buyer would know when the seller is over demanding.

The following process has been carried out for predicting and understanding the correlation among the factors involved for predicting the sale price.

**Data Cleaning:**

Data cleaning has been carried out for both train and test data. It involves imputing null values, changing data types, adding and manipulating fields.

**Exploratory Visualization:**

Exploring each feature through graph, their distribution and their correlation with Sale Price which may help in selecting or dropping a feature and removing outliers.

**Feature Engineering & Preprocessing:**

Create One hot encoded variables for all the nominal fields which will be used for modelling.

**Data Modeling & Evaluation:**

Lasso regression has been used for feature selection. Once the most impactful features are selected, they are evaluated using Linear, Ridge and Lasso regression model.

**Prediction:**

Based on the best model selected during evaluation, prediction is carried out using the test data and submitted on Kaggle. 

**Conclusion & Recommendation**

Based on the prediction and evaluation, further recommendations are provided.

### Dataset

There are two datasets provided by Kaggle. One is train.csv and other is test.csv.

Train dataset is cleaned and is exported to 'housing_train_cleaned.csv' file and further modelling is done using this cleaned file. Test dataset is cleaned and is exported to 'housing_test_cleaned.csv' file and is used to generate the final predictions.

This process has been carried out in 3 notebooks:

Train_Clean_EDA - Clean and EDA for Train data and exporting to housing_train_cleaned.csv

Test_Clean - Clean data and exporting to housing_test_cleaned.csv

Modelling - Creating and evaluating models, predict and conclude.


### Conclusion & Recommendation:

Based on the analysis following are the features that have greater impact on increase of the sale price:

- Ground Liv Area
- Overall material finish and quality of the house
- Exterior quality and condition
- Newly constructed house
- Neighbourhoods: Northridge Heights, Stone Brook
- Basement Area
- Land Area
- Kitchen quality

However one of the main reason that was noticed for price drop is age of the house. As the age of the house increases, price decreases.

Hence, would recommend to consider the factors mentioned above while buying/selling a house.

