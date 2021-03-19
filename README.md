# World_Weather_Analysis

# Background
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data I’ve already retrieved in this module. Then, I'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, I will create a travel route between the four cities as well as a marker layer map.

# Deliverable 1: Retrieve Weather Data

I generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data I gathered in this module, I used my API skills to retrieve the current weather description for each city. Then, I created a new DataFrame containing the updated weather data.


# Deliverable 2: Create a Customer Travel Destinations Map

I used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. From there, I showed the destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation_map](Vacation_Search/WeatherPy_vacation_map.png)<br><br>


# Deliverable 3: Create a Travel Itinerary Map

I used the Google Directions API and created a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, I created a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_Travel_Map](Vacation_Itinerary/WeatherPy_Travel_Map.png)<br><br>
![WeatherPy_Travel_Map_Markers](Vacation_Itinerary/WeatherPy_Travel_Map_Markers.png)<br><br>
