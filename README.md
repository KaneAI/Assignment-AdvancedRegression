# Advance Linear Regression Asignment
> This project has been developed as part of my Masters in Artificial Inteligence and Machine Learning course with Upgrad  

# Problem statement
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data was provided in the train.csv file

# Objectives
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 The company wants to know:

 - Which variables are significant in predicting the price of a house, and

 - How well those variables describe the price of a house.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project will compare both ridge and lasso models
- We will use hyper parameter tuning to identify the optimal value of lamda (often also refered to as alpha)
- We will attempt to find the 5 most important features impacting house prices

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The top 5 features identified in the Lasso model where:
 - GrLivArea               ($212375.99)
 - OverallQualSq           ($115221.72)
 - LotArea                 ($111092.41)
 - BsmtFinSF1              ($78209.38)
 - Neighborhood_StoneBr    ($57023.84)

The values in brackets show how much value the feature can add to the sale price of a property
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.11.2
- Numpy - version 1.23.5
- Matplotlib - version 3.7.1
- Scipy - version 1.10.1
- Seaborne - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@KaneAI] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->