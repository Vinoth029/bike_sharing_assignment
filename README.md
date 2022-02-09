# Bike Sharing Problem (BoomBikes)

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
3. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market  based on some factors. 

## Business Goal
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* [Basic Info](#Basic-information)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Basic Information
- General information
    - Dataset is very much clean and there is no missing values. 
    - Dataset is having 15 columns and 730 rows.
    - It has integer, float and object datatype.

- Pre-processing
    - Below columns are dropped
        - 'instant'
        - 'dteday'
        - 'atemp'
    - All the columns are renamed for better understanding.

## Exploratory Data Analysis
- Count vs Weekday
    - On Weekends, the Non-Registered users are very high.
    - On weekdays, the Registered users are high
    ![](Graphs/weekdays.png)

- Count vs Month
    - counts are higher in the middle of the months. Especially in case of Non-Registered users.
    ![](Graphs/months.png)

- Count vs Different Seasons
    - Fall Season has the higher no of counts and spring season has the lower no of counts.
    - Counts are very higher in 2019 then 2018.
    - Approx 70% of the data are work days and 30% of the data are leave days(holiday and weekend) but still we can't see much difference. Hence we can say that in a year the proportion of total count for the bike rental is 50-50 for leave days and work days.
    - Only 2.87% of data are represending the holidays. Even with that low number of days we could see that count is higher in fall season (Autumn - Pleasant Environment) compared with weekdays which is the remaining 97% of days in a year.
    ![](Graphs/seasons1.png)
    ![](Graphs/seasons2.png)
    ![](Graphs/seasons3.png)








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
