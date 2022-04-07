# NYC-CitiBike-Bike-Share
Tableau and Pandas

## Overview:

The Purpose of this project was to gain familiarity with Tableau, a data vizualization software. This required that I learn how to import, style, and portray data accurately via the Tableau platform. I then created worksheets, dashboards, and a story to visualize key data from a New York Citi Bike dataset.  The data set consisted of aproximately 2.34 million rows of data, including multiple columns, such as: Bike Id, User info, start and stop locations, and bike usage.  The data visualizations were then used by a friend, who is interested in starting a similar company in Des Moines, Iowa. A link to NYC CitiBike Challenge story on my Tableau Public page can be found [here](https://public.tableau.com/app/profile/bart.black/viz/NYCCitiBikeChallengeDUDataAnalyticsBootcamp/Story1
).

I used Jupyter Notebooks and pandas to process the large data file.  Processing included the following steps:

1) Create a DataFrame for the 201908-citibike-tripdata data
2) Check the datatypes of the columns
3) Convert the 'tripduration' column to datetime datatype
4) Verify the the datatype of my new column ("Trip Duration")
5) Export the Dataframe as a new CSV file without the index

The updated CSV data file was then loaded into Tableau and the following vizualizations were created, which were then used to create dashboards and a story:
* Checkout times for all users
* Checkout times by Gender
* Trips by Weekday
* Trips by Gender (weekday per hour)
* Trips by Gender and User type (by weekday usage)
* August Peak hours
* Start and End location

The graphs above included multi-plot line graphs, heat maps, horizontal bar graph, and maps with pop-up info and markers.


## Results:

The following visualizations were created using the above data.

<br><br>![This is an image](https://github.com/bartblack13/NYC-CitiBike-Bike-Share/blob/main/Resources/Checkout%20times.png)<br>**Figure 1 - Bikes are rented for a maximum of 5hrs, regardless of Gender, with about 3,000 bikes being rented for aproximately 5hrs. Males rent more bikes than females, and unknown, totalling ~2,100 bikes for around 5hrs; ~750 bikes for around 6hrs; and ~60 bikes, between 4-6hrs, respectively.**

<br><br>![This is an image](https://github.com/bartblack13/NYC-CitiBike-Bike-Share/blob/main/Resources/Usage%20by%20User%20type.png)<br>**Figure 2 - Thursday, between 5-6pm is the most busy time for bike rentals, with aproximately 44-45K bike rentals, almost double any time block on Saturday between 10am and 6pm. Evenings are popular for all days, except Sunday and Wednesday.  Again, Males users (specifically those on subscription plans) comprise the majority of this usage and follow the same patterns mentioned above. Subscribers use the bikes more than non-subscribers, suggesting the bikes are used heavily by commuters.**

<br><br>![This is an image](https://github.com/bartblack13/NYC-CitiBike-Bike-Share/blob/main/Resources/August%20Peak%20times.png)<br>**Figure 3 - Peak usage for the month of August is between 5-6pm, with combined monthly usage at ~440K rentals for that time window.**

<br><br>![This is an image](https://github.com/bartblack13/NYC-CitiBike-Bike-Share/blob/main/Resources/start%20stop%20locations.png)<br>**Figure 4 - Start and End locations, where color and size of circular maker indicate volume of rentals.  Start and end locations are extremely similar.  The most popular spot (Dark red), located in the center of the map is across the street from Grand Central Terminal, 2 blocks east of the NY Public Library, and several blocks north east of the Empire States Building.**

## Summary:

After analyzing the data presented in the above visulaizations, it is clear that most bikes are rented from between 4-6 hours, with 5hours being the peak (see Figure 1).  Males are the majority users, accounting for ~72% of the usage.  Those with subscipription plans are noticeably higher than those without (see Figure 2 or page 2 in story).  This is surprising considering the density of usage within the downtown New York City/Manhattan area (see figure 4), which experiences high levels of tourism.  Given the congested traffic and expensive and limited parking, you would think that one-time users (non-subscribers) would use the bikes to tour the city and the famous attractions.  But the data argues that commuters use the bikes the most.  This is confirmed in Figure 2 and 3.  Usage is the most high in the early morning and in the evenings (around 5-6pm), which correlates with end of the work day.  Usage during the evening of weekdays exceeds Saturday and Sunday usage.  The rental location with the highest use is located near Grand Central Terminal, again, a key point for commuters using public transportation.

In order to succeed in implementing a similar bike-sharing company in Des Moines, it is recommended to locate the bike rental stations along the main commuter routes in the downtown area, near main train/subway stations.  The company should target males and should offer subscription plans, especially since Des Moines, is not nearly as well known for tourism as is New York City.
