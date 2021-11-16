# Project Overview

The purpose of this project was to analyze 2019 Pyber data to observe how fares differed within different city types. Specifically, the goal was to provide insight into how average fare per ride and total weekly fares differed depending on the type of city in which they occurred. The city types examined were Rural, Suburban, and Urban.

# Results <br/>
### Average Pyber Ride Fares
![Fig1](https://user-images.githubusercontent.com/90878911/139337214-2a31a8d7-e8db-4090-9690-90c0e66925e8.jpeg) <br/><br/>


The plot above shows that generally, more densely populated (Urban) cities have more riders, more drivers per city, and lower average fares. Conversely, Rural cities have fewer riders, fewer drivers, and higher average fares. More analysis is needed to confirm why this is. Perhaps the average distance per ride is playing a role. Trips would likely be further in Rural areas where destinations are more spread out. Something else to dig deeper into might be the ratio of drivers to the number of rides given. In the table below, we can see that in Rural and Suburban areas, there are more rides given than there are drivers. In Urban areas, we see the opposite. The difference in supply vs. demand between city types could certainly be driving price differences. Again, more analysis would be needed to confirm this.

<img width="679" alt="Pyber_summary_df" src="https://user-images.githubusercontent.com/90878911/139339379-5d6e5e88-ffa3-4246-9683-76507e9234e0.png"><br/><br/>


### Total Weekly Fares by City Type (January-April 2019) <br/><br/>

![PyBer_fare_summary](https://user-images.githubusercontent.com/90878911/139340772-a8f1c2a2-ff1b-48be-861d-e10a52549b51.png)<br/><br/>

Looking at the chart above, we can see that each city type appears to fluctuate in similar patterns despite vastly different total fare revenue. Expanding the line plot above to include all of 2019 would help confirm that observation. Urban areas generate the highest amount of weekly fares despite having a lower cost per ride. We can attribute this to their outsized share of total rides. We can see from the pie chart below that Urban areas account for 68.4% of total rides: 

![Fig6](https://user-images.githubusercontent.com/90878911/139342330-14abf490-fde8-4501-8244-72a6adbd59c1.png)<br/><br/>

# Summary <br/><br/>

From the analysis above, we can see stark differences between the average cost of a Pyber ride and total weekly fares by city type. Specifically, while urban areas account for the biggest share of total weekly fares, average fares per ride are significantly higher in suburban and rural areas. This is not inherently problematic, but it does reveal opportunities for further analysis. My recommendations are as follows:
- Consider incentivizing more drivers in Rural and Suburban areas. These city types have higher average fares and a lower number of drivers per ride given, suggesting that demand has outpaced supply. More analysis would be needed to validate this.
- Consider identifying inactive drivers in Urban areas. Unlike Suburban and Rural cities, Urban cities have more drivers than riders. This could be making our driver count in Urban cities less useful and is worth exploring.
- Given that fare totals in each city type seem to ebb and flow similarly, marketing to each city type could be streamlined. Because fare totals move so similarly, it could be the case that seasonal campaigns/deals can be applied to all city types rather than curating marketing efforts to each one.



