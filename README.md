# Bike Sharing Problem (BoomBikes)

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* [Basic Info](#Basic-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Basic Information
- General information about the dataset
    Data columns (total 16 columns):
    #   Column      Non-Null Count  Dtype  
    ---  ------      --------------  -----  
    0   instant     730 non-null    int64  
    1   dteday      730 non-null    object 
    2   season      730 non-null    int64  
    3   yr          730 non-null    int64  
    4   mnth        730 non-null    int64  
    5   holiday     730 non-null    int64  
    6   weekday     730 non-null    int64  
    7   workingday  730 non-null    int64  
    8   weathersit  730 non-null    int64  
    9   temp        730 non-null    float64
    10  atemp       730 non-null    float64
    11  hum         730 non-null    float64
    12  windspeed   730 non-null    float64
    13  casual      730 non-null    int64  
    14  registered  730 non-null    int64  
    15  cnt         730 non-null    int64  
    dtypes: float64(4), int64(11)

> Dataset is very much clean and there is no missing values but some of the categorical variables are formated as integer. By referring the data dictionary again    converted it to categorical variable for the analysis and we drop some of the variables which are not required for the analysis.



- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?


## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!
