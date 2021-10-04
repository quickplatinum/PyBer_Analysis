# PyBer_Analysis
## Module 5 Challenge : Matplotlib

## Overview of the analysis

- The CEO of Pyber has given myseld and my boss Omar a brand-new assignment. Using my  Python skills and knowledge of Pandas, I was tasked to create create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, the CEO requested that I create a multiple-line graph that shows the total weekly fares for each city type. Finally, in order tyo sunmmarize and showcase my knowledge I will submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers and the CEO at PyBer.

## Results

![Fig9](https://user-images.githubusercontent.com/88692025/135785985-9a89c75c-7eea-4865-901e-97faee7475c0.png)

- In order to analyse the data requested by the CEO, it was the best method to create Dataframes corresponding to each request. 
- The Table and Line Graph showacse a few of the findings and metrics discovered when creating this analysis, some of the varable chosen were total rides per 3 categories of city type (Rural, Sububran, and Urban). The categories seen here are Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average fare per Driver. 

![Fig8](https://user-images.githubusercontent.com/88692025/135786920-1a402264-0f16-45c3-a686-9311f3e2ec05.png)

- A few points of analysis can be made form the Table and Line Graph regarding each city type and variable:
1. Total Rides: The number of rides in Urban areas is the highest at Pyber, which is expected because it is the most populated city type so theire is a higher supply and demand for rides in this case. Suburban as second highest and Rural which is the least populated city type coming in last place.
2. Total Drivers: follwoing the same logic as the Total Rides, Total Drivers are also less concentrated in rural and subaurban areas in favor of Urban drivers. The gap is more substantial here, as trhere almost 2000 more drivers (2,405) vs (490) in Sububran areas and then (78) in Rural areas.
3. Total Fares, Total Average Fares and Average Fare per Driver: These 3 variables arte best described grouped together.
  3. the margins here are less wide than total rides and drivers. Total fares for rural areas are much higher as seen with an average fare per ride of $34.62 compared to $24.53 uban and $30.97 Suburban. Even with only 125 rides in rural areas, the driver fare and length of trip compensates for the low number of rides and keeps the total fare within a reoasnable range. Since the average fare and fare per driver is higher for rrual areas, it could be inferred that this is becvause drives are longer as more distance is covered compared to compact and smaller disntances in heavily populated Urban/Suburban areas.
4. Line Graph Time Trend: Another point of conclusion can be made when analysing the graph over time, the data ahows that despite a few spikes the trend within the data is consistent within all 3 city types over the period of analysis between Jan 2019 and May 2019.
  
## Summary Reccomendations

- In order to help the CEO of Pyber with this anlysis going forward and revealing more information, here are a few reccomednations on what might make the analysis more encomapssing:
1. Inlude the average distance of the trip for all 3 city types, inlcuding this data in the anlysis will help Pyber reveal if there is any link between the average fare per ride and the distance covered within the 3 city types. 
2. Much like the first point, another obvious point of future analysis is to include the average time of the trip, inlcuding this data in the anlysis will help Pyber reveal if there is any link between the average fare per ride and the distance covered within the 3 city types. So perhaps both distance and time can be combined to reveal if trips cover more/less distance or time and thus impact averag ride/driver fare.
3. Perhaps Pyber could add more fare charges to Urban riders since they are making mor emoney than the other segments
4. Since the analysis has revealed there are less rides and drivers in Rural areas, Pyber coould increase supply of drivers by incentivizing them to go to rural areas to work and earn more because of the higher average fare per ride and driver fare.
