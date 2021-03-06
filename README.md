# Pyber_Analysis

## Overview
This is an in-depth analysis of data from the popular ride-sharing app PyBer. In this analysis, we explore relations between data collected from over 2,000 rides in 2019. This data is categorized based on the type of city where the ride took place: Urban cities, Suburban cities, and Rural areas. 

### Purpose
The purpose of analyzing this data is to view the relationship between the type of city and fare prices, number of rides, and number of drivers. The findings will help PyBer determine ways to increase access for consumers in underserved areas. 

## Results

### Comparing Urban cities, Suburban cities, and Rural areas
![PyBer Summary Chart](Plots_and_Figures/Fig8.png)

Comparisons of the data show that Rural areas have the fewest number of rides and drivers, Urban cities have the highest number of rides and drivers, and Suburban areas fall somewhere between. 

Naturally, due to supply and demand, the average cost of a ride in Rural areas is much higher than in Urban cities due to fewer available drivers. The average fare per driver is similarly higher in Rural areas. We can see visualized below the correlation between higher driver counts and higher number of rides with low average fare per ride. Rural areas with fewer drivers and fewer rides have a significantly higher fare per ride while Urban cities with high number of drivers and high number of rides have a significantly lower fare per ride.

![Average Fares by City Type and Driver Count](Plots_and_Figures/Fig1.png)

Despite the higher average fare per ride in Rural areas, Urban cities and Suburban cities more than make up for the lost revenue in volume of rides. The total fare in Urban cities is almost ten times that of the total fare in Rural areas. This is visualized in the below figure:

![Total Fares by City Multi-Line Graph](Plots_and_Figures/Fig9.png)

## Summary
Despite the higher average fare per ride in Rural areas, there are simply not enough rides to compensate for the large disparty in Total Fare. To help address the disparities between Urban cities, Suburban cities, and Rural areas, we would recommend:
- Operating at a loss, or with a lower profit margin, in Rural areas in order to increase popularity of the PyBer app amongst residents of Rural areas, and gradually raising prices as popularity increases and competitors are priced out. 
- Increasing the number of drivers available in Rural areas, possibly by moving drivers from Urban cities. 
- Reducing the number of available drivers in Urban cities in order to justify raising the fare per ride, increasing profit margins. 