# PyBer_Analysis

## Overview of Project/Purpose

### Pyber ride-share data is grouped and analyzed by three different city types: Rural, Suburban, Urban. A summary DataFrame and line chart are created from the raw data (Results section).                                                                                    The analysis is done using the pandas and matplotlib Python libraries. 


## Results
![alt text](https://github.com/specialcanadian/PyBer_Analysis/blob/main/Analysis/Pyber_summary_DF.png?raw=true)
Fig.1 (Summary DataFrame)                                                                                                                 Fig.1 shows a clear summary of our data sorted by the three city types. As expected, Urban cities have the highest totals, but lower averages                                                                                                                                            

![alt text](https://github.com/specialcanadian/PyBer_Analysis/blob/main/Analysis/RideShareChart.png?raw=true)
Fig.2 (Line Chart of Total Fares Per Week)
Fig.2 plots out the sum of the fares each week by city type. This visualization helps identify spikes in total fares. 



## Summary
Based on the provided figures, I would recommend three business strategies:
- Looking at Fig.1, the Average fare per driver in Urban cities is much lower than the other two. A possible explanation is because having 50,000 Urban drivers is overkill for the amount of Urban passengers. In this case, it would make sense to do another study focusing on different Urban cities, and see which ones require less drivers.
- Another cause could be a high number of inactive drivers, or drivers that only do Pyber part time. It is not uncommon for people to do gig jobs like this in addition to a regular job. It would make sense to fire drivers with inactive or very rarely used accounts, assuming the cost of keeping their account active is more than what they earn for the company.
- Given that Rural areas only account for 7% of the total fares, it wouldn't make sense to try and expand to more rural areas. The best option would be focusing efforts on Urban cities, where the total fares are much higher.      




