# PlanMyTrip App <br/>
## Background <br/>
In this remote working world where the stress of work and school is overwhelming, we need a break to destress our minds. 
Traveling is one good way to take your mind off stressful things. 
And a scheduled vacation according to your weather preference can give you something to look forward to.
<b> Plan My Trip </b> can help you choose your travel destination according to your weather preference.<br/>
## Tools used in this project </br>
- Python 3
- Jupyter Notebook
- NumPy
- OpenWeatherMap API
- Google Maps Direction API
## What Is An Application Programming Interface?</br>
![](https://github.com/ramyasnl/Plan_My_Trip/blob/main/Deliverable1/REST_API.png)

## What We Are Creating<br/>

## Deliverable 1: Retrieving Weather Data<br/>
1.In this project we have generated a set of 2,000 random latitudes and longitudes,retrieve the nearest city, and perform an API call with the OpenWeatherMap. 
(https://openweathermap.org/api)<br/> 
2.In addition to the city weather data gathered, we have
used API to retrieve the current weather description for each city. <br/>
Then, created a new DataFrame containing the updated weather data.<br/>
Exported the DataFrame as a CSV file, and saved it as WeatherPyDatabase.csv<br/>
## Images<br/>
![DataFrame of Cities](https://github.com/ramyasnl/World_weather_analysis_challenge/blob/main/Deliverable1/allcitiesdataframe.png)<br/>

## Deliverable 2: Create a Customer Travel Destinations Map<br/>
1.Used input statements to retrieve customer weather preferences.<br/> 
2.Then used those preferences to identify potential travel destinations and nearby hotels. <br/>
3.Showed those destinations on a marker layer map with pop-up markers using google API.<br/>
4.Google API https://maps.googleapis.com/maps/api/place/nearbysearch/json.<br/>
## Images<br/>
![All Cities Marked](https://github.com/ramyasnl/World_weather_analysis_challenge/blob/main/Deliverable2/allcities2.png)<br/>

## Deliverable 3: Create a Travel Itinerary Map<br/>
1.From the vacation search map, choose four cities that a customer might want to visit. 
They should be close together and in the same country.<br/>
2.We have to refine our search with different weather criteria to get cities that 
are close together.<br/>
3.Created a directions layer map using the Google API, variables from previous steps 
where the starting and ending city are the same, 
the waypoints are the three other cities, and the "travel_mode" we used is "driving"<br/>
4.Finally, a marker layer map with a pop-up marker for the cities on the itinerary is created, 
and it is uploaded as WeatherPy_travel_map_markers.png <br/>
## Images<br/>
![Route Map Connecting All the Travel Destinations ](https://github.com/ramyasnl/World_weather_analysis_challenge/blob/main/Deliverable3/WeatherPy_travel_map.png)<br/>
![Added Weather Description To The Route](https://github.com/ramyasnl/World_weather_analysis_challenge/blob/main/Deliverable3/WeatherPy_travel_map_markers.png.png) <br/>


### Note for the reader <br/>
We worked in anaconda prompt python 3 environment <br/>
Before going into jupyternotebook , "conda install numpy" should be done ,dont forget to follow the instructions in googleapi.txt  <br/>
Every API needs a key , Here we have used allweather.com for generating the dataframe of cities ,we need the api key which is in config.py not added to GitHub .<br/>
For Deliverable 2 ,3 we use googleApi to create the maps and we need to enable Directions API in google api to create the Deliverable 3,<br/>


