# Project Name
#### Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

The goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
- Exploratory analysis was done on the dataset based on continuous and categorical variables.
- For the continuous variables it was observed that temp and atemp follows a linear association with target variable cnt.
- There is a high correlation among atemp and temp. So a temp is dropped.
- Looking at the pair-plot among the numerical variables, the column temp has the highest correlation with target variable cnt.
- For the categorical variables it was observed that
    •	The number of people using bike sharing on holiday is less than non-holiday. Average number of bike sharing is slightly more on a working day.
    •	There is no significant impact of weekday on bike sharing count.
    •	A good weather situation attracting more bike sharing and it is least on bad weather.
    •	Average demand for bike sharing is gradually increasing from January to July and gradually decreases from july to december. July shows the highest average bike sharing. This might be a correlation of season.
    •	From 2018 to 2019, the demand for bike sharing has drastically increased.
    •	Demand for bike sharing is highest in the fall season and is least on spring season.
- The top 3 columns contributing towards demand are temp, yr and workingday
- The mean of residuals is found to be -1.040017745126801e-16 which very close to 0.
- The displots of the residual errors are normally distributed with mean 0 in both test and train dataset predictions
- In the scatterplot of residuals vs fitted values, there is no definite patterns observed. So it can be inferred that Homoscedasticity obtained
- So the chosen features seems proper

## Technologies Used
- jupyter notebook - version 6.0.3
- python - version 3.8
- pandas - version 1.0.5
- numpy - version 1.18.5
- matplotlib.pyplot
- seaborn - version 0.10.1
- sklearn
- statsmodels

## Acknowledgements
This project is created as part of upgrad assignment on linear regression. Thanks to upgrad for inspiring to work on interesting problems.

## Contact
Created by [@bakhortechnologies] - feel free to contact me!