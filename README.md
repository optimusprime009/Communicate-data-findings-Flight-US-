# Communicate-data-findings

# US Flights of 2008
### by (himanshu)


## Dataset
> The dataset reports flights in the United States, including carriers, arrival and departure delays from 1987 to 2008. Actually, the plan was to gather & analyze data for three years (2006, 2007 & 2008). However it is time consuming to treat the report due to the detaset size which is (21,604,865) observations. Therefore, the report will gather & analyze flights of 2008 which is (7,009,728) observations by resolve the following questions:-
> - what are the best airports/states in terms of delayed and cancelled flighes?
> - what are the best airlines in terms of delayed and cancelled flighes?
> - what are the best flights in terms of delayed and cancelled flighes?  

[Dateset Source](http://stat-computing.org/dataexpo/2009/the-data.html)



## Summary of Findings
> - The rate of cancelled flights is high in Pierre Regional Airport, Pueblo Memorial Airport & Tupelo Regional Airport.
> - The rate of delayed departures is distributed in the whole US.
> - The rate of delayed arrivals is high in Pueblo Memorial Airport.


## Key Insights for Presentation
> AM Flights (day flights) have more cancelled flights than PM flights, while PM flights have more delayed flights than AM flights.


## Prerequisite
- Installing jupyter-gmaps: `conda install -c conda-forge gmaps`.
- creating an API key in Google [instructions](https://console.developers.google.com/flows/enableapi?apiid=maps_backend,geocoding_backend,directions_backend,distance_matrix_backend,elevation_backend&keyType=CLIENT_SIDE&reusekey=true).
