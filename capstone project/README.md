# Cyclistic Bike-share Analysis

![divvy](http://chi.streetsblog.org/wp-content/uploads/sites/4/2020/07/Divvy-Meet-The-Ebike_7.jpg)

## Scenario

As a data analyst in the company, I'm working with the director of marketing who believes the company’s future success depends on maximizing the number of annual memberships. My team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, the team will design a new marketing strategy to convert casual riders into annual members.

## Goal

How do annual members and casual riders use Cyclistic bikes differently?

## Dataset

12 months trip record data from Dec 2020 to Nov 2021. The trip record consists of ride ID, ride types, starting datetime, ending datetime, starting station, ending station, member types. The csv files have been concatenated into one dataframe. Data cleaning process was carried out to eliminate trips with zero or negative time duration. Duplicated records weren't found. Geographical information is incomplete to great extent, which was not used for analysis.

After cleaning, there are 5,478,022 valid trip records, where the longest trip lasts 38 days. 

## Analysis summary

![p1](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/member_casual.png)

![p2](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/ride_type.png)

![p3](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/duration.png)

![p4](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/monthly.png)

![p5](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/weekday.png)

![p6](https://github.com/siyue-zhang/google-data-analytics-cert/blob/master/capstone%20project/images/weekday_duration.png)
