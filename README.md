# PyBer Analysis
## Overview of PyBer Analysis
####
The CEO of PyBer requested that raw data from two CSV files pertaining to rural, suburban, and urban regions be summarized with the use of charts. Shortly after the presentation of this data using Python and Pandas, the CEO requested a new analysis to be performed based solely on the ride-sharing data by city type. This new request focused heavily on tables to summarize the data in a readable format. A single line plot was also created to best display the weekly totals of fares by city type using Python, matplotlib, Jupyter Notebook, and Pandas. 

## PyBer Analysis Results
### General Results
#### 
Below are the findings from the analysis:

* Total Rides by City Type:
*   - Urban: 1625
*   - Suburban: 625
*   - Rural: 125
* Total Drivers by City Type:
*   - Urban: 2405
*   - Suburban: 490
*   - Rural: 78
* Total Fares by City Type:
*   - Urban: $39,854.38
*   - Suburban: $19,356.33
*   - Rural: $4,327.93
* Averge Fare per Ride:
*   - Urban: $24.53
*   - Suburban: $30.97
*   - Rural: $34.62
* Average Fare per Driver:
*   - Urban: $16.57
*   - Suburban: $39.50
*   - Rural: $55.49
 
The results outlined above are rather straight forward and easy to interpret. When looking at the totals for each city type, it is obvious that the urban cities will have the largest amount of riders and drivers due to a larger and centralized population. The further away from an urban city, the lower the totals drop. Rural areas, with the lowest total riders at just 125, showcases the reality of how most individuals in rural areas will typically have their own means of transportation compared to the 1,625 riders in urban cities that may not need to maintain their own means of travel. The averages follow a distinctly different trend as seen below in the pivot table. 
#### ![table_image](https://github.com/victoriaguille/PyBer_Analysis/blob/main/analysis/PyBer_Summary_DF.PNG)
In the pivot chart, rural cities had the highest fare prices per driver and ride compared to the urban cities. For a rural rider, it costs roughly ten dollars more a ride than it would for an urban rider. This can be a numerical demonstration of the reality that in rural communities, places of interest are further apart as the need for space isn't as great as it is in an urban community. Urban cities are pushed by the populations that come to live and work in these larger cities for the ease of central locations. Urban cities are built upon city centers with communities growing around these centers. With smaller distances to travel, the cheaper the fare for both drivers and riders. Suburban cities lie in the middle ground of these two extremes. 
### Weekly Results
####
The previous analysis that was performed focused heavily on comparing average totals by individual cities and city types, showing the trend witnessed in this analysis' pivot table regarding totals by city type. This new analysis uses a resample function to look at the weekly averages of fare prices by city type. Upon first glance, the below line plot shows the obvious results that the urban city type is the most profitable and the rural city type the least profitable. However, it can also be gleaned that there are spikes in activity across all three city types in late winter and mid spring. This particular format of the results also showcases in which months might be the slowest for PyBer or in the same vein, which months will be the best to employ changes for riders and drivers depending on the company's activity per city type. 
####
![plot image](https://github.com/victoriaguille/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
####
A quick glimpse at any of the charts and tables from either analysis performed for the CEO of PyBer shows there is great disparity between rural and urban cities with suburban cities sitting somewhere in the middle. Much of the disparity can be contributed to the way communities sprout up around these cities based on need and population. These types of differences cannot be addressed by a single ride-sharing company, however, some changes can be suggested to best serve both the company and customers. One of the most glaring challenge to combat would be the high cost per fare for a rural rider at the high price of $34.62. To attempt to drop the cost for the rider, and encourage more business, PyBer might be able to push promotionals in those regions during peak activity as seen in the plot chart. Potentially offering a few dollars or a flat fee regardless of distance could cut down on the high cost while also potentially encouraging new customers that may have balked at the high cost. Another disparity that appeared was the one between total total riders and drivers in urban cities. There are roughly 800 more drivers than riders, the largest gap of all the city types. Much like the potential flate fee for riders in rural cities, offering additional discounts or promotionals to riders may encourage more business in urban centers lagging in customers. 


