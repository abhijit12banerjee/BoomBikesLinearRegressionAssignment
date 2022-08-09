# Linear Regression Assignment on BoomBikes
> A US based company Boom Bikes provides bikes on rent, using Linear Regression we have to predict the factors which mostly affect the bike bookings and thus the company can analyze the factors and increase their busniess


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
# What is the background of your project?
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
-Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it.
-This bike can then be returned to another dock belonging to the same system
# What is the business problem that your project is trying to solve?
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.
- So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19 and have planned to prepare themselves according to the people's needs.
- They want to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
- The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
# What is the dataset that is being used?
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
# Conclusion 1 from the analysis
- The R-Square value of the Test Data is 0.80 which means 80% of the variation in the output variable is explained by the input variables.
- The Adjusted R-Square value of the Test Data is 0.79 which means 79% of variation is explained by only the independent variables that actually affect the dependent variable.
- The R-Square value of the Train Data set was 0.830
- The Adjusted R-Square value of the Train Data set was 0.827
- Thus we can say this is a Perfectly Fit Model where the independent variables perfectly predicts the demand for shared bikes
# Conclusion 2 from the analysis
- The Predicted variables are :
- yr (year)
- holiday
- temp (temperature)
- hum (humidity)
- windspeed
- season_2 (summer season)
- season_4 (winter_season)
- mnth_9 (September Month)
- weathersit_3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
# Conclusion 3 from the analysis
- The top 5 predictor variables which majorly affect the bike bookings are :
- temp - A unit increase in temperature variable increases the bike bookings by 0.60 units.
- hum - A unit increase in humidity variable decreases the bike bookings by 0.28 units.
- yr - A unit increase in year variable increases the bike bookings by 0.22 units.
- windspeed - A unit increase in windspeed variable decreases the bike bookings by 0.20 units.
- weathersit_3 - A unit increase in weathersit_3 variable decreases the bike bookings by 0.20 units.
# Conclusion 4 from the analysis
- Suggestions to the Business :
- Boom Bikes should try to reach out to maximum customers during summer and winter seasons especially in the month September.
- The company can give some attractive offers during high humidity, high windspeed and little bad weather as during this time there is a fall in customers.
- The company can also give some attractive offers during holiday as there is a fall in customers in holidays.
- The company can also expect an increase in customers in year on year basis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Machine Learning
- Linear Regression

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the assignment given by Upgrad in the model Linear Regression


## Contact
Created by [@abhijit12banerjee] 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->