# Project Name
### Problem Statement
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.
### Business Goal:
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- Train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Conclusion
- Lambda value
    - Ridge = 0.80
    - Lasso = 0.0001
- Mean Squared Error
    Ridge = 0.013368
    Lasso = 0.013358
- Based on Ridge Following Fetaures are are effective:
    - MSZoning_RL
    - MSZoning_RM
    - OverallQual
    - MSZoning_FV
    - TotalBsmtSF
    - OverallCond
    - GrLivArea
    - GarageCars
    - BsmtFinSF1
    - MSZoning_RH
    
- Based on Lasso Following Fetaures are are effective:
    - MSZoning_RL
    - MSZoning_RM
    - OverallQual
    - MSZoning_FV
    - TotalBsmtSF
    - OverallCond
    - GrLivArea
    - GarageCars
    - Foundation_PConc
    - BsmtFinSF1

As Mean Squared Error for Lasso is slightly lower than Ridge so following Features which may affect the pricing:
    - Zoning classification
    - Living area square feet
    - Overall quality
    - Condition of the house
    - Foundation type
    - Number of cars that can be accomodated in the garage
    - Total basement area in square feet and the Basement finished square feet area
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.0
- NumPy
- Pandas
- matplot
- seaborn
- sklearn
- statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Upgrad Assignment

## Contact
Created by [@swapnilkj89] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->