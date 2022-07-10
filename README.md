# Big-Mart-Sales-Prediction
Big mart sales prediction is done by using linear, ridge, lasso regression algorithms.

# Problem Statement

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## Overview:
We are going to predict the Item_outlet_sales and our aim is to build a predictive model and predict the sales of each product at a particular outlet.

## The Data
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

Variable | Description
----------|--------------
Item_Identifier | Unique product ID
Item_Weight | Weight of product
Item_Fat_Content | Whether the product is low fat or not
Item_Visibility | The % of total display area of all products in a    store allocated to the particular product
Item_Type | The category to which the product belongs
Item_MRP | Maximum Retail Price (list price) of the product
Outlet_Identifier | Unique store ID
Outlet_Establishment_Year | The year in which store was established
Outlet_Size | The size of the store in terms of ground area covered
Outlet_Location_Type | The type of city in which the store is located
Outlet_Type | Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales | Sales of the product in the particulat store. This is the outcome variable to be predicted.

## Outlet Type:
![image](https://user-images.githubusercontent.com/104161233/178136159-96f0f23f-0efb-4e60-af07-6f1ed8af3844.png)

## Bivariate Analysis:
![image](https://user-images.githubusercontent.com/104161233/178136638-bc606e3b-3e61-46d4-9b58-f451cffc1677.png)


## Conclusion:
In this project, we tried to build a model using algorithms such as Linear regression, Ridge regression, Lasso regression, BayesianRidge regression and HuberRegressor to get the best possible prediction.
