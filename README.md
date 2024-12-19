# Bike-Sharing-Assignment
Boombikes, a US bike-sharing provider wants to understand the factors on which the demand for it's shared bikes depends (specifically in American market):

The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
They have recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Business Goal:

Demand for shared bikes should be modelled with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Objectives: 
Boombikes, a US bike-sharing provider wants to understand the factors on which the demand for it's shared bikes depends (specifically in American market). They have recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Linear Regression model is to be developed to understand the important variables useful in predicting demand for shared bikes using the provided dataset.This will help the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
cnt = 0.20 + 0.23* yr+ 0.49*temp + (-0.15)*windspeed + (-0.07)*spring + (0.05)*summer + (0.08)*winter + (-0.28)*light-snow-rain + (-0.08)*misty + (-0.05)* jul + 0.07*sep + (-0.04)*sun 

- The R squared for training data is 84% and test data is 81%.  Adjusted R square for training data is 83% and test data is 80%.The model is fitting well on the training data and generalising fairly on the testing data 
- Three key features are temperature, ligh-snow rain (weather situation) and year.(High coefficient values)
- RMSE for training data is 0.091 and for test data is 0.096 indicating the model is fitting well on the training data and generalising fairly on the testing data 

## Recommendations
- Leverage High Impact Features: Temperature, Light-snow rain and Year have higher coefficients. Therefore, these features should be focused on when making business plan.
- Year: Positive coefficient suggests that bike demand increases over time.Continue monitoring long-term growth trends and plan for increasing infrastructure (e.g., more bikes and stations) accordingly.
- Temperature: Positive coefficient suggests that temperature has positive influence on demand.Promote biking on favourable warmer days through discounts or events.
- Windspeed: Negative coefficient suggests that windspeed has negative influence on demand.Provide wind-resistant gear or incentives on windy days to maintain demand.
- Seasonality: Negative coefficient for spring (-0.07) and positive for summer (0.05) and winter (0.08).Develop strategies to boost demand in spring (e.g., spring promotions) while leveraging naturally higher demand in summer and winter.
- Weather Situation: Negative influence from both light-snow-rain (-0.28) and misty (-0.08) conditions. Offer promotions or awareness campaigns encouraging biking in less favorable weather, emphasizing safety and comfort.
- Months: Negative coefficient for July (-0.05) and positive for September (0.07).Investigate potential reasons for reduced demand in July (e.g., vacations or extreme heat) and capitalize on increased September demand with targeted campaigns.
- Day: Organize special events to promote the demand on Sunday.
- Monitoring : Update the model with more recent data and adapt strategies based on evolving market conditions to ensure sustainable growth in revenue.

## Technologies Used
- Python - version 3.12.4
- Numpy - version 1.26.4
- Pandas - version 2.2.2
- Matplotlib - version 3.10.0
- Seaborn - version 0.13.2
- Statsmodels -version 0.14.2
- Scikit Learn - version 1.4.2

## Acknowledgements
- Live sessions of upGrad on Linear Regression Models
- UpGrad tutorials on Linear Regression on the learning platform
  
## Contact
Created by [Priyanka Gulati](https://github.com/pgulati9)
