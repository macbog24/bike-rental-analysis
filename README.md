# bike-rental-analysis
1.	Code environment
a.	Python 3.7 via Jupyter Notebooks was used to create this solution.
Haversine formula inspiration: https://gist.github.com/rochacbruno/2883505

2.	Data exploration
a)	The data was found on the Divvy Bikes website: https://www.divvybikes.com/system-data
b)	Once the quarterly trips data frames are concatenated, station data and coordinates are merged to each row, and distance and speed are calculated and added in as columns, there are 3,829,003 rows and 18 columns.  The boxplot below shows the summary statistics for  trip duration by user type after rides less than 2 minutes or greater than 6 hours are removed. The next graph shows the distribution of rides by trip duration in seconds. Almost all rides are under 5,000 seconds or 83.33 minutes. The bar chart shows that most of our riders are subscribers, followed by customers, with only a handful of dependent riders. The scatterplot shows the geographical lay out of the stations most frequently used- the stations on “the loop” or near Navy Pier are in downtown Chicago and near touristy areas, so they are most popular. The border on the right is Lake Chicago, so there are no stations there, but there is heavy usage from the stations in the east, riders seem to enjoy riding near the lake.
