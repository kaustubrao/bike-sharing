# Bike sharing assignment
> The objective of this assigment is to build a multiple linear regression model for the prediction of demand for shared bikes, in order to understand the drivers of demand as well as the effect size of these drivers
> It also contains the PDF containing the answers to the subjective questions asked as part of the assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the pandemic. 
- The company is finding it very difficult to sustain in the current market scenario. 
- So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- The objective is to determine variables are significant in predicting the demand for shared bikes, as well as measuring the effect size of those variables
- The model will be used to understand the demand dynamics of new markets and mould the business strategy accordingly
- The dataset consists of bike daily bike rentals from 2018 and 2019, along with useful information such as temperature, weather, humidity, etc.


## Conclusions
- Temperature has the largest effect on rentals (positive - higher temperatures correlate with higher rentals)
- Snow/Rain seems to have a large negative effect on rentals, while misty or cloudy weather also has a negative effect, but much smaller in size
- There is also a growth factor with time - one can anticipate higher demand in the secind year post launch as compared to first
- Windspeed and humidity also have a moderate negative effect on rentals
- Spring has the lowest demand by far, with summer and fall having the highest


## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.23.5
- seaborn - version 0.12.2
- matplotlib - version 3.7.0
- statsmodel - version 0.13.5
- sklearn - version 1.2.1


## Contact
Created by [@kaustubrao] - feel free to contact me!