## Visual Analysis of Bike Ride Sharing App User Statistics
### This is a primarily visual analysis of subscribership and ride statistics for a bike sharing platform for in New York City. The analysis will explore through charts and maps how subscribers are biking based on gender and time. These insights will provide useful and universal user data points to help the platform expand to other cities by targeting their user recruitment marketing and providing access to bikes and services during peak hours and days.

## Results:
### Popular Checkout Times for Users

![Screen Shot 2022-09-21 at 9 08 55 PM](https://user-images.githubusercontent.com/107326987/191656724-a1b5c78d-d25f-422e-975d-bf96abe6adcb.png)

This line chart shows the duration of each trip as a continous value along the x axis (in minutes and hours) and the amount of trips taken for each trip duration length as the y value. The chart clearly shows that most trips are less than 30 minutes, peak trip count being at 140,000 rides that are around 5 minutes long

### Popular Checkout Times for Users by Gender

![Screen Shot 2022-09-21 at 9 09 15 PM](https://user-images.githubusercontent.com/107326987/191656732-6a97f881-8bd2-4cf9-941a-3c2ad3a88426.png)

This chart is a duplicate of the previous line chart showing the relationship between trip duration and ride count. Additionally in this line chart, the count is seperated out into rides by gender. We can see that for the peak trip duration (140,000 riders total at 5 minutes) 108,000 riders were male, 33,000 were female, and for 5,000 riders the gender was unkown or unreported. We can also see that popularity of trip duration is not gender dependent. Each line peaks at 5 minutes.

### Trip Count by Weekday per Hour

![Screen Shot 2022-09-21 at 9 09 29 PM](https://user-images.githubusercontent.com/107326987/191656775-2a788c32-8ed7-4dd1-8a97-351add481126.png)

This chart is a heat map showing the density of ride start times (as rows) and ride stop times (as columns) for each hour of each weekday. The color gradient shows the popularity of ride start and stop times by a progressively darker color. We can see that the darkest intersections have the highest incidence of start/stop times around 8am and 6pm on weekdays and mid-morning to mid-afternoon on Saturdays.

### Trip Count by Weekday per Hour by Gender

![Screen Shot 2022-09-21 at 9 10 09 PM](https://user-images.githubusercontent.com/107326987/191656787-2809bc2b-e445-4a0c-9e72-067482a0627b.png)

Above is a heat map of start and stop time incidences filtered by day of the week and hour of the day. Each heat map represents this data by gender. As a comparison we can see that Male riders comprise the majority of riders for the bike share application but that popular ride times are consistent across genders.

### User Trip Count by Gender by Weekday

![Screen Shot 2022-09-21 at 9 10 20 PM](https://user-images.githubusercontent.com/107326987/191656798-eb5afe9c-380d-487d-a0e1-04d7f7576fc2.png)

This heat map examines the makeup of the bike share application user base. We can see the heat density is  much great for subscriber users than for customer (non repeat users). The color density represents the count of bike rides. There is a strong correlation between hour and day for subscriber riders. For customer riders there is a much weaker relationship between day, time and ride count.

### Peak Ride Start Time August

![Screen Shot 2022-09-21 at 9 10 32 PM](https://user-images.githubusercontent.com/107326987/191656809-50408c76-b950-4dba-956b-0035ec2f8d17.png)

This bar chart shows the clearest relationship between the start time of each ride and the number of riders. We can see that the most popular time to start a ride is 5pm. This is an indicator to any bike share platform to have the maximum number of bikes availble for use during this time.

### Total User Base by Gender

![Screen Shot 2022-09-21 at 9 10 55 PM](https://user-images.githubusercontent.com/107326987/191656813-b6c04bae-00f6-41c6-bf65-5c6cf7192988.png)

We can deduce the makeup of the bike shar platform user by gender from our other charts. Here however we provide a definitive circle chart to elucidate the relational subscriber size for each gender. It is visually clear that a majority of subscribers are male (1.53 million, 72%), with female users comprising nearly 27% of user base at 588,000 total, and unkown gender making up about 1% of user base. 

## Summary Analysis:

Through this visual analysis we can extrapolate a hypothesis about peak ridership times and subscribership by gender assuming that these analysis outcomes are universal. From these outcomes we can make recommendations to the bike share insights team for how to market to and expand into new territories. Their target consumer is a male rider looking for long term subscribership. We can anticipate that peak use will be weekdays (Monday through Friday) 8am and 5pm. Most rides will last less than 6 minutes. More analysis can be conducted to provide specific insights. We recommend that further analysis be performed on the following two areas.

- Subscriber type (single use customer versus long term subscriber) by gender: help platform managers target new rider marketing.
- Geographical relational data between urban services hotspots (event venues, restaurant clusters, public transit hubs) and popular ride start and end locations: this information would help platform managers design geographical placement of bike pickup/drop off sites with access to technical services and lock up locations.

[link to dashboard](https://public.tableau.com/app/profile/ava.mikolavich/viz/NY_Citibike_Ridership_Analysis/Story1?publish=yes)
