# python-api-challenge

## Part 1: WeatherPy
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator using citipy Python library and the OpenWeatherMap API. Random geographic coordinates will be generated with their nearest city to each latitude and longitude combination to create the list of cities.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data from the cities list generated and create a series of scatter plots to showcase the following relationships:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship by defining a function to create the plots. Include the linear regression line, the model's formula, and the r^2 values. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Plots should be created for each of the following:
* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

## Part 2: VacationPy
Use the Geoapify API and the geoViews Python library to create map visualizations that help plan a future vacation.
1. Create a map plot that displays a point for every city in the list of cities from Part 1. The size of the point should be the humidity in each city.
2. Narrow down the cities data to your ideal weather condition.
3. Create a new DataFrame to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Create a new map that displays the cities that meet your ideal weather conditions. Add the hotel name and the country as additional information in the hover message for each city on the map.
