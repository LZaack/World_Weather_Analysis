# World Weather Analysis
## Overview

In the first place, Jack asked me to develop an application to provide real suggestions for his client’s ideal hotels, so, I followed the next plan:

  **1** Collect and analyze weather data across cities worldwide.

  **2** Use the data to recommend ideal hotels based on clients' weather preferences.

  **3** Create a Pandas DataFrame with the world's unique cities and their weather data in real-time. This process will entail collecting, analyzing, and visualizing the data.

After delivering my analysis, Jack asked me to add weather description to the weather data already retrieved in order the testers could: 

  **(i)** Input statements to filter the data for their data preferences;

  **(ii)** Choose 4 cities to create a travel itinerary; and

  **(iii)** Create a travel route between the cities.

## Results

To achieve the goals asked, I applied these steps:

`(i)` I generated a set of 2,000 random latitudes and longitudes, retrieved the nearest cities, and performed an API call with the Open Weather Map, to get the current weather description for each city, as it is shown in the next image:


![city_data_df](/Weather_Database/city_data_df.png)


`(ii)` Then, I used input statements to retrieve customer weather preferences to identify potential travel destinations and nearby hotels, as it can be seen in the last column of the following table:


![clean_hotel_df](/Vacation_Search/clean_hotel_df.png)


`(iii)` Finally, I created a travel itinerary showing the route between the four cities selected by the testers and made a pop-up marker layer for each city. 


![WeatherPy_travel_map](/Vacation_Itinerary/WeatherPy_travel_map.png)



![WeatherPy_travel_map_markers](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

