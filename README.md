# python-api-challenge
Use APIs to find ideal vacation destinations.

# Instructions/Premise

## Part 1: WeatherPy

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

## Part 2: VacationPy

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

# Modules

matplotlib.pyplot

pandas

numpy

requests

time

scipy.stats

pprint

citipy

hvplot.pandas

## API KEYS

A personal api_keys.py document is needed with following variables declared.

geoapify_key = “YOUR API KEY” (available at https://www.geoapify.com/)

weather_api_key = “YOUR API KEY” (available at https://openweathermap.org/)

# Summary

These Jupyter Notebooks generates random integers to create a list of cities across the globe in order to pull in their weather information from the OpenWeather API. Using the temperatures, humidity, cloudiness and wind speed, we chart the values against the latitude of each city in seek of a relationship between a city’s distance from the equator and expected weather patterns.

Once this is done, we filter the list of city’s to ideal weather forecasts for a vacation – in my case, a max temperature greater than 20 C and less than 27 C, with a humidity lower than 65%. We then use GeoApify’s API to seek a hotel within 10 kilometres, return the hotel’s information and map the potential vacation destinations.

# Citations

https://stackoverflow.com/questions/16327055/how-to-add-an-empty-column-to-a-dataframe

Adding a column for 'Hotel Name' in VacationPy was returning a warning. I found this solution for the column addition instead of concatenation.