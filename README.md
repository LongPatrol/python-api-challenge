# python-api-challenge

## Weather Py
For this exercise, we are analyzing the relationship of various weather phenomenon and whether or not those phenomena are dependent on latitude. We are calling the Open Weather api for our weather data: https://openweathermap.org/api . We are also using the CityPy package to find the nearest city to a random assortment of latitudes and longitudes.

### Temperature vs. Latitude:
![Temperature vs. Latitude](https://github.com/LongPatrol/python-api-challenge/blob/main/WeatherPy/images/latitude_temp_all.png)

The code here is getting the latitude and max temperature from our city dataframe. We are using a scatter plot to compare these two together. We're asking: Is temperature dependent on latitude?


## Vacation Py
Now we are going to take our weather data from above and look for cities for our perfect getaway. Once we identify those wonderful places, we need to find a place to stay and figure out how to get to those hotels. We are using the gmaps package to map a humdity heatmap (just for kicks), and to plot markers for the locations of our hotels. To find the hotels, we are calling Google's place api with the nearbysearch.
