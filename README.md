# Bike Sharing Assignment
> This is a programming assignment to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
A US-based bike-sharing company, Boom Bikes, has recently experienced significant declines in revenue due to the ongoing COVID-19 pandemic. The company is struggling to stay afloat in the current market environment. In response, it has decided to develop a strategic business plan aimed at boosting its revenue once the lockdown ends and the economy returns to normal.

The company seeks to determine:

Which factors are most important in predicting the demand for shared bikes.
How effectively these factors explain the fluctuations in bike demand.
Using data gathered from various meteorological surveys and insights into people's behaviors, the company has compiled a comprehensive dataset on daily bike demand across the US, taking into account several key factors.

Business Goal:
You are tasked with creating a model to predict the demand for shared bikes using the available independent variables.
This model will help management understand how demand fluctuates based on various factors, enabling them to adjust their business strategy to align with demand levels and meet customer expectations.
Additionally, the model will serve as an effective tool for management to grasp the demand dynamics in new markets.

## Conclusions
According to our final model, the top three predictor variables influencing bike bookings are:

1. Temperature (temp): A coefficient value of ‘0.5683’ suggests that for each unit increase in temperature, the number of bike bookings increases by 0.5683 units.
2. Weather Situation 3 (weathersit_3): A coefficient value of ‘-0.3176’ indicates that, compared to Weathersit1, a unit increase in Weathersit3 leads to a decrease of 0.3176 units in bike bookings.
3. Year (yr): A coefficient value of ‘0.2316’ implies that for each unit increase in the year variable, the number of bike bookings rises by 0.2316 units.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python,Numpy,Pandas,Matplotlib.pyplot, Seaborn
- %matplotlib inline
- Google Colab


## Acknowledgements
Give credit here.
- This project/assignment is part of curriculum the Upgrad & IITB AI and ML Program 

## Contact
Created by [Rohit Harbola] - feel free to contact me!
Contact 9045267723
url:https://github.com/harbu1234/BoomBikes.git


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
