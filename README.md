# NYC-Traffic-Accidents

## Introduction
In this project, I analyzed Motor vehicle collisions reported by the New York City Police Department from January 2021 to April 2023. Each record represents an individual collision, including the date, time, and location of the accident (borough, zip code, street name, latitude/longitude), vehicles and victims involved, and contributing factors.

Data source: <a href="https://maven-datasets.s3.amazonaws.com/NYC+Traffic+Accidents/NYC_Collisions.zip">NYC_Traffic_Accidents</a>




### Business Questions

1. Compare the % of total accidents by month. Do you notice any seasonal patterns?

2. Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?

3. On which particular street were the most accidents reported? What does that represent as a % of all reported accidents?

4. What was the most common contributing factor for the accidents reported? What about for fatal accidents specifically?

## Data Exploration and Cleaning

I explored and cleaned the NYC Traffic Accidents data using SQL Server. I chose this tool because of the volume of the data and the ease of writing queries. The queries used in the exploration and cleaning of the data can be found <a href="https://github.com/GloriaOlaleye/NYC-Traffic-Accidents/blob/main/NYC%20Data%20Cleaning">here.</a>

## Observations
There were 238421 rows in the dataset. All of the rows are disctinct. On further exploration, 7197 rows of data are without borough: these rows were removed during cleaning. The null values returned for the cross street column were irrelevant to the goal of this analysis.
22324 rows of data have neither longitude nor latitude. These were also removed during data cleaning.

1287 rows of data without contibuting factors were also removed from the dataset.
Duplicate rows were also checked and removed. After cleaning, 214798 rows of clean data was remaining.

## Analyze and Share
The data was loaded and tranformed further in Microsoft Power BI before visualizing with the same tool.
After analysis, the following insights were observed from the visualized data and they could be used in making decisions that would reduced road traffic accident in all the Boroughs in New York City.
