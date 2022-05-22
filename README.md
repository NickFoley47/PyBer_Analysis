# PyBer_Analysis

## Project Overview
Pyber requested that we conduct data analysis on ride-sharing data by city type and use the data to determine any recommendations for the CEO for addressing any disparities among the different city types. 

## Resources
-Data Source: city_data.csv, ride_data.csv
-Software: Jupyter, Python 3.6.1, pandas data analysis tool, conda 4.12.0
	
## Results:
Looking at our data, we can agree that Urban is the most popular city type for our company. Urban total fares are about 8 times more than rural and almost 2 times more than suburban. Total rides for urban are more than 2 times as much as suburban total rides and almost 13 times more than rural. Total drivers for urban are more than 3  times as much as suburban and 20 times greater than rural. We can see some disparities  for our rural customers. They do not have many drivers and the total rides are most likely due to the fare of the ride. The average fare per ride is $34.62 for a rural customer and $24.53 for an urban customer. 
- Urban data:
	- Total Rides: 1,625
	- Total Drivers: 2,406
	- Total Fares: $39, 854.38
	- Average Fare per Ride: $24.53
	- Average fare per Driver: $16.57
- Suburban data:
	- Total Rides: 625
	 -Total Drivers: 490
	- Total Fares: $19, 356.33
	- Average Fare per Ride: $30.97
	- Average fare per Driver: $39.50
- Rural data:
	- Total Rides: 125
	- Total Drivers: 78
	- Total Fares: $4,327.93
	- Average Fare per Ride: $34.62
	- Average fare per Driver: $55.49




Summary Data Frame:

![Summary]( https://github.com/NickFoley47/PyBer_Analysis/blob/main/analysis/Summary.PNG)

Analyzing the Total Fare by City Type graph we can observe 3 spikes in fares in February through April for our Urban customers. We have 1 spike for our Suburban customers We have 2 spikes for our rural customers. We can notice a relation of spikes at the same time around February, which I believe is representing Valentine’s Day for our customers. We can see suburban total fare increasing as the summer months approach. 

Total Fare by City Type:

![PyBer_fare_summary](https://github.com/NickFoley47/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)



## Pyber Recommendations:
My recommendations for Pyber:
1.	Increasing total drivers in the Rural area. Total rides will increase if we can decrease the average fare per ride. Rural has 125 rides with only 78 drivers while urban has 2,406 drivers for 1,625 drivers. 
2.	Offer incentives for drivers giving more rides in Rural areas. Allowing an incentive will help with completing my first recommendation while increasing drivers the average fare per ride will decrease. 
3.	We can offer incentives for our drivers on weekday evenings when most people are shopping and traveling. With this incentive we can increase our drivers and increase the total fares for all three city types. 
