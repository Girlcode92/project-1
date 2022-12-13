Data Analysis:
Fatal Crashes in Chicago 2019 - Present 
 
The dataset used for our project today is from the Chicago Data Portal website. The data is pulled from the Vision Zero Chicago website. As stated in the description of the dataset, “Vision Zero is Chicago’s commitment to eliminating fatalities  and serious injuries from traffic crashes”.  Within this data set there is a list of designated fatal accidents as defined by the Fatal Crash Response Coordination Committee (FCRCC). For a death to be appended to the list, the death has to be within 30 days of an accident involving a motor vehicle within a public right of way. If the accident is attributed to a homicide, suicide or the person(s) was hit by a train or other similar vehicles of transportation it will not be listed. The same goes for expressway fatalities. Within our data, we are given individual accidents, report numbers, dates/times of the incident,  victim categories, location by longitude/ latitude, and street addresses spanning back to January 2019 to present. Upon cleaning and organizing our data we were able to group victims to get a count of who is being affected by these fatal crashes. We located the top 5 deadly streets in Chicago. As well as, the times of day and months that most fatal accidents occur. 
 
Variable
Description
Person_ID
A case number that can be used to link this data to other traffic crash datasets
RD_No
A case number that can be used to link this data to other traffic crash datasets
Crash_Date
Includes date (MM/DD/YYYY), and time (HH:MM:SS XM) of the fatal accident
Crash_Location
Provide a house number and street address of the incident 
Victim
Used to describe the person who died in the incident- grouped by: PEDESTRIAN, DRIVER, PASSENGER, MOTORCYCLIST, CYCLIST, PEDESTRIAN-PENDING, MOTORCYCLIST (MOPED)
Longitude
west of the standard meridian of a celestial object, expressed in degrees 
Latitude
a celestial object north or south of the celestial equator, expressed in degrees
Location
A point using longitude & latitude values

https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vision-Zero-Chicago-Traffic-Fatali/gzaz-isa6/data

 
Who is affected?
 
The graph above shows the affected population by the fatal accidents in the dataset. This is an accumulation of incidents (537 fatal crashes) spanning back to 2019 to the date the data had been pulled. 185 pedestrians have been hit and killed since 2019. The second largest group affected are drivers at 180. The Pedestrian-Pending category is a processing report at the time the CSV was exported for this dataset.

The graph above shows each fatality represented as an individual data point on 
a scatter plot that compares victim type versus the timestamp of the reported fatality. The timestamps are plotted on an axis that indicates every January and July of each year from the dataset; that is, 2019-2022. The trends indicated on this graph show differences both by time of the year and between years as well as by victim group. Weather conditions seem to be a key variable here.
We see consistent increases in fatalities during the beginnings of winter and summer, perhaps due to  inclement weather during the winter, or increased vehicle and foot traffic during the summer months. This is particularly true of pedestrians and drivers, most likely due to the year-round necessity of these transportation types. However, pedestrian fatalities show higher frequency in the summer months, likely due to the warmer weather being more conducive for walking outdoors. Cyclists and motorcyclists have a similar trend, as many will prefer not to travel via bicycle during the colder months. The passenger trends tend to follow that of the drivers with reduced frequency, as the passengers do not move independently of their drivers, but likely exist in less frequency; you can have a driver with no passengers, but not a passenger with no driver. 

 
Where are the fatal crashes taking place?

 
The map above plots every fatal accident location that has happened in Chicago since 2019 according to our dataset. The key on the side provides information on the color code for each victim category. With this information we can analyze areas that have clusters of fatal accident sites and the victim that is frequently affected in that area. 
During our research, we observed 3 areas with clustered victims. The S Stony Island merge to S Cornell near the Jackson Park Golf Course had a cluster of victims (Driver, Cyclist, Motorcyclist & Pedestrians have been killed near that merge). The S Pulaski and 5th Avenue intersection has a few clustered incidents. The W Madison Street stretch between N Kildare & S Pulaski has 3 pedestrian incidents too. 
 
 
 
