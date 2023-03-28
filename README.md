# Ford GoBike System Data Exploration
## by Emmanuel Okodogbe


## Dataset

> There are 183412 goBike data in the dataset and it has 16 features(duration_sec, start_time, end_time, start_station_id, start_station_latitude, start_station_longitude, start_station_name, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). I added some new columns for `start_time_day`, `start_time_hour`, `start_time_month_name` as they were needed to establish relationship between the user category, duration of trip and the time.

## Summary of Findings

> In the exploration, I found out that most ride trips were on Thursdays and Tuesday while Saturday and Sunday have the least number of trips. I also found that Ford GoBike system had more subscribers than customers which could have been the reason subscribers had more rides. With respect to gender, female gender had longer trips while compared with the male gender.


## Key Insights for Presentation

> For this presentation, I focus on the date data of the rides. How many rides were done in a day and week. I further went ahead to introduce categorical data such as user_type and the member_gender to ascertain which category of the system users performed more rides. I used the boxplot plots to show the relationship between user_type and their age. Also, how this influnced the distance of a trip. I ensured I use different plot types, fullu detailed and well labelled and different color palettes for each quality variable to make sure there is no ambiguity. 
