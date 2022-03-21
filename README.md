# Pyber_Analysis

## Overview of the Analysis

The CEO of Pyber, a ride-sharing service, has ask us to use our Python skills and knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type to analyse the differences in total drivers, total rides, total fares and fare's average. We are going to be looking at three types of cities: Urban, Suburban and Rural.

## Results

After merging our ride_data cvs and our city_data cvs we can use the group by function to get the total of rides, total of drivers, total fares, average fare per ride	and average fare per driver for each type of city.  See the link below for the code.

https://github.com/gotica462/Pyber_Analysis/blob/main/PyBer_Challenge.ipynb

Here are our results:

![image](https://github.com/gotica462/Pyber_Analysis/blob/main/Analysis/Table_summary.png)

As expected the total drivers and total rides are significantly greater in the Urban areas, but the drivers in the rural areas earn more money per ride. 


See the line graph below to see the fares for each city over time from January to April

![image](https://github.com/gotica462/Pyber_Analysis/blob/main/Analysis/Pyber_fare_summary.png)


As we can see the peak for all three types of cities is at the end of February. We can assume that people use the ride sharing services more when the winter is over.

## Summary

We can conclude that peope use the Pyber service less in rural areas but they travel longest distances and therefore earn more money, but the chances of making money in rural and suburban areas is significantly less than in urban areas based on the total number of rides. Fianlly we can see there is more competition in the urban areas. 

Based on our analysis we can make the following recommendations:

- Increase the incentive for the drivers in the urban areas. The total number of drivers in the urban areas is more than the total number of rides, which means some of the drivers did not even make a ride. We can assume that some of this drivers are not using the Pyber services as their primary income and only using sporadically. Increasing the incentives, maybe eachh dirver gets a little more revenue or establishing a reward point system would increase productivity among the drivers.

- Make the fares include not only the mileage, but also the time spend on the car. We can assume since urban areas are more compact, drivers travels less miles and therefore earn less money, but it is also possible that they spend the same amount of time in each ride due to traffic conditions. I would suggest doing an analysis using the mileage for each ride and the average time of each ride in each type of cities.

- Do more advertising in the urban areas. The table shows us that the number of drivers in the urban areas exceed the numbers of rides. We can theorize that in urban areas people are accostumed to use public transportation. If we can get the word out of our service, and doing promotions like first ride free, and do a good advertising campaign maybe we can get people in the urban areas to use more Pyber.












