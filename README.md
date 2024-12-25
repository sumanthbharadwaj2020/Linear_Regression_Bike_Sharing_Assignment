# Linear_Regression_Bike_Sharing_Assignment
Bike Sharing Assignment

## Table of Contents
* General Information
* Conclusions
* Technologies Used

## General Information
The project is to build a multiple linear regression model for the prediction of demand for shared bikes.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The aim of the project is to build a model that answers 
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

The dataset used in the model is `day.csv` file.

## Conclusions
Based on final model, 

following are the factors that positively impact the bike rental
* temp
* yr             
* day_Saturday
* mnth_Sep
* workingday
* mnth_Oct

following are the factors that negatively impact the bike rental
* w_light_rain
* windspeed
* season_spring
* w_cloudy
* mnth_Jan
* mnth_Jul

`temp, yr and w_light_rain has more impact on the final impact than other independent variables`

## Technologies Used
* Pandas
* NumPy
* Seaborn
* Matplotlib
* ScikitLearn
* Statsmodel

## Contact
Created by [sumanthbharadwaj2020] - feel free to contact me!

