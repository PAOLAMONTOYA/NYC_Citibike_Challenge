# CitiBike NYC Bikesharing

## Project Overview
We are tasked with analyzing the Citibike NYC data for the month of August and put together a "proof of concept" business proposal for the Des Moines, Iowa area.  

We seek to create a trip analysis that will help key stakeholders decide on the investment.

The proposal is powered by Tableau to answer questions using data.

Following are questions we provide visual answers to:
*  How long bikes are checked out for all riders and genders.
*  How many trips are taken by the hour for each day of the week, for all riders and genders.
*  A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.




## Resources
- Data Source: https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip
- Software: Jupyter Notebook, Tableau Public

### Link to Tableau Story
[Link to dashboard](https://public.tableau.com/shared/6TWMMM5DK?:display_count=y&:origin=viz_share_link)


## Results
### Subscriber vs Customer

![customers](https://github.com/ashley-green1/bikesharing/blob/main/images/customers.png)

*  Citibike achieved an 81.06% Subscriber rate for the month of August in NYC.  


### Bike Transactions Grouped by Trip Duration 
![Average_Trip_Duration](https://github.com/ashley-green1/bikesharing/blob/main/images/avg_trip_duration.png)

*  The 0-59 minute Trip Duration group represents 99.3% of transactions.


### Bike Transactions by Gender, Grouped by Trip Duration

![Average_Trip_Duration_Gender](https://github.com/ashley-green1/bikesharing/blob/main/images/trip_duration_by_gender.png)

*  The 0-59 is most attractive to the male audience (orange), followed by the female (blue) and lastly unknown (red). 

*  The 5 minute duration is most popular, while duration times even out amongst all genders around the 50 minute mark. 


### Trips by Weekday

![Weekday_Trips](https://github.com/ashley-green1/bikesharing/blob/main/images/trips_by_weekday.png)

The service is very appealing to those who want a hassle free way to travel to work.

The largest demand for the bikeshare service corresponds with the "rush hour" work commute:
*  6AM-10AM Mon - Fri
*  4PM-8PM Mon-Fri
*  Thursday is the busiest weekday

While weekday demand is largest, weekends are in demand as well:
*  Saturday 8AM-8PM
*  Sunday 9AM-8PM


### Trips by Weekday by Gender

![trips_by_weekday_by_gender](https://github.com/ashley-green1/bikesharing/blob/main/images/trips_by_gender_weekday.png)

The data is filtered to the hours with most demand.    
*  While males use the service more heavily than females, the demand trend is pretty similar. 
*  Unknown genders primarily use the service on weekends. Indicative of travelers who aren't interested in providing demographic information. 

### User Trips Gender by Weekday

![user_trips_gender_weekday](https://github.com/ashley-green1/bikesharing/blob/main/images/user_gender_weekday.png)

Male Subscribers are the largest group of service users, followed by female subscribers and lastly the Unknown customers.

The largest demand for subscribers Monday through Friday, with Thursday being the busiest day.


### Bike Utilization

![bike_utilization](https://github.com/ashley-green1/bikesharing/blob/main/images/bike_utilization.png)

Bike maintenance and repairs is a cost to the service that must be managed well.  The circle chart highlights the utilization rate for each bike.

Dark Green to green-yellow represents low utiliztion to average utilization, respectively.

Dark Yellow to red represents above average to high utilization, respectively. 
This category should be maintenanced and repaired in the near future.  


## Summary

With the data, we were able to answer all of the questions regarding proof of concept.  We identified peak demand service hours, busiest days and also performed a deep dive into the users to get a feel for the services appeal.  

While the data is insightful, more information about Des Moines, Iowa is needed to determine if the service will appeal to potential users there.  NYC is a very busy and expensive city, where the bikeshare service may not only save users money, but also time commuting.  Des Moines is affordable and may also be less congested.  I would compare work commute congestion between NYC and Des Moines and create a comparison vizual similar to the "Trips by Weekday by Gender," but with "Traffic by Weekday by City."  Then I'd go further into Des Moines traffic to confirm the work commute congestion.

Age is a factor in the services appeal to users and comparing the age of residents in each city would be insightful as well.

In conclusion, while I can't suggest the service is a good fit for Iowa, the "proof of concept" is there.  With the right team, I'm sure we can easily identify cities that are a match. As well as, secure the data necessary to perform the Des Moines specific details. 
