# PyBer Analysis

## Overview
Create a ride-sharing data by city type to create a multiple-line grahp showing total weekly fares for each city type that summarizes how data differs by city type to help Pyber decision-makers.

## Process
1. Import provided data contain on `CSV` files
2. Review data
3. Merge rides and city data

## Resources
* Data Source: `city_data.csv` and `rides_data.csv` files.
* Language:
  - Python 3.9.7
* Libraries:
  - Pandas
  - Numpy
  - Matplotlib (pyplot)
  - SciPy (stats)

* Development tools: 
  - Jupyter Notebook 6.4.6
  - Visual Code 1.62.3; just to edit README.md file.


## Analysis
![PyBer Summary by City type](/Analysis/SummaryData.png)

* Urban cities produce the higher revenues (***62%***), but the average fare per ride and driver are the worst due to the high number of rides and drivers within this city type. Clearly Urban cities are the most lucrative for PyBer, while are the less lucrative for their drivers.

![PyBer Percents Fare per City Type](/Analysis/Fig5.png)


* The average number of rides in the Rural cities is about 4 and 3.5 time lower than in the Urban and Suburban cities.

![PyBer Rides per City Type](/Analysis/Fig2.png)

* The average fare for rides in the Rural cities is about $11 and $5 more per ride than the Urban and Suburban cities.

![PyBer Rides Fare data](/Analysis/Fig3.png)

* Despite the fare differences between the city types, all of them tend to move in a similar pattern.

![PyBer Fare by City Type plot](/Analysis/PyBer_fare_summary.png)

## Summary
1. January appears to be the slower month in the year, so a promotion during this time offering a lower fare might increase the number of rides.
2. It is evident that the number of rides per driver are low within the Urban cities, affecting the driver's fare per ride. Again, a promotion in fare price could increase the number of rides.
3. The fact that there are more drivers than rides, I would dig further but now checking all cities within the Urban areas to see how drivers and rides per city are distributed, results could help drivers withing the Urban cities to relocate their efforts.
4. Other factor that could be affecting our numbers could be that there are many drivers registered within the Urban cities but not working, PyBer should look at this as well. Data for drivers not provided.