# Boom Bikes Demand Prediction
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- We are trying to predict the demand of bikes so that the business can make a plan on how to position themselves in the market post covid and how to scale essentially.
- The dataset used is provided by Boom Bikes itself containing several data points of their historical sales of bikes.


## Conclusions
- Summer and Fall season have some upside in sales.
- If it is a working day the sales see a upside.
- In in initial months we can see a low sales and mostly the sales go up from the 5th month till 9th month and again at the end sales start dropping.
- holiday, weekday, temp, hum, windspeed, season_spring, season_winter, and year - are providing significant value to our model covering 80% of the variance on the training data and 78% variance on the test data.
- The demand is to be calculated by a formula 
cnt = 0.3908 - 0.0843 * holiday + 0.0449 * weekday + 0.4955 * temp - 0.3010 * hum - 0.2189 * windspeed - 0.1125 * season_spring + 0.0639 * season_winter + 0.2273 * yr_2019


## Technologies Used
- pandas - version 2.2.0
- seaborn - version 0.13.2
- numpy - version 1.26.3
- matplotlib - version 3.8.2
- scikit-learn==1.4.1.post1
- scipy==1.12.0


## Contact
Created by [@abhinav-mane] - feel free to contact me!