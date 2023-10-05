# BoomBikes-Bike-Sharing-Assignment
## Linear regression model for the prediction of demand for shared bikes.

### Problem Statement

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### Essentially the company wants :

. To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.

. To identify the variables affectin g their revenues i.e. Which variables are significant in predicting the demand for shared bikes.

. To know the accuracy of the model, i.e. How well those variables describe the bike demands

. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## Business Goals

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Insights:
![Untitled](https://github.com/Naga1417/BoomBikes-Bike-Sharing-Assignment/assets/135252572/fe72468b-ccfd-4e92-879c-7f5c9d476f57)

The graph clearly shows the qualitative distributions of the data, now if the model suggests the important predictors, using these graphs we can be more confident about the predictions of the model.

1.The bike demand is almost constant throughout the week. there seems no trend in the weekday dataset thus we can leave this variable for the prediction.

2.There are no users when there is heavy rain/ snow indicating that this weather is quite adverse. Highest count was seen when the weather situation was Clear, Partly Cloudy.

3.The count of users decreased during the holidays.

4.From the "Workingday" boxplot we can see that maximum bookings happening between 4000 and 6000. There is not much of difference in booking whether its working day or not.

5.The number of rentals peaked in September, whereas they peaked in December. This observation is consistent with the observations made regarding the weather. As a result of the typical substantial snowfall in December, rentals may have declined.

### Calculating the r-squared

r2_score of train dataset 0.821846912469421

r2_score of test dataset 0.8033098399800022

### Key points from the the above model, BoomBikes should focus while going ahead with expansion plans:

1. Company should focus on expanding business during Fall, Summer and Winter
   
2. September month has shown great demand.
   
3. It has been observed that the demand for bike rentals had gone up from 2018 to 2019. So we can say that it will go up once the situation gets normal post Covid
   
4. There would be less bookings during Bad and no demand in Severe weather conditions.
   
5. There is no much demand during the holidays

### Significant variables to predict the demand for shared bikes

    holiday,
    temp,
    windspeed,
    Season - (Summer, Spring and Winter),
    months(July, September),
    Year,
    weathersit (Bad and Moderate).

   

