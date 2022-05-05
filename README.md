# Surfs_up

## Overview of the analysis:

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. 
In Deliverable1 and 2, the temperature data is extracted by two seperate queries, one for June and the other being December.

Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Results attached.


## Results:

`June Summary Statistics:`

![June_temp_summary.png](https://github.com/klkanchi/surfs_up/blob/main/output/June_temp_summary.png)

`December Summary Statistics:`

![Dec_temp_summary.png](https://github.com/klkanchi/surfs_up/blob/main/output/Dec_temp_summary.png)


1. Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.

2. The maximum temperatures of 85 (June) and 83 (December) are also similar.

3. The minimum temperature of 64 in June  and  56 in December show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.


## Summary:

  Overall the weather in December and June are very similar, although December has a wider range of results, with its high being close to June's but the low's  are way below June minimum temperature. If we are able to gain more data for the area we can run even more additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
