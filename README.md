# NYC Citibike August 2019 Analysis

## Overview
### This analysis aimed to answer some simple questions about the behavior of Citibike customers during one of the peak usage months in 2019. We looked at what hours of the day saw the most bike usage, and also broke down this metric by gender and weekday. We also looked at the top starting locations and ending locations of trips on the island of Manhatten.

## Results
### Gender Breakdown
![gender_breakdown](/Resources/gender_breakdown.png)

This pie chart shows the gender of the customer for every ride in in August 2019. As can be seen the majority of riders are Male.

### Start Times
![start times](/Resources/start_times.png)

This chart demonstrates the number of rides according to starting time of day as well as weekday. The darker color indicates more rides. Most rides seem to begin during weekdays and at the usual commute times of 8 am and 6 pm. This suggests a large proportion of Citi Bike riders are using the bikes for commuting purposes. This could help inform where to focus future bike starting areas in new city expansions.

### Start Times by Gender
![Start times by gender](/Resources/gender_start_times.png)

This chart is similar to the above, except the data has been further parsed to account for the gender of each rider. Here we see a similar conclusion to the gender breakdown, which is that more Citi Bike riders identify as male than female by a significant margin. Additionally, we can see that there is a very similar concentration of rides around commute times for female riders as well as male. 

### Usertype Start Times
![Usertpe Start Times](/Resources/usertype_start_times.png)

This chart now breaksdown what days riders are using the bikes the most by gender as well as usertype. Here we see that the majority of our male and female riders are subscribers. However, it appears most of the unknown are one time customers. I would assume this is because we are not collecting gender data as part of the sign up and pay process of a one time use.

### Trip Durating by Gender
![Gender Trip Duration](/Resources/gender_trip_duration.png)

This chart plots the trip duration of all rides by gender. We see that virtually all trips are under 60 minutes and that the curves for both male and female peak at 5-6 minutes. Keeping in mind we know most of those users are subscribers. The unknown gender curve is virtually all one time customers and we see a flatter curve with a similar number of trips ranging up to 30 minutes. We can conclude our one-time users are taking longer trips.

### Top Start/Stop Locations
![Top Start Locations](/Resources/start_location.png)

This heat map shows all the start locations in NYC, and the size/color of the circles represent how many trips start from that location.

![Top Stop Locations](/Resources/end_location.png)

While this heat map shows the top trip ending locations. The combination of these two maps can help confirm the earlier conclusions that most of our subscribers are riding during the commuting hours of 8 am and 6 pm. We can use these maps to see where exactly people are commuting from and where they are commuting too, i.e. where the jobs are located of people who use Citi Bike. This can help inform good starting locations for bikes in future cities of expansion.

## Summary

We can conclude the following from this data:
  1. The majority of riders are subscribers.
  2. These riders are mostly using the bikes to commute to and from work on weekdays.
  3. There are almost 3 times as many male riders as female.
  4. There is little difference in the start times, weekdays of use, and trip durations between genders. The data is largely the same.

The dig deeper into this analysis I would recommend improving the starting and stopping location heat maps to include gender. Both of these heat maps would have to be seaparated by gender. It would be important to include the unknown gender data since these are all one-time users and do demonstrate slightly different trip duration and weekday behavior than the subscriber data. 
