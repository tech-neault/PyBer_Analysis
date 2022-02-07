# PyBer Ridesharing Analysis
## A Look into PyBer's Ridership and Demographics

## Overview
This analysis has been requested by PyBer in order to examine the shares of each market type (City, Suburban, and Rural). By merging two datasets, we combined rider and city data to create a new Data Frame that includes a summary of total rides, total drivers, total fares ($), average fare per ride, and average fare a driver makes per ride. Then, the data was resampled with a focus on January to April 2019. We found the average fare per week during this time for each market type. The data from these analyses have been summarized below to provide understanding and recommendations for the future to PyBer's CEO.


## Results
![farebycityresampleimage](https://github.com/tech-neault/PyBer_Analysis/blob/main/resampled_dates.png)

From this multiple line chart, we can visualize how the total fares for each market type (Urban, Suburban, and Rural) vary from each other but appear stable over time. While there are bumps in the prices, each market shows a line that stays relatively stable. Price bumps can be due to many factors, so exact reasons cannot be deduced from this graph. 


### Breakdown By City Type
![summarydataframeimage](https://github.com/tech-neault/PyBer_Analysis/blob/main/Ride_DF.png)

This Data Frame provides a summary of different aspects of ridership and prices. 

Rural cities show the lowest overall ridership and the highest overall price per ride. However, rural cities also have the lowest number of PyBer drivers and the lowest fare total. From this information, we can consider that riders may need longer rides in rural areas due to remote locations and lack of walkability or public transport. There are fewer rural rides overall - the next closest number is Suburban, which has 5x more total rides. 

Urban cities show the highest ridership, number of drivers, and total fares in USD. Urban average fares are the lowest, with the average fare per ride at $24.53 and the average fare earner by the driver at $16.57. Urban ridership statistics could be explained by riders seeking more frequent and shorter rides.

Suburban cities are ranked in the middle on every aspect of this analysis. This suggests that suburban riders and drivers are currently well-served by PyBer.

## Summary and Recommendations

This analysis may be used to form future recommendations for PyBer's decision makers. Urban, Suburban, and Rural cities all have different needs, and PyBer can use their current data to ensure they are meeting those needs in different communities. 

- For example, based on ridership in rural areas, one potential avenue PyBer could consider is to provide incentives for riders to consider PyBer (like a coupon/discount on rides) and to increase rural driver recruitment. This could help rural citizens access transportation in parts of the country where there are no other options. 
     - Incentivizing new riders and drivers helps PyBer become more well-known, while providing job opportunities to people living in rural communities. 
- Suburban areas are well-served by PyBer, but may still benefit from additional incentives and coupons. PyBer could use these strategies to investigate whether or not investing in Suburban markets would be worth the expense by doing targeted trials, for example, sending coupons to riders who haven't taken a ride in a designated amount of time. 
- Urban areas see high ridership and low fares. This balances well, as riders will continue to use PyBer for reliable rides, and drivers will continue to earn fares by taking on the rider requests that come in. PyBer can continue to focus on this market as it is the largest share by far, and therefore creates the most revenue. 

