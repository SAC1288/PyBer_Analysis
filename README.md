# PyBer Analysis Report

## Section I: Project Overview

The purpose of this project was to analyze ride-sharing data information for PyBer and produce an analytical report that summarized the information we found. We covered 120 cities with 2,375 ride-sharing data points. The period covered was between January 1, 2019 – May 8, 2019. The focus of this analysis was to determine underserved areas, particularly among urban, suburban, and rural cities. Our analysis is presented in the following sections.

## Section II: Project Results

Again, we analyzed the location information based on urban, suburban, and rural cities. We checked the data to see if there were any other categories for cities or missing values and there were none. We performed additional preliminary analyses to determine if any of the other categories within the dataset had missing, null values or other types of incomplete information. They did not. As a result, we were able to proceed and perform the analysis. 

We collected the following metrics for all three city types: 

•	The total rides for each city type.

•	The total drivers for each city type.

•	The total fares for each city type.

•	The average fare per ride for each city type.

•	The average fare pr driver for each city type.

<img src="Resources/PyBer Summary DataFrame.png">

**Figure 2-1**

The numbers for each category are presented in Figure 2-1. Urban cities had by far the highest number of rides among all three city types with about 68% of all the rides within the ride-sharing data. In addition, urban cities also had the highest number of drivers, comprising of 81% of all the drivers within the data set. On a macro level, this makes sense given that urban cities have larger populations than suburban and rural cities. This means that there is both more demand for ride-sharing services and a greater ability to provide drivers since there are more workers as well. 

When we proceed onto the fare metrics, we can see that Urban cities had the highest amount of total fares at $39,854.38 for the four and ½ month period. In terms of the average fare per ride and the average fare per driver, however, Urban cities was at the bottom of both of these categories. Indeed, if you compare the amount of fares brought in per driver, rural city drivers brought in almost five times as many fares as their urban counterparts. 

What possible explanation could be given for the lover amount of average fare per rider and per driver data for cities closer to urban areas? We believe that the major contributor to this phenomenon is that the supply of drivers in more urbanized cities greatly exceeds consumer demand for those areas. We suspected this at first when we noticed that the number of drivers for urban cities (81% of all city drivers) exceeded suburban and rural drivers at a greater degree than the number of rides for urban cities (68% of all rides) exceeding those for the other two city categories. Still, we wanted to further quantify the difference and so provided the following table in Figure 2-2:

<img src="Resources/Drivers Per Ride Table.png">

**Figure 2-2**

The above figure better quantifies the degree of how much the supply of drivers exceeds demand for ride-sharing services for each city type. For each city type, we took the total number of drivers and divided them by the number of rides and came up with a new metric called “drivers per ride”. In essence, this shows the number of drivers available per ride. Urban cities had a greater amount of drivers available per ride at almost 1.5 drivers per ride compared to suburban and rural areas which each had about .62 and .78 riders available for every ride. 

Again, the greater amount of supply in comparison to demand means that prices will come down in those areas. On the flip side, this would explain why rides are so much more expensive for suburban and rural areas. As a result, our solution to PyBer will consist of recruiting more drivers in cities that are further out of urban areas so that ridesharing is more affordable in those areas, thereby stimulating even more demand and generating more company revenue. 

Finally, we wanted to analyze weekly total fares for each city type within the data to determine if there was a relationship among the three categories. Our analysis is presented in the multi-line chart in figure 2-3:

<img src="Analysis Folder/PyBer Fare Summary.png">

**Figure 2-3**

With the exception of a few points, the graph generally does not exhibit a strong positive relationship among all three city types (i.e., when one city type experiences a rise in fares, then so do the other two categories). Nor does the chart show a strong negative relationship among all three city types (i.e., if one or two city types experience a rise in fares then one or two of the other city categories experience a decline and vice versa). Without calculating the exact correlations for each city type among all the others and given that we cannot observe a strong relationship of any kind among fares for all three city types, we conclude that there is probably no relationship among fares among all three city type categories. 

From an economic standpoint, this conclusion would make sense. Assuming general macro-economic conditions remain the same, we would expect that micro-economic conditions would vary (greatly even in some areas of the country) among urban, suburban, and rural cities across the country. This is due to smaller economies having a greater degree of economic variation (amongst employment, the supply of money, the amount of industries within their areas, the types and amounts of government regulations, etc.) at the local level. As a result, the supply-demand conditions would be different for every city within the same city type and even for those across different city types. 

## Section III: Summary

After analyzing the data and discussing its implications with the analytics team, we recommend that PyBer take the following actions to address underserved areas:

1.)	Provide an initial signing bonus in suburban and rural areas so that more people sign up to become PyBer drivers.

2.)	An analysis by GLG Insights shows that a majority of Uber and PyBer drivers are part-time1. Therefore, in order to address supply issues, particularly in less urbanized areas, we believe that PyBer should incentivize part-time drivers to become full-time by providing higher rates of compensation and benefits.

3.)	Finally, we believe that a cost-sharing plan should be incorporated to attract more drivers to PyBer in underserved areas. We understand that many of the rides include driving greater distances for drivers in rural and suburban areas. As a result, we believe that we can help cover some of these costs so that drivers can lower their fares. This will reduce margins some but we believe that the resulting increase in revenues from lower prices will greatly offset those expenses. 

We believe that all three of these proposals will increase the supply of drivers in underserved areas, which should lead to lower fares and thereby stimulate more demand for our ride-sharing services. We will need to collect more data after implementing this program and make adjustments as they come. This is the end of our report so please reach out to us if you have any questions. 

## Works Cites

1.)	“Uber and Lyft: How Driver Incentives Drive Retention.” GLGInsights. 4th of December, 2021. https://glginsights.com/articles/uber-and-lyft-how-driver-incentives-drive-retention/

