# Project Name: House Price Prediction

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## General Information

### Project Background

**Problem statement**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


### Data Set

> The data is a CSV which contains information about past houses based on various factors like property age , pool area , Fireplaces , overall quality and condition of houses in various localities.

## Conclusions

**Final infrence**

These variables have the highest impact on sales price 


*   GrLivArea  - Above grade (ground) living area square feet
*   OverallQual - Rates the overall material and finish of the house
*   OverallCond - Rates the overall condition of the house
*   GarageArea- Size of garage in square feet
*   Fireplaces - Number of fireplaces 
*   BsmtFullBath  - basement full washrooms
*   TotalBsmtSF - Total square feet of basement area

Some of the factors which reduces a decrease in sales price are:



*   Property Age  
*   PoolArea - Pool Area in sq feet
*   MSSubClass - Identifies the type of dwelling involved in the sale.




## Technologies Used

- Pandas 
- NumPy 
- Seaborn 
- MatplotLib 
- Linear Regression
- Lasso Regression
- Ridge Regression

## Acknowledgements

This project was done as part of Case study for UpGrad IITB Programme on Artifical Inteligince and Machine Learning.
