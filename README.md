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
The last bar-and-whisker plot we created was to examine the driver counts as a function of the city types.

![Fig4.png](/Analysis/Fig4.png)

Figure 4. Bar-and-whisker plot of the number of PyBer drivers as a function of the city type.



### Percentage of Total Fares by City Type


![Fig5.png](/Analysis/Fig5.png)

Figure 5. 



### Percentage of Total Rides by City Type


![Fig6.png](/Analysis/Fig6.png)

Figure 6.  



### Percentage of Total Drivers by City Type


![Fig7.png](/Analysis/Fig7.png)

Figure 7. 



### Total Fare by City Type


![PyBer_fare_summary.png](/Analysis/PyBer_fare_summary.png)

Figure 8. 



## Summary

