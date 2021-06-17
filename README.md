# World_Weather_Analysis
WeatherPy with Python API's

## Overview
Travel and tourism offer individuals a glimpse of the world. Weather conditions influence travel behavior and impact overall travel experience. The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

### Resources Utilized to Complete Analysis
* **CSV Files:** 
[Weather_Database.csv](https://github.com/EJones621/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv), 
[WeatherPy_vacation.csv]( https://github.com/EJones621/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)
* **Jupyter Notebook Files:**: 
[Weather_Database.ipynb](https://github.com/EJones621/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), 
[Vacation_Search.ipynb](https://github.com/EJones621/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb),
[Vacation_Itinerary.ipynb]( https://github.com/EJones621/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)

* **Python**: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

## Weather Database
A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities. 

The following data was retrieved from the API call: 
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current Weather description 
