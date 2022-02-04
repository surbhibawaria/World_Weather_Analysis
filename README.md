# World Weather Analysis

## Overview of the Analysis

### Purpose

PlanMyTrip is a top travel technology comapny that specializes in internet related services in the hotel and lodging industry. Jack is the head of analysis for the user interface team. The purpose of this analysis is to help Jack collect and present data for customers via the search page, which they will then filter based on thier preferred travel criteria in order to find their ideal hotel anywhere.

### Analysis

To perform this task, Jupiter notebook and the city PI module is used to get the cities for 2000 random latitudes and longitudes. Then requests are performed on the open weather map API and retrieve the chase on weather data. From these cities, the weather data is added to a Panda's data frame. The purpose of this data is to help the team predict the best time of year for people to plan their vacation. The weather data is used to choose the best cities for a vacation based on certain weather criteria. And then map these cities using jupyter G maps and the Google places API.

Later, a few changes are made to take the app to the next level. Weather description is added to the retrieved weather data. Then input statements are used to filter the data for weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, four cities are selected to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route is created between the four cities as well as a marker layer map.

#### Travel Route

<img width="419" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/95826875/152583611-b38a00ac-afbe-4b0f-90b0-5664b667bf2d.png">

#### Marker Layer Map

<img width="747" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/95826875/152583652-769a62e6-5c63-4198-961f-0e11fbbd81ed.png">
