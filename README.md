# Seattle Crime Analysis

Chekc the link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1055051710907192/1749074612195708/842309477568637/latest.html

Motivation: I live in Seattle area. Seattle is plagued by “soaring crime” and homelessness problem according to the media. I want to analyze Seattle's historical crime data to get insights on how to control crimes in Seattle.  

Steps:

1.  Collected the data from Seattle government open data website, and the data contain over 500,000 crime records from 1964 to 2019. The features included in the dataset include the crime occurred date and time, crime category, and the location of the crime, etc.

2. I cleaned the data by fixing the time column, converting datetypes, and limiting my analysis to crimes occurred bwetween 2008 and 2018 because of incomplete crime records before 2008 and in 2019.

3. I used Spark SQL to conduct online analytical processing. From data visualization, I discovered that top crime category in Seattle is car prowl; most dangerous districts is north district. The most dangerous time is from afternoon to midnight. The most dangerous neighborhoods are downtown commercial, north gate, and capitol hill.

4. Based on my analysis, I gave suggestions on  how to distribute the police to control the crime most effectively and gave advice to tourists to choose the safest travel time. 

In addition, I performed cluster analysis using K-means algorithm to explore the spatial distribution,  and applied time series model to predict car prowl per month in 2019, and validated with real data.
