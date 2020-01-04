# Elevating Weather Data

## Objective

Gather weather data for cities in the world to elevate differences in humidity, cloudiness, windspeed, and temperature due to location latitudes.

## Purpose

Use [Open Weather Map API](http://api.openweathermap.org/data/2.5/weather) to gather city weather data information from around the world based on generating 1500 random numbers between -90 and 90 for latitude and -180 and 180 for longitude.  From the generated latitude and longitude numbers use the [citipy](https://github.com/wingchen/citipy) to find the nearest city.  Using weather data create graphs for each city based on latitude comparing
- humidity 
- cloudiness
- windspeed
- temperatures

## Technologies Used

- Python
- Jupyter Notebook

## Modules Used

- Pandas
- Numpy
- Requests
- Time
- Random
- Seaborn
- Datetime
- Config
- Citipy

# Graphs

- **Humidity**
<img src="https://github.com/ktung1189/WeatherPy/blob/master/Images/Humidity.png" alt='humidity'>

- **Cloudiness**
<img src="https://github.com/ktung1189/WeatherPy/blob/master/Images/Cloudiness.png", alt='cloudiness'>

- **Windspeed**
<img src="https://github.com/ktung1189/WeatherPy/blob/master/Images/WindSpeed.png" alt='windspeed'>

- **Temperature**
<img src="https://github.com/ktung1189/WeatherPy/blob/master/Images/Temperature.png" alt='temperature'>

## Running Program

An API will be needed from http://api.openweathermap.org/data/2.5/weather to be able to run the Jupyter Notebook.