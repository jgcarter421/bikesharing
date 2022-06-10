# bikesharing

Click here to view the [NYC Citi Bike Analysis Story on Tableau](https://public.tableau.com/app/profile/joshua.carter8024/viz/NYCCitiBikeAnalysisStory_16548191904040/NYCCitiBikeAnalysis?publish=yes).

## Overview
The purpose of this project is to collect data and create a story to convince potential investors that a bike-sharing business in Des Moines, Iowa is a solid business proposal.  The given data set was a CSV (text) file of data collected from New York City's Citi-Bike program for the Month of August 2019.  August's weather in NYC create's a great time to get out and ride.  From the data set, I was able to create visualizations showing the length (in time) of bike rides, the gender breakdown of riders, the starting locations, and the lenth of bike rides.  I also had to use Pandas to transform the data's tripduration from an integer to a datetime object.  

## Results
### Starting Locations
<img width="977" alt="Screen Shot 2022-06-10 at 1 43 54 PM" src="https://user-images.githubusercontent.com/99417460/173132319-057d66e8-7cc5-4589-835f-8b5ad386b131.png">
This map shows the starting locations for Citi-Bike rides throughout Manhattan and the surrounding buroughs.  It is important to note that Manhattan is not only a global top tourist attraction, but it is also a bustling business district.  Lower Manhattan, where the highest number of starting locations, is where the business and tourist district concentrate.  Upper Manhattan and the surrounding buroughs are where the locals live and play.  While the business/tourist district has the majority of the starting locations, the residential areas have a good number of starting locations.

### Active Hours
<img width="983" alt="Screen Shot 2022-06-10 at 1 44 08 PM" src="https://user-images.githubusercontent.com/99417460/173132966-16b325ef-95a3-40f2-a8e1-d03958b96137.png">
This horizontal bar chart shows the active hours for start times of the Bike Sharing program.  The most used times are during the work commute hours, suggesting that the majority of riders are commuting to and from work.  The non-commute day time hours are still fairly active, which would be when the majority of the tourists would be out riding a bike.  From 2 a.m. to 4 a.m are the least popular hours, which would be a good time to service the bikes.

### Trip Duration
<img width="947" alt="Screen Shot 2022-06-10 at 2 08 00 PM" src="https://user-images.githubusercontent.com/99417460/173133852-54eee366-740c-4590-b5a9-eb41f5effb94.png">
This line graph shows that the majority of rides last a shorter amount of time.  The vast majority of rides last 20 minutes or less, and the most common ride length is five minutes.  Therefore, the majority of people riding the bikes are taking very short trips (i.e. work commuters).

### Trip Duration by Gender
<img width="950" alt="Screen Shot 2022-06-10 at 1 44 36 PM" src="https://user-images.githubusercontent.com/99417460/173134279-033588ae-2215-4832-b258-92a93fe1e7d6.png">
This line graph shows the exact same information of the Trip Duration Line graph, but is broken up by gender.  Males make up a majority of the riders, but both Males and Females keep the same shape of the line, indicating that they have the same riding patterns.  Both peak at the five minute ride mark, and drop significantly the longer the ride.

### Trips by Weekday Hour
<img width="980" alt="Screen Shot 2022-06-10 at 1 44 51 PM" src="https://user-images.githubusercontent.com/99417460/173134567-70601a9e-b170-484d-bc40-3d1889d8708b.png">
This heatmap shows the breakdown of bike rides by hour of the day, for each day of the week.  As you can see, the most popular times for bike rides are during the work commute hours, with Thursdays in the 5 p.m. and 6 p.m. hours being the most common time to ride a bike.  Weekends from 10 a.m. to 7 p.m. are still fairly popular times to ride a bike, which are typically tourists or locals out for a ride.

### Trips by Weekday Hour by Gender
<img width="974" alt="Screen Shot 2022-06-10 at 1 45 04 PM" src="https://user-images.githubusercontent.com/99417460/173135054-2dd2a274-9f41-4d2b-b865-931ad6292a16.png">
This heatmap shows the breakdown of rentals by hour of the day, for each day of the week, for each gender.  Again, while males make up the majority of bike rentals, both males and females follow the same trends.  The majority of rides are during the week work commute.

### Usertype
<img width="962" alt="Screen Shot 2022-06-10 at 1 45 13 PM" src="https://user-images.githubusercontent.com/99417460/173135314-413d9183-7090-4385-884a-80a023cbdc72.png">
This heatmap shows the breakdown of usertypes, by gender.  The vast majority of users are subscribers, indicating that they live in the city and use the bike-sharing service often.  The map also shows that males make up the majority of users, and Thursdays are the most popular day to ride.  

## Summary
Based off this analysis, the data suggests that the majority of users are locals commuting to and from work, not just tourists out on a stroll.  Most of the peak riding times are during work commute hours.  There were more males using the service rather than females, which could be useful to know for future marketing.  Another point to be made is that the majority of rides were shorter in length (by time); the majority of rides peaked at the five minute mark, and significantly decreased from there.  

For futer analysis, I would want to know the following:
* The gender make-up of NYC.
  * If NYC has more males than females, it could mean that the data here is skewed, and that the percentages of males and females patronizing the bike-sharing business are the same.
* I would also want to know the population density, broken up by neighborhoods.
  * This would be helpful to know what neighborhoods in Des Moines to place more bike-sharing stations, rather than equally spacing them throughout the city.  One neighborhood may use them, while others may not.  The farther out from the business center of the city, the less likely the people will use the bike-sharing service.

Prior to starting the bike-sharing service in Des Moines, I would also want to know how many businesses are in the city, where they are centrally located, and what the population density is.  Due to the majority of the rides in NYC being fairly short, I wouldn't want to start a bike-sharing service where everything is spread out.  I would also want to know how many apartment complexes and homes are within a five minute ride to the business center of the city.  




