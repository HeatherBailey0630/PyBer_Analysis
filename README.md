# PyBer_Analysis

## Overview

Utilized PANDAS, MATPLOTLIB, and Jupyter Notebook to analyze rideshare data and showcase the relationship between the type of city and the number of drivers and riders. The dataframes and charts created can be used to improve affordability and access for underserved neighborhoods. The cities were categorized into three types: Rural, Suburban, and Urban. 

## Results

### Rides
 - Rural: 125 rides
 - Suburban: 625 rides
 - Urban: 1625 rides
 
 ![Fig1](https://user-images.githubusercontent.com/106620821/180329775-0207b871-8505-4ef9-8bfc-cf490c677ad1.png)

 ### Drivers
  - Rural: 78 drivers
  - Suburban: 490 drivers
  - Urban: 2405 drivers
  
 ![Fig7](https://user-images.githubusercontent.com/106620821/180329940-3b113718-ca30-4c22-af69-9db00be3cdd6.png)

 ### Fares
 Sum of Fares-
 - Rural: $4327.93 
 - Suburban: $19,356.33
 - Urban: $39,854.38

 Average Fare Per Ride-
 - Rural: $34.62
 - Suburban: $30.97
 - Urban: $24.53

Average Fare Per Driver-
- Rural: $55.49
- Suburban: $39.50
- Urban: $16.57


 ![Fig5](https://user-images.githubusercontent.com/106620821/180329923-f1b68a87-aee3-4845-8fd3-1a8b9ef71924.png)

## Analysis

Total Rides Per City Type: There were far more rides in Urban cities than in rural cities with Urban cities having 1500 more total rides.

Total Drivers: Urban cities have a total of 2,327 more drivers than rural cities.

Sum of Fares: Urban cities have far greater overall total fares at $39,854.38, compared to rural cities at $4327.93.

Average Fares: Rural cities have a significantly higher fare per driver, and slightly higher fare per ride than Urban cities. 

We have one significant finding from this data. Although there are dramatically more drivers, rides, and sum of all fares in the Urban cities, the average fares per driver and per ride are significantly higher in Rural cities. One could assume that this is due to geography. Typically rural cities are more spread out, and people have to travel farther distances to get from A to B. Therefore, each ride is more expensive. In Urban areas, individuals typically travel short distances for short periods of time, but do so more often, and at a much higher volume.

## Summary

After dissecting the data and categorizing it by city type, we uncovered the total rides, total drivers, the total fares, the average fare per ride, and the average fare per driver. Our analysis shows that although Urban cities have far greater totals in most of these categories, the Rural cities have significantly higher average fares per driver and average fares per ride. This may be due to the geography of these areas. Customers in rural areas typically have to travel farther distances and therefore pay higher fares. My 3 business recommendations are as follows:

1. Implement a trial model in which customers in the "Rural" cities category will be charged fares based on categories of distance. For instance, if a customer needs to go between 1 and 10 miles, the charge is $x. If the customer needs to go between 10 and 20 miles, the charge is $y. And maybe a flat rate for distances greater than 25 miles. This may incentivize customers in rural areas to utilize the rideshare service more often and increase overall profit.
2. A similar process could be done in "Urban" cities. Incentivize the longer trips with higher fares by creating a rewards program in which every time a customer hits a milegage "milestone", they could receive x amount of free miles. 
3. For "Suburban" cities, an incentive program could also be put into place. For those traveling to the city on weekends, there could be a "city day" fare where rides into the city are discounted. A membership could be offered to those traveling to the city for work on weekdays which would increase overall rideshare useage.
