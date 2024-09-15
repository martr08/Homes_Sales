# Homes_Sales
Module 22 Challenge

In this module you will find a google colab worksheet about home sales. Using pyspark in the cloud to pull data from a website. The data pulled was a csv with the home sales information. The csv provided number of beds and baths to sqft and pricing. Using this csv, I was able to create:
1. A temporary view of the dataframe
2. Rewrite the schema to change the struct type
3. Filter and calculate averages for certain criteria
4. Cache and uncache the temporary table
5. Partition the data
6. Check time it takes to run a query


In conclusion, I was able to compare the time start and end of a query of the partition data versus the cache table. When I ran it, the cache table was the quickest at 0.6 seconds. Compared to the partition data that took 1.2 seconds. This may be due to the way the data was split to process the data. However, keep in mind that a cache table may not as effective with large datasets. Partition data however, does work with big data, even if it takes a longer to process the information!

