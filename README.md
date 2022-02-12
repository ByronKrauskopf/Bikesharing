# NYC CitiBike Bikesharing Analysis

## Overview of the Analysis

The purpose of this analysis is to determine who the primary user groups of the NYC CitiBike service are. It will also idenitfy what user groups are under-represented. This will allow us to ensure that the service is robust enough to support the continued use of the primary groups, while providing insights for expansion and targeted marketing to the smaller user groups. This analysis will focus on the following user details:
  - User type: Subscriber vs Customer
  - Gender
  - Age
  - Location

The analysis can be access directly at the following link:
[Tableau Story](https://public.tableau.com/app/profile/byron.krauskopf/viz/NYCCitiBikeChallenge_16440017516090/NYCCitiBikeStory?publish=yes)

## Results

### User Types
Subscribers make up the largest portion of users at 81%. Men make up 65.28% of users, more than double that of women at 25.1%.

![User Types](/images/user_types.png)


### Checkout Times for Users
The vast majority of trips are short duration trips of 30 minutes or less. 

![Checkout Times for Users](/images/checkout_times_for_users.png)

### Checkout times by Gender
Men tend to take longer trips then women.

![Checkout times by Gender](/images/checkout_times_by_gender.png)

### Average Trip Duration by Age
There is a slight negative correlation between the age and the average length of a trip meaning that younger users tend to ride longer. There is however an anomalous datapoint at age 50 that bears further investigation to see if it is a true value or a data error. 

![Average Trip Duration by Age](/images/average_trip_duration_by_age.png)

### Trips by Weekday per Hour
The heaviest usage falls between 7-10am and 5-6pm Monaday through Friday which corresponds with morning and evening rush hours.  

![Trips by Weekday per Hour](/images/trips_by_weekday_per_hour.png)

### Trips by Gender (Weekday per Hour)
The breakdown by hour and gender confirms the previous findings that men are the highest users and the the heaviset use times correspond with rush hours.

![Trips by Gender (Weekday per Hour)](/images/trips_by_gender_weekday_per_hour.png)

### User Trips by Gender by Weekday
Customer usage is largely uniform across the days of the week with slightly higher usage on weekends. Subscriber usage is heaviest on weekdays. 

![User Trips by Gender by Weekday](/images/user_trips_by_gender_by_weekday.png)

### Top Starting Locations
The highest number of starting locations are clustered in downtown and midtown Manhattan with some smaller useage in the nearest edges of the outer burroughs. Since most users are subscribers it is likely that this concentration indicates where the majority of users live and or work.

![Top Starting Locations](/images/top_starting_locations.png)

### Top Ending Locations
The highest number of ending locatoins are in the same areas as the starting locations indicating that the majority of trips are of short distance. This is consistant with the short average use times identified earlier. 

![Top Ending Locations](/images/top_ending_locations.png)

## Summary 

- additional vizs
  - User type by gender
  - Start location by user type
  - End location by user type
