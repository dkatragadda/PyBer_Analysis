# PyBer_Analysis

## Overview of the PyBer Analysis
The purpose of this analysis was to use our skills with pandas and matplotlib to perform data operations on a dataset containing information about ride sharing in different cities along with data on the city type, fares and driver count. This exercise involved merging two datasets (city data and ride data) to determine the metrics by city type and the fares. After processing the data, the objective was to visualize the dataframe using charts by leveraging the matplotlib package. 

## Results

### Overall summary of dataset shared

![Total_info_by_city_type](https://github.com/dkatragadda/PyBer_Analysis/blob/main/analysis/Total_info_by_city_type.png)

Based on the table above, the data shows that the urban cities earn the highest fares followed by the suburban cities and then the rural cities. The driver count is also the highest in the urban cities followed by suburban cities and rural cities respectively and the same pattern is observed for total rides as well. The order is inversed when we look at metrics such as average fare per ride or average fare per driver where it is the highest in the rural cities and gradually reduces in the urban cities.

### Deliverable 2: Plotting data for a sample of the dataset Jan 2019 to Apr 2019

![Total_Fare_by_City_Type](https://github.com/dkatragadda/PyBer_Analysis/blob/main/analysis/Total_Fare_by_City_Type.png)

The line chart denotes the total fares by city type when plotted against the month. As can be seen, the fares in the urban cities supercedes the fares in suburban or rural cities. In the last month on the chart, April, the suburban fares seem to have increased while the fares in the urban and rural cities have dropped or remained flat. All the city types seem to have some volatility in the fares by week while observing the chart. 


## Summary

The three major recommendations to be proposed are:

1. Investigate causes for spike in fares in suburban cities in April 2019 while there is a decline in the urban and rural cities. There may be learnings or market conditions to adapt to accordingly depending on the city type.  
2. Investigate and replicate the demand from the last week of Feb 2019 if possible. The fares are peaking in all types of cities.  
3. Leverage the learnings from the urban cities to grow the suburban and rural markets as the average fare per ride and average fare per driver are higher in the rural and suburban markets. 
