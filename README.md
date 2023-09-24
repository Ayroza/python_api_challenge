# python-api-challenge

WeatherPy - Create a Python script to visualize the weather of over 500 cities of varying distances from the equator.

1. Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships: Latitude vs. Temperature , Latitude vs. Humidity, Latitude vs. Cloudiness, Latitude vs. Wind Speed

2. Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

You should create the following plots: Northern Hemisphere: Temperature vs. Latitude, Southern Hemisphere: Temperature vs. Latitude, Northern Hemisphere: Humidity vs. Latitude, Southern Hemisphere: Humidity vs. Latitude, Northern Hemisphere: Cloudiness vs. Latitude, Southern Hemisphere: Cloudiness vs. Latitude, Northern Hemisphere: Wind Speed vs. Latitude, Southern Hemisphere: Wind Speed vs. Latitude

VacationPy - Use your weather data skills to plan future vacations
1. Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition.
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
