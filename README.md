# Transjakarta Passenger Mobility 

As a final project for Data Analysis Skill Accelerator Program at Purwadhika Digital Technology School I analysed and engineered the Transjakarta public transport data using Python. Then visualised trends and passenger mobility insights in a [Tableau dashboard](https://public.tableau.com/app/profile/snurjihan/viz/Transjakarta_17116901286380/TransjakartaPassengerMobility)

## Overview
The Transjakarta dataset consists of information of individual passengers movement commuting with the public transportation Transjakarta, with routes within Jakarta and trans-Jabodetabek regions throughout April 2023. Details of passenger movements were analysed through travel duration and length, stops name (tap in and tap out), corridor name and time.

 <img width="1280" height="789" alt="image" src="https://github.com/user-attachments/assets/3964cd11-5981-4d93-9f2b-cbf064bfece5" />

### The following statements were analysed:
1. Number of passengers, daily, weekly and overview of the month
2. Days of the week with tje highest and lowest number of passengers
3. Passenger demographics.
4. Amount spent (IDR) per journey.
5. Number of stops and travel duration
6. Which corridor(s) has the highest number of passengers?
7. Which stop(s) has the highest number of passengers that go though (tap in and tap out)?
8. Which area in Jakarta do passengers get on and get off the most?
 
### The following questions were explored:
1. Is there a correlation between the number of stops and travel duration?
2. Does the number of stops determine the travel duration?
3. When is the busiest and least busiest time?

## Transjakarta Metadata
* transID: Unique transaction id for every transaction
* payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
* payCardBank: Customers card bank issuer name
* payCardName: Customers name attached to the card.
* payCardSex: Customers gender attached to the card.
* payCardBirthDate: Customers birth year
* corridorID: Corridor ID / Route ID as key for route grouping.
* corridorName: Corridor Name / Route Name contains Start and Finish for each route.
* direction: Direction of the route (0 = Forward, 1 = Back).
* tapInStops: Tap in (start) stops ID for identifying stops name
* tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
* tapInStopsLat: Latitude of Tap In Stops
* tapInStopsLon: Longitude of Tap In Stops
* stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
* tapInTime: Time of tap in. Date and time
* tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
* tapOutStopsName: Name of the destination bus stop/ where customers tap out.
* tapOutStopsLat: Latitude of the destination stop.
* tapOutStopsLon: Longitude of the destination stop
* stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc, related to direction.
* tapOutTime: Time of tap out
* payAmount: Amount paid, includes free and paid travel.
