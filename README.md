# SAN-ORD-Flights-Analysis-1997-2007

## This project is in progress and will be updated upon completion!

An analysis of delays and cancellations between San Diego International and Chicago O'Hare International airports between 1997 and 2007.

ChemCorp Inc. recently moved their headquarters from San Diego, CA to Chicago, IL. Although the headquarters moved, a significant number of high-level employees have remained in San Diego. ChemCorp holds quarterly meetings at their new headquarters in Chicago. Employees travelling to these meetings have been arriving late due to excessive delays and some have missed meetings altogether due to cancelled flights.

The goal of this project is to analyze ways for ChemCorp adjust quarterly meeting dates and book optimized employee flights to increase on-time meeting attendance by 5% by their next quarterly meeting.

To accomplish this the criteria for success is:
Reduce the average flight delay for employees travelling from SAN to ORD to under 5 mins.
Reduce the percentage of cancelled flights by 1%.

Some constraints are:
Departure and arrival airports must be located within 25 miles of San Diego and Chicago offices.
Meetings must be held quarterly
Flights must be direct – no layovers
Flights must be on weekdays

Key data sources are:
1997-2007 US flights dataset
Plane information by tailnumber dataset 
Airport code and location dataset
Airline code and name dataset

All data sources have been uploaded as tables in a SQLite database.


