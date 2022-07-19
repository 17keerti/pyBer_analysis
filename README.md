# PyBer Analysis

## Overview of the analysis

Purpose of the new analysis - Using Python and knowledge of Pandas, we created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type.

## Results

**Summary DataFrame**

Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, we calculated the total number of rides, total number of drivers, and the total fares for each city type. Then, calculated the average fare per ride and average fare per driver for each city type. Finally, we add this data to a new DataFrame, then formatted the columns.

![summary DataFrame ](Resources/Summary%20dataframe.png)

**Total weekly fares by city type**

Using Pandas and two new functions, pivot() andresample(), we created a multiple-line graph that shows the total fares for each week by city type.

![Total weekly fares by city type](analysis/PyBer_fare_summary.png)

## Summary

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
