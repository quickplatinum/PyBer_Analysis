# PyBer_Analysis
## Module 5 Challenge: Matplotlib

## Overview of the analysis

- The CEO of Pyber has given myself and my boss Omar a brand-new assignment. Using my Python skills and knowledge of Pandas, I was tasked to create a summary Data Frame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, the CEO requested that I create a multiple-line graph that shows the total weekly fares for each city type. Finally, in order to summarize and highlight my knowledge I will submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers and the CEO at PyBer.

## Results

![Fig9](https://user-images.githubusercontent.com/88692025/135785985-9a89c75c-7eea-4865-901e-97faee7475c0.png)

- In order to analyze the data requested by the CEO, it was the best method to create Data frames corresponding to each request. 
- The Table and Line Graph showcase a few of the findings and metrics discovered when creating this analysis, some of the variable chosen were total rides per three categories of city type (Rural, Suburban, and Urban). The categories seen here are Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average fare per Driver. 

![Fig8](https://user-images.githubusercontent.com/88692025/135786920-1a402264-0f16-45c3-a686-9311f3e2ec05.png)

- A few points of analysis can be made form the Table and Line Graph regarding each city type and variable:
1. Total Rides: The number of rides in Urban areas is the highest at Pyber, which is expected because it is the most populated city type so there is a higher supply and demand for rides in this case. Suburban as second highest and Rural which is the least populated city type coming in last place.
2. Total Drivers: following the same logic as the Total Rides, Total Drivers are also less concentrated in rural and suburban areas in favor of Urban drivers. The gap is more substantial here, as there 2000 more drivers (2,405) vs (490) in Suburban areas and then (78) in Rural areas.
3. Total Fares, Total Average Fares and Average Fare per Driver: These 3 variables are best described grouped together.
  3. the margins here are less wide than total rides and drivers. Total fares for rural areas are much higher as seen with an average fare per ride of $34.62 compared to $24.53 urban and $30.97 Suburban. Even with only 125 rides in rural areas, the driver fare and length of trip compensates for the dwindling number of rides and keeps the total fare within a reasonable range. Since the average fare and fare per driver is higher for rural areas, it could be inferred that this is because drives are longer as more distance is covered compared to compact and smaller distances in heavily populated Urban/Suburban areas.
4. Line Graph Time Trend: Another point of conclusion can be made when analyzing the graph over time, the data shows that despite a few spikes the trend within the data is consistent within all three city types over the period of analysis between Jan 2019 and May 2019.
  
## Summary Recommendations

- In order to help the CEO of Pyber with this analysis going forward and revealing more information, here are a few recommendations on what might make the analysis more encompassing:
1. Include the average distance of the trip for all three city types, including this data in the analysis will help Pyber reveal if there is any link between the average fare per ride and the distance covered within the three city types. 
2. Much like the first point, another obvious point of future analysis is to include the average time of the trip, including this data in the analysis will help Pyber reveal if there is any link between the average fare per ride and the distance covered within the three city types. So perhaps both distance and time can be combined to reveal if trips cover more/less distance or time and thus impact average ride/driver fare.
3. Perhaps Pyber could add more fare charges to Urban riders since they are making mor money than the other segments
4. Since the analysis has revealed there are less rides and drivers in Rural areas, Pyber could increase supply of drivers by incentivizing them to go to rural areas to work and earn more because of the higher average fare per ride and driver fare.
