# Ford GoBike Readme file
## by Abdulelah Aljaloud


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This dataset explores trip data containing bike rides in February 2019. The dataset contains 16 columns before, and after some cleaning it became 25 columns, the 9 more columns came after wrangling that:
- removing rows that does not have gender value and station id
- changing start_time and end_time datatype to be datetime
- changing ids to string
- changing user_type, member_gender to category
- creating new column for age from 'member_birth_year'
- creating new columns for duration in minute, hour, day, week, month, from 'start_time' 
- creating new column for age groups  from 'age' 
> which then created these 9 columns: start_year, age, start_date, start_time_month, start_dayofweek, start_time_day, start_time_hour, duration_min and age_group. 


## Summary of Findings

> This exploration showed us two types of user: Subscriber, Customer. In the exploration, I found that Subscribers are immensely larger than Customers in total. but and customers spends more time in total, double the time of subscribers, even though that contomers count are immensely larger than subscribers but the deference in duration is just the double. and Customers bike-riding duration lasted longer than Subscribers in every day, most of customers are riding between 8-12 minutes, and most subscribers rode between 5-10 minutes. another thing i found is that Subscribers use bikes on weekdays more than on weekends which can tell us that most subscribers are using it for work.

> Another findings is in the age groups: In the exploration, I found that most of the members are around 24-40 years old, and peaks at 30, and the bike usage is dropping significantly as the person gets older in age. and most of the members are around 24-40 years old, and peaks at 30, 30-39 age group is the most consistently bike-riders in each day, and the bike usage is dropping significantly as the person gets older in age. also the majority of bikers are around 20-39, 20-29 group comes as second, and some days 20-29 group surpassed 30-39. finally, young riders have a longer trips in Friday.


> On the duration exploration I found that 28/2/2019 is the day with the most bike trips. and Thursday is the most common day to start, Sunday and Saturday are the least. Wednesday and Thursday bike rides lasted longer than rest of the days. On time of the day: 8:00AM and 5:00PM are the most common times.


## Key Insights for Presentation

- For the presentation, I focused on presenting the visuals that shows the differnce between the Customers and Subscribers bike trip count overall and count the bikers in each day of February, And focused on presenting the riding duration and the difference between Customers and Subscribers duration during weekdays, and the relationship between age and duration for the bikers.
- I use the bar to visualize bike trip count of Subscriber and Customer and it's difference, and used Facet for the riding duration for Customer and Subscriber, I also used pointplot to count of subscribers rides in February and to see the difference between Customer and Subscriber Bike-riding duration, and finally a heatmap of age vs duration in minutes to find observations by looking at high density in the heatmap.
- I added some small details to polish the presentation like adding titles in each plot in the slideshow, and a little more informations in the slides.