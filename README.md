# **Written report for the PyBer analysis**


## **Overview of the analysis**

This report aims to analyze the data differs by city type and how those differences can be used by decision-makers at PyBer. It uses Pandas and Matplotlib to create the summary DataFrame of the ride-sharing data by city type. Multiple-line graph is showns below to display the total weekly fares for each city type.


## **Results**

*1. PyBer summary DataFrame*
      -  This DataFrame displays the total number of rides and drivers, the sum fares for each city type, the average fare per ride and average fare per driver for each city type. We can see that the city type of "urban" has the highest of total rides (1,625) and the highest total fares($39,854.38). Even though the "urban' type has the highest total rides and fares, its "average fare per ride" and "average fare per driver" are lower than the "rural" and the "suburban" types.
      
The DataFrame of PyBer summary as the following image shown:
      ![This is an image](https://github.com/ruimin1231/PyBer_with_Matplotlib/blob/main/pyber_summary_df.png)

      
*2. Total Fares by City Type*
            -  This chart is a multiple-line graph that shows the total fares for each week by city type. The trends of the "suburban" and the "rural" types are gentler than "urban". The trends of the three cities have the almost parallel change from Feb to Mar. The trend of the "urban" displays its most fluctuated part from March to April. 
      
The data of the total fares by city type as the following image shown:
      ![This is an image](https://github.com/ruimin1231/PyBer_with_Matplotlib/blob/main/Pyber_fare_summary.png)



## **Summary**

Based on the information collected and the analysis, PyBer executives could hire fewer drivers in urban areas. Although these areas usually have the largest population and the greatest theoretical demand, the profitability of a single driver is significantly lower than that of less populated areas. Similarly, ride surcharges in urban areas can be introduced to increase the average fare per ride. The combination of these two adjustments may bring greater profitability to pyber and drivers in urban areas, but at the cost of firing some urban drivers. Finally, pyber executives should seek to take advantage of time periods with high predictive demand. For example, if the previously mentioned peak in February is accurately predicted, the rate can be increased to maximize revenue. Adopting a forward-looking approach to pricing their rides may lead to revenue growth for individual drivers and pyber as a company.