This bar graph above displays the top 5 fatal streets of Chicago, where the most fatal accidents have occurred based on the street name. This information is based on the fatal accidents that have happened from 2019 to current in the city of Chicago. As we can see in the graph, S Ashland Ave is the most dangerous street according to this dataset with 17 fatalities. S Pulaski Rd comes in second with 12 fatalities, then 11 fatalities within S Cicero Ave, while S Western Ave & S Archer Ave both have 10 fatalities. Even though many would think that this is a small amount, it is reasonably high since not every street was accounted for, particularly for this graph. Also, the city has about 4,000 miles of streets that serve drivers, buses, cyclists and pedestrians, in addition to 1,900 miles of alleyways. In total it is 60 fatalities just for these 5 streets alone, which makes up to 11% of all fatalities from 2019 - Current.  
 
 

 
When are these fatal crashes happening?
 
 
The line graph displays the fatalities over four years, specifically 2019 to present it also includes monthly fatalities. First unfortunately this is incomplete data because we do not have the data for 2022 in October to december. With that being said this line graph tells us a lot of information. Something that I thought was very interesting is even during covid in 2020 we were still having a rise in fatalities during the summer months. Even more interesting you can see a return to normal when it comes to traffic fatalities through the pandemic. In 2019 it was a clear baseline on what previous years look like with that being said the next two years deaths skyrocket and in our current year we have returned to a sort of default. Some other clear factors when it comes to deaths is weather, during the winter months are clearly lower due to less traffic in the city. This is by all means no surprise, but it does show some interesting numbers. For example, November is clearly a bad month for Chicago deaths. Even during the coldest time of recording november 2019 it had little effect on the traffic deaths, which is interesting. It is clear that the pandemic had a serious increase in traffic when it came to the city, especially when the lockdowns were lifted. This is why we have such a skewed 2020 and 2021 July is clearly the worst month. The reason for that is July in Chicago is when events happen, concerts, airshows and other events take place that drive people to the city. Also this relates to the pie chart below because the night life in chicago in July is clearly peak for bars and clubs.
 
 
 
 
 
 
 
 
 
 
 

 
 
 

This graph shows the division of fatalities by time of day. Times were taken from the timestamp and divided as follows: Morning: 6 am - 12 pm, Afternoon: 12 pm - 6 pm, Night: 6 pm -12 am, Late: 12 am - 6 am. As a result, it has become apparent that the majority of fatalities occur at night, with late closely trailing behind. This may be due to reduced visibility at these timepoints, as well as other characteristics specific to this time.
 
 
 

In continued exploration of this trend, the fatalities have been divided both by time of day and victim type. The same trends as captured by the previous chart seem to be replicated among victim types, with higher fatality counts at the night and late time divisions. Despite differences in quantity, the distribution between victim types seems consistent across times as well. Fatalities are most common for pedestrians with the notable exception of late. Here, drivers have the most fatalities, most likely due to the reduced presence of pedestrians at this time and potential increase in speeding and reckless driving.
 
 
Conclusion of findings
	Ultimately from our dataset, our group has concluded that the individuals that were affected the most by fatal crashes were pedestrians and drivers, which occurred mostly in the Southern parts of Chicago. From this, it was determined that the top 5 streets where the most fatal accidents occurred were: S Ashland Ave, S Pulaski Rd, S Cicero Ave, S Western Ave, and S Archer Ave with a total of 60 fatal crashes occurring on these streets. In addition, we have found that the majority of crashes occurred at night, from 6 pm to 6 am, and that the frequency of crashes amongst all victim types increases in both early winter and summer months. With all these findings combined, there may be certain safety measures that the city can implement, especially concerning low visibility at night as well as inclement weather during the winter, or increased vehicle and foot traffic during the summer months. 
	This is a very general overhead look at fatal crashes in Chicago. Each case can be different and have different reasons as to why/how that person died. To dig into the causes of death to solve possible traffic infrastructure issues would require more time and a granular analysis of the required dataset(s).                                                               
 
 


