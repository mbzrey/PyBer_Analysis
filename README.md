# PyBer Analysis

## Overview of the Analysis

PyBer's CEO has asked for an analysis of the ride-sharing operations by city type, based on the data of number of rides, number of drivers, and fares in a time span of January 1st, 2019 through April 28th, 2019.


## Results

The analysis was performed on two data sources:
* Data on the number of drivers by city and type of city ("city_data.csv")
* Data on the rides ("ride_data.csv")

Based on those files, we could create a summary of the principal variables:

![image](https://user-images.githubusercontent.com/113773420/231286643-63433834-5998-48af-97ce-daf48a7c39a6.png)

Rural cities hace lowest number of rides and drivers. As expected, total fares are also the lowest in rural cities. However, avergae fares per ride and driver are the highest. As for the rides in urban cities, this effect happens on the exact opposite.

As for the dates of the rides, the total fares in each type of city is regular and doesn't show any upward/downward trends. Yet, it's noticeable that total fares are significantly higher in urban cities; suburban cities are the second highest type of city in total fares; and, the lowest are the total fares in rural cities.

![download](https://user-images.githubusercontent.com/113773420/231286076-9d867ff8-4470-445c-a9f1-2223b059910a.png)


## Summary

Based on the analysis performed, here are some recommendations for addressing any disparities among the city types:
* There are cities where the number of rides are extremely low. Consider further analyses on such cases, in order to take actions to improve the situation.
* It would be advisable to analyse the data further, considering the number of drivers and rides compared to the number of cities in every type: there are far more drivers in urban cities than in rural ones; however, the number of rides per driver ir high in rural cities, as is the fare per ride. That is, it seems that the ride-sharing operations are more efficient in rural cities.
* Suburban cities might be more profitable than urban cities, due to the higher number or rides and fares than in rural cities, and due to the better performance ratios (rides per driver and fare per ride) than the ones in urban cities.

