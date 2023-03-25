# (Data Exploration of GoFordBike-System)
## by (Emmanuel Olorunbogun)

## Dataset
Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data was downloaded through the link: https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv
> 
>This dataset contains about 183,412 rows and 16 columns and below are the descriptions for each column.
#### Column Description:
<br>**`duration_sec`**: contains the trip duration in seconds.
<br>**`start_time`** : the start time of the ride.
<br>**`end_time`** : the end time of ride.
<br>**`start_station_id`** : id to identify the station where the ride started.
<br>**`start_station_name`** : name of the start station.
<br>**`start_station_latitude`** : latitude of the start station.
<br>**`start_station_longitude`** : longitude of the start station.
<br>**`end_station_id`** : id to identify the station where the ride ended.
<br>**`end_station_name`** : name of the end station.
<br>**`end_station_latitude`** : latitude of the end station.
<br>**`end_station_longitude`** : longitude of the end station.
<br>**`bike_id`** : id to identify each bike.
<br>**`user_type`** : shows if the user has subscription or not.
<br>**`member_birth_year`** : year of birth of the user.
<br>**`member_gender`** : gender of the user.
<br>**`bike_share_for_all_trip`**

The wrangling of the dataset involved cleaning the dataset by changing the datatype format of some columns and the unwanted columns were removed from the dataset. Some new columns were added also, such as:
- **`Day_of_week`**: to store day of the week.
- **`duration_minutes`**: to store the duration in minutes.
- **`age`**: age of riders.
- **`time`**: hour of the day.

## Summary of Findings

<br>1. Riders in the age group of 25 - 40 had the highest number of trips taken.
<br>2. About 75% of the riders are Males.
<br>3. 90% of the riders are Subscribers.
<br>4. Most of the trips taken only lasted for about 5 - 12.5 minutes.
<br>5. Thursdays have the highest number of trips.
<br>6. Subscriber completes at least thrice the number of Customers rides daily.
<br>7. Weekends have lesser number of trips, therefore it records higher average ride time compared to weekdays.
<br>8. The average ride time for riders who shared bikes and those that didn't was almost the same.
<br>9. The average age of Female subcribers is 33.3 and for female customer is 32.7.
<br>10. The average age of male subscribers is 34.5 while for male customers is 33.9.
<br>11. The average age of subscribers of the other gender is 36 while for those that are customers is 34.9.


## Key Insights for Presentation
For the Explanatory phase, the focus is on the characteristics of riders and how they performed in duration of rides in respect to the different:
- **User types**
- **Gender**
- **Hours of the day** and
- **Days of the week**.

The key insights for the presentation were as follows:
<br>1. The Gender Proportion of Users in the GoFord Bike System.
<br>2. The proportion of riders by user type.
<br>3. Duration of an average trip.
<br>4. Daily usage of bikes by user type.
<br>5. Daily average ride time by the user type.
<br>6. Busiest hour of the day for riders.


```python

```
