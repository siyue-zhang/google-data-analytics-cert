# Cyclistic Bike-share Analysis

![divvy](http://chi.streetsblog.org/wp-content/uploads/sites/4/2020/07/Divvy-Meet-The-Ebike_7.jpg)

## Scenario

As a data analyst in the company, I'm working with the director of marketing who believes the company’s future success depends on maximizing the number of annual memberships. My team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, the team will design a new marketing strategy to convert casual riders into annual members.

## Goal

How do annual members and casual riders use Cyclistic bikes differently?

## Dataset

12 months trip record data from Dec 2020 to Nov 2021. The trip record consists of ride ID, ride types, starting datetime, ending datetime, starting station, ending station, member types. The csv files have been concatenated into one dataframe. Data cleaning process was carried out to eliminate trips with zero or negative time duration. Duplicated records weren't found. Geographical information is incomplete to great extent, which was not used for analysis.

After cleaning, there are 5,478,022 valid trip records, where the longest trip lasts 38 days. 

## Tools

Python numpy, pandas, matplotlib, seaborn

## Analysis summary

Among 5.5 million trips, the annual membership customer takes up 55% while the casual customer takes up the rest 45%. Casual riders tends to take longer trips than member riders, arounds two times of duration in average. Provided with mile charge information, the cost saving by subscribing memership can be estimated for the long trip riders.

![p1](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/member_casual.png)

Classic bikes were mostly used by member riders and casual riders, which took up 66% and 51% respectively. Almost none of member riders chose the docked bike while the 13% of casual riders used the docked bike. 

![p2](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/ride_type.png)

The largest amount of trips took below 10 minutes for member rider. The amounts of trip with less than 10 minutes and between 10 and 20 minutes were equally high for casual rider. Long trips above 30 minutes were much more popular for casual rider. 

![p3](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/duration.png)

There were high demand of cycling service from June to September for both member rider and casual rider. The demand of casual rider decreased more rapidly than that of member rider. The membership conversion campeign could be carried out during the peak season when riders have more frequent need of bikes. 

![p4](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/monthly.png)

![p5](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/weekday.png)

![p6](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/weekday_duration.png)
