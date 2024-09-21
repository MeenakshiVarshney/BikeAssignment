# Bike Sharing
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demand.
Goal:
Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Using Linear regression, build model to find the variables which are significant the demand for shared bikes with the available independent variables.
- day.csv is dataset provided for this problem

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In the Fall season bookings are more compared to other seasons and in each season the booking count shows increasing trends from 2018 to 2019.
- Most of the bookings have been done during the 2nd & 3rd quarter of the year. The Trend increased starting of the year till mid of the year and then it started decreasing as we approached the end of the year. The booking count shows increasing trends from 2018 to 2019 for each month.
- Clear weather attracts more bookings & booking increases from 2018 to 2019 for each weather.
- Thu, Fir, Sat have a greater number of bookings as compared to the start of the week.
- On the Holiday booking is less compared to non-holiday days.
- Booking seemed to be almost equal either on working days or non-working days.
- Linear regression equation : cnt = 0.134 + 0.2328*year + 0.547*temp - 0.1*holiday -0.153*windspeed+ 0.08*summer + 0.13*winter +0.099*sept -0.049* sun - 0.288*light_snowrain - 0.080*Misty_Cloud
- Demand of bikes depend on year, holiday, temp, windspeed, sep,summer, winter, Light_snowrain, MistyCloud & Sunday.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - Version 3.11.7
- Numpy - Version 1.26.4
- Pandas - Version 2.1.4
- matplotlib - Version 3.8.0
- seaborn - Version 0.12.2
- sklearn - Version 1.2.2
- statsmodels - Version 0.14.0
- Jupyter Notebook - Version 7.0.8
- JupyterLab - Version 4.0.11
- Anaconda Navigator - Version 2.5.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Linear regression Upgrad model


## Contact
Created by @Meenakshi1112- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
