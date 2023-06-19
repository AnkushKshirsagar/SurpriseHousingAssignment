# Project Name
> Surprise Housing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
Essentially, the company wants —


- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.


### Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Following steps for final model:

1) Reading and understanding the data

2) Visualizing the data

3) Preparing the data for model training 

4) Splitting the Data into Training and Testing Sets

5) Linear Regression

6) Ridge Regression

7) Lasso Regression

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Optimal Value of alpha for Ridge and Lasso regression are:
    - Lambda for Ridge: 10
    - Lambda for Lasso: 0.001
- R2 for Ridge and Lasso are:
    - Ridge: Train – 94.39, Test – 86.76
    - Lasso: Train – 93.44, Test – 86.42

Looking at the above stats, it looks like both the models are doing a fairly good job, as the train R2 is
in the range of 93-94.5 and test R2 is around 86.5 for the both the models. <b>We can choose Lasso in
this case, as it helps in feature elimination, which increases the model interpretation.</b>

- 5 most important predictor variables are:
    - GrLivArea
    - OverallQual
    - SaleType_New
    - YearBuilt
    - Neighborhood_Crawfor

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas
- library - numpy
- library - seaborn
- library - matplotlib.pyplot
- library - sklearn
- library - statsmodels
- library - scipy
- library - Ridge from sklearn
- library - Lasso from sklearn
- library - GridSearchCV from sklearn 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@AnkushKshirsagar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->