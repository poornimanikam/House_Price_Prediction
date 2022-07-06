# House Price Prediction Assignment
> Build the Linear Regression model for House Price Prediction.


## Table of Contents
* [General Info](#general-information)
* [Data Understanding](#technologies-used)
* [Data Visualization](#Data-Visualization)
* [Data Splitting](#Data-Splitting)
* [Model Building and Evaluation](#Model-Building-and-Evaluation)
* [Assumption Validation](#Assumption-Validation)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

- What is the business probem that your project is trying to solve?

It is required to build the model to predict the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?

Dataset is available in “.csv” format.

## Data Visualization:
The analysis of categorical and numerical variables are done.
Categorical variables are analyse with box plot and count plots.
Numerical variables are analise with pairplots and heatmaps.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Spliting:
The given dataset is splitted into train and test dataset in 70-30 proportion.


## Model Building and Evaluation:
Total 3 models are build Linear , Ridge and Lasso regression and finally Lasso Regression is finalise as our final model for House Price Prediction.

## Assumption Validation:
Linear regression assumptions are check whether they are valid for for final model or not.

## Conclusions

Lasso regression performs well and is consider as final model.
The most important features are:
1. GrLivArea	
2. OverallQual
3. TotalBsmtSF
4. BsmtFinSF1	
5. Neighborhood_StoneBr


## Technologies Used
- pandas - version 1.3.4
- numpy - version  1.20.3
- matplotlib - version 3.4.3
- seaborn - version  0.11.2
- sklearn - version 0.24.2

## Contact
Created by [@poornimanikam] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->