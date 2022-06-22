# World Weather Analysis
## Overview
The purpose of this analysis is to look at different weather parameters around the globe. Travelers will use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of possible travel destinations, the travelers will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities and a marker layer map.

Three folders offer different levels of analysis:

### Weather Database
This analysis uses an Open Weather Map API to retrieve specific weather information from over 700 random cities. The data retrieved consisted of:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description (for example, clouds, fog, light rain, clear sky)

### Vacation Search
This analysis uses input statements to retrieve customer weather preferences, then uses those preferences to identify potential travel destinations and nearby hotels. Finally, we show those destinations on a marker layer map with pop-up markers.
![VacationSearchMap](https://github.com/msevillano89/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vaction Itinerary
This analysis uses the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, we show a map with a direction layer and a pop-up marker for each city on the itinerary.
#### Directions Map
![ItineraryMap](https://github.com/msevillano89/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

#### Pop-Up Marker Map
![ItineraryMarker](https://github.com/msevillano89/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
