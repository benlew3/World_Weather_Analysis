# World Weather Analysis

## Overview of Project:

We will be using Python, google maps API and pandas to perform analysis on various locations globally. We will be looking at their weather, ranging their temperatures and weather conditions for vacation purposes. 

### Purpose:

The purpose of this project is to utilize Python, Pandas and the GMAP API to find a range of minimum and maximum temperatures across the globe. We want to identify a range of temperatures that we like and where in the world we can go that fits the criteria. We use API, city geo locations to find hotels near those coordinates. 

## Analysis Results and Challenges:

### Analysis of Outcomes 
To get a general base for this project, we will be setting up 2000 randomly generated coordinates. We then will find what are the closest locations to these geolocation points. This comes back with 566 cities.

Based on the locations, we compiled a list based on temperatures ranging from 70-90°F.

#### Vacation Map
![](Weather_Database/WeatherPy_vacation_map.png)

From the vacation map, the island of Mauritius was chosen as the preferred travel destination.  Four cities where chosen to visit on vacation.  The Google Maps based driving route, map with pop-up markers for additional information, and map designating the four cities (with no additional pop-ups) were generated.

#### Mauritius Travel Itinerary
![](Vacation_Itinerary/WeatherPy_travel_df.png)

#### Mauritius Vacation Driving Route
![](Vacation_Itinerary/WeatherPy_travel_map.png)
    

#### Mauritius Vacation Map with Pop-up Markers
![](Vacation_Itinerary/WeatherPy_travel_map_markers.png)


#### Mauritius Vacation Map without Pop-up Markers
![](Vacation_Itinerary/WeatherPy_travel_map_markers_nopop.png)


### Challenges and Difficulties Encountered
During the vacation search, the findings were cleansed to remove any empty rows.  It was found that some destinations did not contain a country code and needed to be dropped from the results list.  In performing that activity, a Jupyter Notebook warning message was displayed even though the rows were successfully dropped (based on comparing total beginning and after row counts).  The analysis proceeded without refactoring the code that produced the warning message as another results cleansing activity would be performed that would further remove results (e.g. additional rows) that did not contain hotel references. This cleaning activity did not produce any warning messages so the analysis was completed without re-factoring code.
