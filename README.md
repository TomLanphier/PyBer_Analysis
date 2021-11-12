# PyBer Analysis
## Overview
PyBer, a ride sharing app company, needed an analysis and vizualizations of their data to improve access and affordability for underserved neighborhoods. They provided two sets of  their data from 2019. The first contained the cities they service, the number of drivers in each city, and the type of city. The second contained the a unique id for each ride they had serviced, the date and time of the ride, the city it occurred in, and the fare for the ride. The primary focus is to examine how the other variables (rides, drivers, and fares) can be extrapolated to provide insight and information as functions of the type of city.

## Results
### PyBer Ride-Sharing Data Overview
The first comparison of data that we generated was the ride sharing data as a whole. In Figure 1, the average fair is plotted as a function of the total number of rides in each city. The size of the circle correlates with the number of PyBer drivers in the city, and the color inside the bubble indicates the type of city.

![Fig1.png](/Analysis/Fig1.png)

Figure 1. Scatter plot of the average fare for a PyBer ride in a city plotted as a function of the number of PyBer rides in that city, with city types indicated by fill color and size of circle correlated to the number of drivers.

Rural cities appear to have fewer PyBer rides, more expensive average PyBer ride fares, and fewer PyBer drivers than suburban and urban cities. Urban cities tend to have more PyBer rides, cheaper average PyBer ride fares, and more PyBer drivers than suburban and rural cities. Suburban appears to be between urban and rural in those categories.

### Ride Count Data 
We looked more closely at the number of PyBer rides as a function of the city type, as shown in Figure 2.

![Fig2.png](/Analysis/Fig2.png)

Figure 2. Bar-and-whisker plot of the number of PyBer rides as a function of the city type.

We can clearly see from Figure 2 that the number of rides per city in urban cities is significantly greater than suburban as the average of the number of rides per city in urban cities is 24, while that is inbetween the maximum and the upper quartile for suburban cities and well outside the rural range. In fact, the minimum number of PyBer rides in an urban city is equal to the maximum number of PyBer rides for a rural city. The suburban cities have a smaller range in number of rides per city type than urban cities, but rural cities have the smallest of all. Since the median is so close to the lower quartile for rural, we know that the rural data is skewed toward less rides per city in the range. Since there is an outlier for the urban data set, we can determine the number of PyBer rides in urban cities can vary significantly, but do tend to be around the median of 24 rides per city. So as noted before, the urban cities have more rides than suburban cities which have more rides than rural cities.

### Ride Fare Data
Next we looked at all the PyBer ride fairs as a function of city type, as shown in Figure 3. 

![Fig3.png](/Analysis/Fig3.png)

Figure 3. Bar-and-whisker plot of the PyBer ride fairs as a function of city type.

As noted from the summary plot, the urban fares tend to be less expensive than the suburban fares which tend to be less expensive than the rural fares. The medians of each city type show this. What's interesting is that the rural fares have a much wider range than the upper and lower quartiles for suburban fares are within the range of the upper and lower quartiles of rural fares. The same is true for the maximum and minimum values for suburban and rural fairs. The distribution of the fares seems to be relatively even for the urban and suburban cities within their respective ranges. We can say this because the the spacing between the minimum and lower quartile, lower quartile to median, median to upper quartile, and upper quartile to maximum are almost identical for the two datasets. The same cannot be said for rural.

### Driver Count Data
The last bar-and-whisker plot we created was to examine the driver counts as a function of the city types, as shown in Figure 4.

![Fig4.png](/Analysis/Fig4.png)

Figure 4. Bar-and-whisker plot of the number of PyBer drivers as a function of the city type.

From Figure 4 we can determine that there tend to be substantially more PyBer drivers in urban cities and in suburban or rural cities, and there tend to be more PyBer drivers in suburban cities than in rural cities. Even though the minimum number of drivers in an urban city is nearly halfway between the lower quartile and minimum number of drivers in suburban cities, we can say there tend to be more drivers in urban cities than in suburban cities because the lower quartile for urban cities is greater than the upper quartile of suburban cities. In other words, atleast 75% of the suburban cities have less drivers than at least 75% of the urban cities. At least 75% of urban cities and 50% of suburban cites have more PyBer drivers than all rural cities, and at least 75% of suburban cities have more PyBer drivers than at least 50% of rural cities. We can also see that the range in number of PyBer drivers in urban cities is substantial while the number of PyBer drivers in rural cities is pretty consistent, such that the minimum and bottom quartile for rural PyBer drivers per city is the same number.

### Percentage of Total Fares by City Type
All the box-and-whisker plots are helpful for examining the range and distribution of drivers, rides, and fares for each city type, but we wanted to see how they compare in quantity relative to eachother. So we moved to pie charts, first being the percentage of total PyBer fares coming from each city type, as shown in Figure 5.

![Fig5.png](/Analysis/Fig5.png)

Figure 5. Pie chart of the percentage of total PyBer fares generated from each city type.

From Figure 5 we can clearly see that most, almost two thirds, of the total fares are coming from urban cities, that nearly one third of fares are coming from suburban cities, and under 7% of fares come from rural cities. 

### Percentage of Total Rides by City Type
The next pie chart was to examine the percentage of total PyBer rides resulting from each city type, as shown in Figure 6.

![Fig6.png](/Analysis/Fig6.png)

Figure 6. Pie chart of the percentage of total PyBer rides from each city type.

Similar to the percentage of total fares by city type, urban cities account for over two thirds of the rides, while suburban cities account for just over a quarter, and rural cities account for about a twentieth of the rides. 

### Percentage of Total Drivers by City Type
The last pie chart was of the percentage of total PyBer drivers in each city, as shown in Figure 7.

![Fig7.png](/Analysis/Fig7.png)

Figure 7. Pie chart of the percentage of total PyBer drivers in each city.

Urban cities account for four fifths of the PyBer drivers, while suburban accounts for about three twentieths and rural is about one fourtieth of the drivers.

### Total Fare by City Type
The last graph we made was the total fares for each city type as a function of time, as shown in Figure 8. Data points are from each week while the months are labeled on the x-axis.

![PyBer_fare_summary.png](/Analysis/PyBer_fare_summary.png)

Figure 8. Line plot of the total fares generated by each city type over time.

We can see that urban cities consistently draw in the most fares, while rural draws in the least fares, and suburban cities are inbetween. At no point do they overlap.

## Summary
This data can be misleading if the number of PyBer drivers, total fares, and number of PyBer rides are not all examined. Rural drivers make up about 2.6% of the PyBer drivers, but they contribute to 7% of the total fares. Meanwhile urban city drivers make up 80.9% of the PyBer drivers but their fares are only 62.7% of the total fares. This juxtapostion is important because rural cities may not seem significant due to their small number of drivers per city, rides, and contribution to total fares, but they are generating more revenue per driver than urban drivers. Suburban drivers are similarly out-performing urban drivers, but not to the same extent as rural drivers. Based on the number of rides urban drivers are providing, there is a significant demand in urban cities. Before giving my suggestions, it needs to be clarified that there was no data provided about how much of the fare is profit for the company versus how much is going to the driver, how far the rides are or how the fare is determined, nor any information about competition. Thus these recommendations are given with caviots that they are extrapolated only from the data at hand, not considering the other factors.
1. Since 
