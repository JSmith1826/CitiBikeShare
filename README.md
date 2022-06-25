# CitiBike Analysis and Visualization

## Overview
The purpose of this project was to visualize data from the CitiBike bike sharing program in New York City. In this analysis we take data for the month of August 2019. We will explore the makeup of the customer base, peak hours of use, the duration of the trips taken and the most popular locations.

The visualizations have been published on Tableau Public and can be accessed [HERE](https://public.tableau.com/app/profile/justin.smith2295/viz/CitiBikeVisualizations_16559565991170/CitiBikeAugust2019?publish=yes)


## Visualizations
![hourly breakdown](/images/hourly_breakdown.png)

This plot shows the overall usage of the service. The darker the shade of blue the more bikes checked out in that hour. 
We can see from this the peak times on weekdays are from 7 to 9 am and 5 to 7 pm. This is likely because customers are commuting to work.
On weekends there is not as defined of a peak. Bikes are utilized from 10 am to 6 pm at a pretty consistent rate


git 
![gender breakdown by hour](/images/gender_breakdown.png)

Here the same information is presented with the genders separated. There is a separate column for men and woman for each day of the week. It shows that the peak usage periods do not very much between the genders.



![customer activity by hour](/images/customer_activity.png)

In this plot we have added another factor to the hourly breakdown. Here we can filter based on whether a ride was taken by a subscriber who has paid a monthly fee and a customer who just purchases one ride at a time.



![over all trip duration](/images/trip_duration.png)

This line graph shows the trip duration in minutes for all rides taken during the month. We can see that most customers use the bikes for just 5 minutes at a time



![duration by gender](/images/duration_gender.png)

Her the trip duration is broken down by gender. We can see that men make up the majority of the customer base. Men are almost three times as likely to get on one of the bikes. It is interesting to note that the distribution of the length of rides for men and woman is very similar.



![start station](/images/start_station.png)

This visualization plots the starting location of each trip on a map of New York City. With this plot it is easy to see the most popular locations and where to make sure to have more inventory on hand. The majority of the bike utilization is in Lower Manhattan. The plot is interactive so the client can drill down to the street level.



![end station](/images/end_station.png)

This plot compliments the previous one in that it shows the ending location of trips. Because of what we have already showed, that the vast majority of trips are short, under 10 minutes it tracks that the ending locations would be rather close to the check out location with the highest concentration in lower Manhattan.



## Summary
These visualizations serve as a good jumping off point to analyses the success of the CitiBike Share program and extrapolate whether the same model can be implemented in other locations. 

I think that a map plot of bike usage verses population density would be very valuable. It is my assumption that high usage areas also correlate to very densely populated areas.

I would also like to compare data month over month. We can assume that August is one of the highest usage months because of the warm summer weather. I am interest to see how much of a drop off occurs when the weather isn't ideal. This could be accomplished by comparing data from the summer months to the other seasons. 

We could also look into how weather affects usage on a micro level. Weather conditions for each day could be used to see how rain, excessive heat, ect affects the usage of the service.









