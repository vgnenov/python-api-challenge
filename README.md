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

