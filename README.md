# Analyzing Citibike Information

## Overview

### Purpose

This project's purpose is to look through Citibike information from August of 2019 and determine if there's any meaningful demographics in order to help influence the introduction of bike-sharing services to Des Moines. To do this, we need to take the various data we have, and find relationships between the more common demographics and time frames in order to produce legible charts detailing trends that could demonstrate how profitable the introduction of bike-sharing opportunities to Des Moines could potentially be.

## Results

### The Story
Before this report continues, the link to the analysis and source of all the images posted here can be found [here](https://public.tableau.com/views/CitibikeAnalysis_16205165166200/BikeDemographicStory).

The story posted there contains the following images. This section will be dedicated to going further into depth as to the significance of those charts.

### Line Graphs
![alt text](https://raw.githubusercontent.com/SirNancyTheNegative/Citibike_Analysis/main/Images/Citibike_Riders.png "")

This chart graphs the number of bike riders, grouped by the duration of their trips. In this case, it's fairly clear that most bike-share users spend less than an hour on bikes. While some riders use it more than that, they don't make up the lion's share of users. It also demonstrates that most users use a bike for less than 20 minutes.

![alt text](https://raw.githubusercontent.com/SirNancyTheNegative/Citibike_Analysis/main/Images/Citibike_Riders_By_Gender.png "")

This chart is a stepping stone from the previous one, as it separates the numbers of bike riders by gender (those who don't fall into one or the other, or who haven't input gender, are listed under "undecided"). From this we can glean that the majority of bike-share users are male, with female users forming less than a quarter of all users. It does show, however, that both the numbers for female and unknown riders decrease slower as the ride time increases, and while they don't become equal at any point in this, the ratio of male riders to other riders does decrease drastically in the process.

### Heatmaps
![alt text](https://raw.githubusercontent.com/SirNancyTheNegative/Citibike_Analysis/main/Images/Citibike_Riders_Heatmap.png "")

In this chart we separated the data by the hour started and by the day of the week each person stopped riding and produced a heatmap consisting of the number of riders at that time and day. As can be seen, the typical work week (i.e. Monday through Friday) has the most notable data points around both 8 AM and 5-6 PM, while Saturday and Sunday have more consistent dark points between 10 AM and 6 PM. 

![alt text](https://raw.githubusercontent.com/SirNancyTheNegative/Citibike_Analysis/main/Images/Citibike_RBG_Heatmap.png "")

This chart, much like the line graph of riders, is just the heatmap above separated by gender. Similarly as well, there are much fewer female users than male users, but there are no points where there are more female users. Additionally, even on the off hours of each day, there's a notable discrepancy between female riders and male riders, going so far as to show that the difference between weekday rides and weekend rides is larger for men than it is for women.

![alt text](https://raw.githubusercontent.com/SirNancyTheNegative/Citibike_Analysis/main/Images/Citibike_Subs_vs_Customers.png "")

This final chart details the breakdown introducing a new variable -- whether or not a customer is a subscriber. As can be seen, there are typically more subscribers than customers. The main exception is with those with "Unknown" gender, where instead there is a dearth of users on the subscriber side. Other than that, we can also glean that subscribers typically use the bikes on the weekdays, particularly on Thursdays, while non-subscribers use the bikes more on Saturdays and Sundays, and the majority of non-subscribers are also of unknown gender.

## Summary

### What Does This All Mean?
From the graphs, we can gather a number of facts. From the first chart, we learned that the majority of the rides were under twenty minutes long, and from the third we learned that the majority of them were done at specific times on weekdays, and over a broader range of times on weekends. This means we have two major categories of riders: Those commuting to and from work, and those using the bikes to get to places they want to be on the weekends.

The second graph demonstrates that most of the riders are male, while the fourth graph shows that men have a much higher weekday-weekend discrepancy in terms of riding than women, and the fifth shows that the majority of rides are done on the weekdays by male subscribers. From this we can determine that most of the rides are done by workers commuting to and from work during the week, with a large number of the subscribers still biking around during the weekends.

The third graph lets us know the breakdown of the riders by hour, and we still have the sides partially unaccounted for, while the fourth graph additionally lets us know the breakdowns of riders by hour and by gender, and the fifth graph lets us know the breakdown by day and by subscriber status. From these we can determine that the majority of users during the week are subscribers, and even during the weekend, subscribers still make a large portion of daily users, with a major influx of non-subscribers making use of the service all the same. However, the number of non-subscriber users whose genders we know isn't anywhere near how many whose genders are never specified. This is likely on account of the lack of commitment. Some people prefer that as little information as possible be gained about them, especially from absolute strangers. The discrepancy of non-subscriber gender ambiguity is easily explained away, then, and as a result, this small hiccup is solved.

### What Are We Still Missing?
While there is plenty we know from the charts we've built thus far, there is still much more we could do to help visualize the clientele. For one, we don't have any idea how the subscriber counts break down from day to day, and a simple first chart we could do is count the number of rides taken per actual day through the month from both subscribers and non-subscribers. This will give us an idea not only of how many new subscribers we might gain in a day, but also of how many new people are introduced to Citibike as well. Similarly, we could determine the age groups that use the bike-sharing services the most by creating bar graphs containing the number of rides taken by people with specific birth years, collated into ranges that make sense. This second one might have a bit more of an issue if we have data that's missing a birth year, but considering the data we have doesn't have this problem, it's potentially safe to say that other data we might have also won't have this problem.
