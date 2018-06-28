## WeatherPy

Here, we are given the task to datamine, prepare and analyze and at the same time create visualization using matplotlib of weather data of 500+ cities across the world of varying distance from the equator. 

 To accomplish this, we need:
 1. [simple Python library](https://pypi.python.org/pypi/citipy)
 2. [OpenWeatherMap API](https://openweathermap.org/api)
 3. Use the Matplotlib and Seaborn libraries
 
Our objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Our final notebook must:

* Must have selected **at least** 500 randomlyunique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls. 
* Include a print log of each city as it's being processed with the city number, city name, and requested URL.
* Save both a CSV of all data retrieved and png images for each scatter plot.
