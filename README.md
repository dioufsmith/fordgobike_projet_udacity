# FORDGOBIKE Data Exploration

### by Ibrahima Diogoye Diouf

## Dataset

The data consists of information regarding 183,412 rides made in a bike-sharing system covering the greater San Francisco Bay area . The dataset includes 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip').
Upon proper data cleaning, the dataset was reduced and feature-engineered into 12 columns with  the new columns being:
 
> day_of_week: to store week day number from start_time.
> start_hour: to store hour number from start_time.
> time_of_day: to store the time of the day from start_hour

> duration_min: to store the duration in minutes.

> distance :to store the distance 





## Summary of Findings


Based on the available information below are the observation we have :


> The day of the week that most trips are taken (Thursday) is NOT dependent on if a user is a subscriber or a customer. However, it was discovered that Subscribers mostly used bikes on workdays (Monday - Friday), while customers bikes usage was about the same for the whole week with a huge increment on Saturday and Sunday

Most of the rides are by the Subscribers.
Majority of the rides were taken on weekdays excluding weekends.



## Key Insights for Presentation

I focus on just  looking at the time of the day and the day of the week that most trips are taken

check if the results depend on if a user is a subscriber or a customer

The presentation showed that there indeed is a dependency of the average trip duration on if a user is a subscriber or a customer. On average, customers rides lasted longer than subscribers rides on every day of the week and time of the day


```python

```
