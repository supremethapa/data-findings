# US Flight Analysis
## by Arun Leo Prakash


## Dataset

> The data set has approx 7 million US flights entries including cancelled & delayed flight information for 2008. Supplement data plane, carrier, airport were merged to the flight data to provide some additional information about the flights. Data cleanup was performed on this data that involves removal of diverted flights, missing plane manufacturer details & outliers on Airtime. The data is downloaded programmatically from http://stat-computing.org/dataexpo/2009. 
Data wrangling operations performed during this analysis includes, 
1. Merging supplement data Airport, Carrier, Plane data. 
2. Long description carriers US Airways & American West Airlines were fixed. 
3. Manufacturers duplicate names were merged
4. column renaming for better naming conventions
5. New columns weekday, period were added
6. Unused columns were dropped 


## Summary of Findings

> During exploration on hourly analysis, the highest no of flights were found at 6 AM during weekdays, and during this time there are minimal delays, and 17 hours is identified as time where high number of delays are registered. Regards to delays and cancellations, winter seems to be the major cause during with notable high during december. Carriers Southwest, Skywest and US Airways are ranking with top 3 flight operations among which US Airways with lesser delays in ranking. Manufacturer Boeing flights are operated with 47% and with minimal delays, Bombardier manufactured flights had highest no of delays registered and further in depth could reveal the root cause, due to the limited scope for this analysis I have stopped my analysis on Manufacturers at this point. 
Carrier, Weather, NAS, Security & Late Aircraft Delay comparison plotting shared a similar graph across months with same level of increase and decrease on monthly report.


## Key Insights for Presentation

> For the presentation, The key aspects considered during presentation were Flights, Delays & Cancellations. Peak hours, top 10 Carriers. Manufacturer wide breakup graphs were included. The graphs were limited from exploration for short and clean presentation without compromosing the key aspects that I wanted to convey from the findings.