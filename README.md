# Project Name: Housing Case Study

Australia Housing - Assignment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know (Problem statement for our assignment):

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Data Cleaning and Outlier Management](#DC-OM)
* [Model Building](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Info
- Raw data provided contains data set from sale of houses in Australia
- Data contains 81 Columns and 1460 Rows 
- We need to analyse this data and derive data that could help identify patterns. 


## Data Cleaning and Outlier Management
- Multiple plots are determined to examine data. 
- Null values are examined and columns with null greater than 40% are deleted.
- For numerical categorical variables we have assigned there relevant verbal description to prevent incorrect evaluation of model.
- Data normalization is done


## Model BUilding
Model was built using Ridge and Lasso for different values of Lambda. Also model was evaluated with multiple combinations of varibales. 

- Conclusion :
  Ridge : Train :90.9 Test :87.4
  Lasso : Train :89.8 Test :86.4
- Top 5 most significant variables in Ridge are:
  1 SaleCondition_Partial - 0.143
  2 SaleCondition_Others - 0.105
  3 SaleCondition_Normal - 0.099
  4 GarageFinish_Unf - 0.094
  5 GarageFinish_RFn - 0.092
- Top 5 most significant variables in Lasso are:
  1 SaleCondition_Partial - 0.198
  2 SaleCondition_Others - 0.12
  3 SaleCondition_Normal - 0.098
  4 GarageFinish_Unf - 0.084
  5 GarageFinish_RFn - 0.079
- These Varaiables are directly proportional to each other.
  Optimal Value of lamda for ridge : 10
  Optimal Value of lamda for Lasso : 0.001

## Technologies Used
- Jupyter Notebook 6.5.2
- GitHub 


## Acknowledgements
Give credit here.
- Upgrad tutorials


## Contact
Created by [@mvinayvenkatesh] - feel free to contact me!