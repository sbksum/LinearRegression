# Linear Regression Bike Sharing - Case Study  
> This project aims to build a multiple linear regression model for the prediction of demand for shared bikes. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project aims to build a multiple linear regression model for the prediction of demand for shared bikes. 

# Problem Statement

#### A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
#### A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

#### In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


#### They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

#### Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 



## Conclusions

- Count of total rental bikes (count) in year 2019 is 23.43% higher than that in 2018.
- Unit increase in temperature increases count by 48%
- Count is 9.7% higher in Winter season.
- Count is 29.02 % lower when there is light snow or rain.
- Count is 8.1 % lower when the weather is misty and cloudy.
- Unit increase in windspeed decreases count by 15%
- Count is 5.5% more on working day.
- Count is 5.5% lower in Spring season.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Pandas
- Numpy
- Matplot library 
- Seaborn library
- Statsmodel
- Sklearn
    - from sklearn.preprocessing import MinMaxScaler
    - from sklearn.feature_selection import RFE
    - from sklearn.linear_model import LinearRegression
    - from statsmodels.stats.outliers_influence import variance_inflation_factor
    - from sklearn.metrics import r2_score

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Wikipedia 


## Contact
Created by [@sbksum] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->