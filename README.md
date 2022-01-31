# PyBer_Analysis

## Overview of the PyBer analysis: 
It's your second week as a data analyst at PyBer, a ride-sharing app company valued at $2.3 billion. You've just been assigned your first big project: analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type.


## Results: 
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types-


Here in PyBer analysis project I create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I create a multiple-line graph that shows the total weekly fares for each city type. The code I use to get the line charts  
[PyBer_Challenge](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

The line graph I got is as below

![PyBer-fare_lineg_raph](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

 
The csv data used here is [city_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/city_data.csv)
 & 
[ride_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/ride_data.csv)

First I create a PyBer summary table with all the data gathered from the merged dataframe
![PyBer_fare_summary_unformatter](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_unformatted.png)

I formatted the Pyber summary DataFrame to look like below: 

![PyBer_Summary_formatted](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_Summary_formatted.png)

Using Pandas skills and two new functions, pivot() and resample(), I created a multiple-line graph that shows the total fares for each week by city type.
The dataframe after using pivot functions look like below:

![pivot _dataframe](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/dataframe_pivot.png)

I create a new DataFrame by applying the resample() function and resample the data in weekly bins, then apply the sum() method to get the total fares for each week the dataframe look like below:

![resampled_dataframe](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/resampled_dataframe.png)

From the above line charts we can see that urban cities has the highest total fares among the city types and rural cities has the lowest total fares among the city types.


## Summary: 

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.

1. Decreasing fares in rural and suburban areas respectively could increase the total revenue in those areas as the income of riders are usually lower in those areas.
2. Giving some  weekly perks could influence people to use more of the ride share.
3. Making a monthly subscription with 10-15% discounts could make the riders in rural and suburban areas to use more ride share.

### Conclusion 
The line graphs made from the ride-sharing data by city types helps to understand the disparities in city types and help the business make dicisions accordingly.








