# Project Name
>A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free . Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

This assigment builds a multiple linear regression model that helps predict demand for shared bikes with the available independent variables . It can be used to understand how exactly the demands vary with different features.  

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The primary Objective of the case study is to understand how and why the factors (variables)in the provided data set influences the demand for bike sharing in the American market. 

The study should enable the company to -
- Identify the signifant variables affecting the demand for shared bikes
- Create a quantitative model that can help in predicting the demand for shared bikes
- How well those variables describe the bike demands i.e. to know the accuracy of the model, how well these variables can predict demand for shared bikes.

The following steps are followed -
1. Reading the data
2. Understanding the data
3. Visualizing the Data
4. Data Preparing for modelling
   *  Dropping unwanted columns
   *  Co-relation checks
   *  Dummy variables creation,
   *  Splitting data into Training and Test Sets
   *  Rescaling of numerical variables
   *  Dividing data into X & Y sets for model building
5. Building the model using RFE & Training the model iteratively
6. Residual analysis of the training data
7. Prediction and evaluation on the test set
8. Final Evaluation

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on the coefficient values of our final model (lm_5), the top 3 predictor variables that influences bike bookings are:  
- Temperature (temp) - unit increase in temp variable could increase bike bookings by 0.5209 units.  
- Weather Situation 3 (weathersit_3) - a unit increase in Weathersit3 variable could decrease bike bookings by 0.2869 units.  
- Year (yr) - a unit increase in yr variable could increase bike bookings by 0.2328 units.  

In addition, the following variables also influence the demand in the order specified  
- windspeed: a unit increase in windspeed variable could decrease bike bookings by 0.1518 units.  
- season 4 (season_4): a unit increase in season_4 variable could increase bike bookings by 0.1381 units.  
- month 9 (mnth_9): a unit increase in mnth_9 variable could increase bike bookings by 0.1116 units.  

NOTE:
* temp : temperature in Celsius
* weathersit_3 : Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light 
* Rain + Scattered clouds
* yr : year
* windspeed: wind speed
* season_4 : winter
* mnth_9 : September
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Panda
- Numpy
- seaborn
- matplotlib
- plotly.express
- SciKit learn
- Statsmodels
- RFE (linearRegression)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Kaggle
- This project was based on courses taken from upgrad.


## Contact
Created by [@abe-twistedtech] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->