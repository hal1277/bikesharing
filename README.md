# NYC Citibikes

## Overview

The purpose of this analysis was to better understand the NYC Citibikes program in order to make a proposal for a similar program in Des Moines, Iowa.  The data was cleansed using Jupyter Notebook and Pandas and then visualizations were created in Tableau.  

## Results

[link to dashboard](https://public.tableau.com/shared/PWY4HZG7R?:display_count=n&:origin=viz_share_link)

![Customers vs Subscribers](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Usertypes.png)

In the NYC Citibikes program more than 80% of users are subscribers compared to less than 20% of users that pay as they use without a subscription.  

![Number of Rides per Bike](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Bike_Usage.png)

There is widely varying usage of the bikes in the NTY Citibkes program with some bikes being very heavily used and some barely being used at all.  

![Duration of Rides](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Bike_Usage_Times.png)

Generally rides are lasting less than an hour with the majority being half and hour or less.  

![Rentals by Gender](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Usage_Times_by_Gender.png)

Males use the bike rentals much more frequently than females with a ration of 3 to 1.  

![Rentals by Time of Day](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Usage_by_day.png)

The majority of rentals occur during the rush hours of Monday to Friday, so from 7am to 9am and 5 pm to 7pm.  

![Rentals by Gender by Time of Day](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Usage_Time_by_Gender.png)

Even though males use the service much more frequently than females both genders use the bikes at similar times of day.  

![Rentals by Time of Day and Customer Type](https://github.com/hal1277/bikesharing/blob/29b64efd41ae47562a7afa7d6c81fc26cbf446be/Images/Usage_by_Gender_and_User_Type.png)

Some variation can be seen in the usage times between subscribers and non-subscribers.  Subscribers tend to use the bikes during the rush hours times Monday to Friday but non-subscribers have more usage on Saturday and Sunday than on the weekdays.  

## Summary

The analysis shows that the NYC Citibikes program has a loyal subscriber base and a smaller group of infrequent users.  Trips are usually occuring during peak rush hour times and are of short time duration.  Males use the bikes much more frequently than females.  Given these results some addiitional visualizations might be helpful to help decide the best way to set a program up in Des Moines.  It would be interesting to add weather data to the analysis to see if there are variations in usage between dry and rainy days and how weather compares between New York and Des Moines.  As well it would be helpul to dig further into map data to understand the most common starting and ending points (ie. where people live vs work) to determine the best locations for bikes.  In addition to this map data it would be useful to know what the bikes routes are between those locations (ie. are there designated bike paths/lanes).  This would then need to be looked at in Des Moines as well.  How safe a rider feels on the bike infrastructre, or lack thereof, would likely impact usage levels.  
