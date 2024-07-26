# ME204 -2024 - Analyze of crimes in North America

North America suffer of a rising of violence this few decade :

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=s_NkLRb_Ldc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe  frameborder="0" style=" width: 100%; height: 110%;" src="figure/Repartition_of_crime_by_type.html"></iframe>




To answer the question is North America a dangerous place we are going to analyze the crime in two North American cities : Balitmore in USA and Vancouver in Canada:

This analyze will be based on data found on kaggle that show the criminality in each city since the start 2012 for Baltimore and 2003 for Vancouver.

# Baltimore :
Baltimore is a major city in the state of Maryland, United States. It is located on the eastern coast along the Chesapeake Bay. Known for its rich history, Baltimore is the largest city in Maryland and serves as an important seaport. The city is famous for its Inner Harbor, historic neighborhoods, and cultural landmarks such as the National Aquarium, Fort McHenry (where the Star-Spangled Banner was written), and its vibrant arts scene.
Population : 585,000 residents
Unemployment Rate : 7%
Median Household Income : $50,000
High school graduation rate : 70%

# Vancouver : 
Vancouver is a major city in the province of British Columbia, Canada. Located on the west coast, it is known for its stunning natural scenery, including mountains, forests, and the Pacific Ocean. Vancouver is one of Canada's most ethnically and linguistically diverse cities, with a strong emphasis on sustainability and quality of life. It is a significant center for film production, technology, and tourism.
Population : 662,000 residents 
Unemployment Rate : 4.5%
Median Household Income : $72,000
High school graduation rate : 91%

Let's start by seeing the repartition of crime by type :
![Title : Number of crime by type](./figure/Repartition_of_crime_by_type.html)

As we can see the theft is the most common crime nearly 50%. Then come the burglary, the larency the assult and the mischief. That five crime represent the majority of crime barely 90%. Hopefully the rape and the arson are rare.


Let's continue by analyze the number of crime in each city :

![Title : Number of crime by city](./figure/number_of_crime_by_city.html)

Based on this graph we can see that there is much more crime in Vancouver than in Baltimore but this is a bias because we do not have the same time range.

Let's then focus on the accuracy of crime with the time :

![Title : City crime counts by city overtime](./figure/city_crime_counts_by_city_overtime.html)

As we can see the crime is decreasing with time in Vancouver in the beggining and the stay kind of stable. For Baltimore me can see that it change cyclically with low accuracy and then high accuracy. Moreover, we can notice two peaks of crime. It may be due to a high number of complaints lodged due to a close of the police office or it can be accidents due to terrible weather.

We can now focus on the locality of the crime. As we have the position we can analyze where are the risky aera on both city.

Vancouver :
![Title : City crime counts by city overtime](./figure/map_Vancouver.html)

The dense cluster of crime indicators in Vancouver proper underscores the city's role as the epicenter of criminal activity in the region. This is typical for urban cores, which often experience higher crime rates due to population density, economic disparities, and more opportunities for certain types of crimes. 
The dominance of blue dots, representing theft, aligns with Vancouver's well-known struggle with property crime. This has been a persistent issue, often linked to drug addiction and homelessness in certain areas. 
The high concentration of various crime types in the northeast part of the dense cluster likely corresponds to the Downtown Eastside neighborhood. This area is notorious for its complex social issues, including poverty, drug use, and associated criminal activity
There's a noticeable decline in crime incidents as you move away from the city center towards suburban areas. This follows a common urban crime pattern where criminal activity decreases in less densely populated residential areas.
The western peninsula and False Creek area show a lower density of crime despite being central. This likely reflects the more affluent nature of these neighborhoods and possibly more effective policing or community prevention measures.
While less frequent than property crimes, violent crimes (homicides, assaults) appear scattered throughout the city rather than concentrated in one area. This suggests that violent crime is not confined to stereotypically "bad" neighborhoods. 
The markedly lower incidence of reported crimes in surrounding municipalities like West Vancouver and North Vancouver highlights the stark contrast in crime rates between the urban core and more affluent suburban areas.
There's a noticeable line of criminal activity along the waterfront areas, possibly indicating crimes related to port activities, tourism, or nightlife in these zones.



Baltimore :
![Title : City crime counts by city overtime](./figure/map_Vancouver.html)

The dense cluster of crime indicators in Baltimore City proper highlights its status as the epicenter of criminal activity in the region. This concentration is typical for urban cores, especially those facing significant socioeconomic challenges like Baltimore.
Unlike some cities where one type of crime dominates, Baltimore shows a mix of various crime types. The prevalence of blue (theft), orange (assault), and red (burglary) dots indicates a complex criminal environment with both property and violent crimes being significant issues.
The high visibility of purple dots (homicide) and orange dots (assault) underscores Baltimore's well-known struggles with violent crime. This aligns with the city's reputation for having one of the highest per capita murder rates in the United States.
The highest density of crimes appears to be in the central parts of Baltimore, likely corresponding to areas with higher poverty rates, abandoned properties, and drug-related activities.
There's a notable presence of criminal activity along the harbor area, which could be related to port activities, nightlife districts, or tourist areas that often attract certain types of crimes.
The surrounding areas like Towson, Pikesville, and Catonsville show significantly fewer crime incidents, highlighting the stark contrast between the urban core and suburban areas. This pattern reflects broader socioeconomic disparities in the region.
While less dense, there are notable crime occurrences stretching south towards Brooklyn Park and north towards Parkville, suggesting that crime issues are not entirely contained within the city limits.
The widespread presence of blue dots (theft) throughout the map indicates that property crime is a pervasive issue across different neighborhoods, not just confined to stereotypically "high-crime" areas.
Certain areas within the city show particularly high concentrations of multiple crime types, possibly indicating zones that require targeted intervention strategies.

# Conclusion

To conclude, even if this aeras seams riskies we have to remember that we look at a map of crime on a period of a decade all zone are not equally risky with time and a year split map could help us to identify with time where we sould not be. The crime is not more or less present that before it remains stable and cyclical and the main issue is theft. In my opinion it can be a good idea to renforce the houses security and if you want to be rich you can open a security business there.


