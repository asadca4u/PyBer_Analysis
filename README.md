# PyBer Analysis

### Overview of the analysis:
- The CEO of PyBer ride sharing has tasked us wtih performing an analysis of the ride sharing data from 2019.
- PyBer operates in three different types of localities; urban, suburban and rural.
- This analysis will break down the total amount of rides given, drivers avaliable and fares exchanged for each of the three types of localities.
- That will aid in analyzing the costs associated with rides and drivers on a per capita basis in each of the three types of localities. 
- Finally, a line graph charting the data from January to April 2019 will be created, depicting the fluctuations in total fares exchanging hands on a weekly basis in each of the three types of localities. 
- The purpose of this analysis is to determine interventions that may be undertaken to reduce the costs associated with operating ride sharing in each of the three types of localities, ensuring the greatest possible profitability. 


### Results: describe the differences in ride-sharing data among the different city types.

![Summary Dataframe](https://github.com/asadca4u/PyBer_Analysis/blob/master/analysis/Rideshare%20summary%20df.png)
###### (Figure 1: Rideshare Summary Dataframe)

1. Total Rides
  - The total amount of rides taken in each locality differs as a function of population density, ranging from the lowest in rural areas, to highest in urban areas. 
  - There were 1625 total rides taken in urban areas in 2019, this was to be expected relative to the other two areas, which had 625 in suburban areas and just 125 in rural areas, due to the high population density in urban areas. 
2. Total Drivers
  - Similarly to the total rides, the total amount of drivers avaliable in urban areas, realative to the other two areas, was greater as a function of population density.
  - However, when comparing the total amount of drivers avaliable and the total amount of rides taken in each type of area, there were more drivers in urban areas than actual rides taken, meaning that each driver is averaging less than one ride per year, as opposed to rural and suburban areas where there are less drivers than rides. 
    - while taking into account the probable amount of drivers who registered in the urban areas and never actually completed a ride, there is still a strikingly low amount of rides completed relative to avaliable drivers, especially in urban areas, but to a lesser degree in rural and suburban areas. 
3. Total Fares
  - the total amount of fares, as a sum of all the fares collected during all the rides taken in a given area during 2019, is expectedly the greatest for urban areas, and the lowest for rural areas. 
4. Average Fare per Rider
  - The average fare paid per rider is a good indicator of the duration and distance of the average ride in each type of region. 
  - Urban areas have the lowest fare per ride, since they are densely populated and generally have relevant destinations situated closer together. 
  - Rural ares have the highest fare per ride, since they are sparsely populated and generally have destinations much further apart. 
5. Average Fare per Driver
  - The average fare per driver is a similar indicator of the duration and distance of the average ride, however the trend is even more pronounced.
  - The average urban driver makes over 3 times less per ride than the average rural driver. 
    - This is significant, as the incentive to go out and drive is limited in urban areas, since the fare is limited. 

![Total Fare by City Type (Jan - April 2019)](https://github.com/asadca4u/PyBer_Analysis/blob/master/analysis/PyBer_fare_summary.png)
###### (Figure 2: Total Fare by City Type, Jan-Apr 2019)

6. Total Fare by City Type
  - The total fare by city type was sectioned off into bins that each represent a week between Jan 1st, 2019 to April 30th, 2019. 
  - These bins contain the sum total of fares that exchanged hands during the week, for each of the three types of localities. 
  - Urban areas, with the greatest overall ridership, had the greatest cumulative fares exchanged during any given week, despite having the lowest average cost to the rider per trip. 
  - Rural areas, with the lowest overall ridership, had the lowest fares exchanged during any given week, despite having the highest average cost to the rider per trip. 
  - Suburban areas can be found in the middle of the rural and urban areas, owing to their moderate cost per trip as well as moderate ridership relative to the other two. 

### Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
1. Urban Areas:
  - Urban areas in 2019 had more drivers avaliable than rides taken, with the average driver giving out 0.68 rides for the year, which is just $11.27 of income when considering the average fare received by drivers in urban areas during 2019. 
    - There is limited incentive to go out and complete a ride in urban areas as the demand is limited.
  - However, urban areas have massive potential for increased ridership, with high population densities, limited distances between destinations, and limited car ownership in the area. 
  - The major competition in the urban centres are taxi services and public transportation, both of which are established modes of transport for urban dwellers, yet have key drawbacks that can be exploited for PyBer's benefit. 
    - Public transport, such as busses and subways, while cost effective, are not personalized to the user's experience. The origin, destination and departure time cannot be customized, but are rather on a fixed schedule, and the vehicle must be shared with potentially dozens of others. 
    - Taxi services by and large rely on older vehicles and payment methods, offering limited integration with smart phones, and limited access to individual ride data.
 - PyBer must situate itself as the cheaper and more efficient alternative to taxi services, while avoiding making the concessions of public transportation, increasing the demand of rides that are taken in urban areas with promotions until ridership is recurrant. 
    - This further incentivizes drivers to get out there and complete rides, making this a sustainable option for alternate income. 
    
2. Suburban Areas:
  - Suburban areas present their own set of challenges, although taxi services and public transport have limited use in such areas, car ownership rates are much higher in suburban areas than urban areas. 
    - The issue becomes convincing people to avoid using their own cars, and to use a ridesharing service instead
    - Owning a car is fairly expensive when considering costs associated with maintainence, insurance, fuel as well as the initial purchase price and any financing to go along with it. However, the average cost to the rider becomes prohibitively high if a ride sharing service is seriously considered as an alternative to owning a car.
      - the cost of the average ride in a suburban area is $30.97, which when taken as a daily expense for individuals that commute to and from work, would cost over $16,000 per year, when considering 260 working days in a year. This is on top of all the other every day trips taken by the average suburban dweller makes the cost prohibitively high. 
  - I would recomend finding ways in which one might demonstratively lower the cost per ride for the average suburban dweller, so that those on the edge of deciding between owning a vehicle and making use of ridesharing, might opt for the latter. It would be very difficult to convince those who already own a vehicle to adopt a regular use of ride sharing services, since they have already sunk a prohibitively large amount of captial into owning and maintaing a vehicle, and would not be so easily enticed into abandoning it and taking on a different regular cost. 
  
  
3. Rural Areas:
  - These are areas with extremely low population densities and large distances between destinations. As a result, these have very low growth potential for ridership and PyBer should be wary of sinking resources into these areas. 
