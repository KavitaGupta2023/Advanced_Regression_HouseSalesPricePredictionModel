# Advanced_Regression_HouseSalesPricePredictionModel
This is Advanced Regression Model prepared for Housing company help to understand the factors impacting the sales price of Houses in Australian Market.
This would help A US-based housing company named Surprise Housing to understand the factors	that impacts the sales price for Houses in Australia and help them to decide on prospective properties to buy to enter the market
This will help company to make decisions to meet the demands and increase customer satisfaction which will inturn increase the business.


## Table of Contents
* [General Information]
* [Conclusions]
* [Technologies Used]
* [Acknowledgements]
* [Contact]


## General Information
- This is Advanced Regression Model for Housing Company
- A US-based housing company named Surprise Housing has decided to enter the Australian market. 
  The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
  For the same purpose, the company has collected a data set from the sale of houses in Australia
- We are builing a Advanced Regression Model using Ridge and Lasso regression to Sales Price trend with the available independent variables. 
 The company wants to know:
 Which variables are significant in predicting the price of a house, and
 How well those variables describe the price of a house.
  It will be used by the housing company to decide what properly to purchase based on property values and make profit.
- advertising.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Optimal Value of alpha for ridge and lasso regression is 500.
- R2 score for Ridge and Lasso are as below:
  Ridge  : Train data set - 0.933 , Test data set - 0.862
  Lasso  : Train data set - 0.940 , Test data set - 0.904
  Based on above Lasso seems to be better model having Train and test score very close.
- Following variables are the top 5 key variables out of 73 selected by Lasso model to impact the demand:
  GrLivArea, TotalBsmtSF, OverallQual(Excellent), OverallQual(Very Good), BsmtFinSF1
  All other variables can be found in the python code or the document.
  


## Technologies Used
- Python 3.10.9
- matplotlib 3.7.0
- seaborn 0.12.2
- sklearn 1.2.1
- statsmodels 0.13.5


## Acknowledgements
- This project was inspired UPGRAD learning platform
- References : https://learn.upgrad.com/course/4616/segment/27464/233859/714264/3605524
- This project was based on https://learn.upgrad.com/course/4616/segment/27464/233860/714268/3605551


## Contact
Created by https://github.com/KavitaGupta2023 


