# Surfs-Up analysis using SQLite

## Overview of the Surfs-Up Analysis

The purpose of this project was to expand upon the original climate analysis we gave to Mr. Avy and provide some additional insights into the temperature trends during the months of June and December specifically.  With this additional information Mr. Avy will be able to consider whether the ice cream and surf shop business will be sustainable throughout the entire year. To complete the project, I wrote two separate queries to retrieve the temperatures for the months of June and December and convert each query into a separate list for each month.  I then convert these lists to a DataFrame that would allow me to then capture the summary statistics for each month. 

## Surfs-Up Results

- The temperature in Hawaii appears to be relatively consistent based on results from June and December.  As expected, June is slightly warmer with an average temp. of 75 degrees compared to an average temp. of 71 degrees in December, but that is not a substantial change. 
- Despite the relative consistency of the average temperature, December certainly appears to be more volatile with a min of 53 degrees and a max of 83 degrees representing a difference of 28 degrees within the range, versus a min of 64 degrees and a max of 85 degrees in June which equates to a range of 21 degrees.
- There were also 183 fewer observations in December versus June which is interesting given that June has one less day in the month than December. 

## Surfs-Up Summary

Based on the summary statistics for temperature in June and December it appears that Oahu may be a great place to open the surf and ice cream shop, however there is some additional data that would be good to include.  One additional query that would provide useful information would be to pull the precipitation for these two months.  The months may be warm, but if they are rainy that could dramatically impact the number of people willing to surf or purchase ice cream.  This will undoubtedly impact Mr. Avy's decision since he already had one venture fold due to rainy weather.  I also think it would be beneficial to query the other 10 months throughout the year to determine if the temperature indeed is consistent. Given that June and December our 6 months apart, and since Hawaii is close to the equator it makes sense that the temperature would not change often, but it would still be a good idea to confirm that for Mr. Avy before he invests in the shop.  
