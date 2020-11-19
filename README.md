# What's the weather like

![Screenshot](/Instructions/Screenshots/World.jpg "Screenshot")

## Purpose Part 1 - WeatherPy
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.  Utilize citipy Python library, the OpenWeatherMap API, and a little but of fun to create a representative model of weather across world cities.

## Process
Utilizing Python, Matplotlib, Pandas and several other libraries I was able to clean the data and perform the following analysis: 

First create a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Second create and run linear regression on each relationship and separate them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less then 0 degress latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Results and Data Observations (Condensed)
![Screenshot](/Instructions/Screenshots/Fig1a.JPG "Screenshot")
![Screenshot](/Instructions/Screenshots/Fig1.jpg "Screenshot")

![Screenshot](/Instructions/Screenshots/Fig3a.JPG "Screenshot")
![Screenshot](/Instructions/Screenshots/Fig3.jpg "Screenshot")

### Regression Analysis (Northern vs Southern)
![Screenshot](/Instructions/Screenshots/NReg.jpg "Screenshot")
![Screenshot](/Instructions/Screenshots/SReg.jpg "Screenshot")


## Purpose Part 2 - VacationPy

Using jupyter-gmaps and Google Places API with our previously cleaned weather data from Part 1 to plan a future vacation

## Process
Utilizing Google Places API, Jupyter Lab, Python and the Python library to create a heatmap that displays humidity for every city from part 1.  The data will be narrowed down to ideal weather conditions (i.e. wind speed less then 10mph, min temp 70 but no higher than 80, zero cloudiness etc).  Hotels will be plotted on the heatmap with each pin containing the Hotel Name, City and Country.

## Results and Observations (Condensed)

### North American Heatmap Showing Desirable Vacation Locations
![Screenshot](/Instructions/Screenshots/NAHeatMap.jpg "Screenshot")

### World Heatmap
![Screenshot](/Instructions/Screenshots/hotel_map.jpg "Screenshot")




