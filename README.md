# python-api-challenge

## Weather Py
For this exercise, we are analyzing the relationship of various weather phenomenon and whether or not those phenomena are dependent on latitude. We are calling the Open Weather api for our weather data: https://openweathermap.org/api . We are also using the CityPy package to find the nearest city to a random assortment of latitudes and longitudes.

You can see an example of one of the graphs in the next section. They are all in the images folder under WeatherPy:
### Temperature vs. Latitude:
![Temperature vs. Latitude](https://github.com/LongPatrol/python-api-challenge/blob/main/WeatherPy/images/latitude_temp_all.png)

The code here is getting the latitude and max temperature from our city dataframe. We are using a scatter plot to compare these two together. We're asking: Is temperature dependent on latitude?


## Vacation Py
Now we are going to take our weather data from above and look for cities for our perfect getaway. Once we identify those wonderful places, we need to find a place to stay and figure out how to get to those hotels. We are using the gmaps package to map a humdity heatmap (just for kicks), and to plot markers for the locations of our hotels. To find the hotels, we are calling Google's place api with the nearbysearch.

Below are the locations of my ideal weather conditions. I am apparently pretty picky:
![Humidity with hotels](https://github.com/LongPatrol/python-api-challenge/blob/main/VacationPy/images/humidity%20with%20hotel%20markers.png)

## Sources:

**Git ignore:**

Rosen, T. (2020, Dec 14). *How To Create A .gitignore File To Hide Your API Keys*. Medium. https://medium.com/@t.rosen2101/how-to-create-a-gitignore-file-to-hide-your-api-keys-95b3e6692e41

**Installing packages:**

PyPA. (2020, Dec 19). *Installing Packages*. PyPA. https://packaging.python.org/tutorials/installing-packages/

**Numpy.random.uniform:**

NumPy. (2020, Dec 19). *numpy.random.uniform*. NumPy. https://numpy.org/doc/stable/reference/random/generated/numpy.random.uniform.html

**Zip function:**

Programiz. (2020, Dec 19). *Python zip()*. Programiz. https://www.programiz.com/python-programming/methods/built-in/zip

**Dictionary to a csv:**

debo. (2020, Dec 19). *Write dictionary of lists to csv*. Stack Overflow. https://stackoverflow.com/questions/23396121/write-dictionary-of-lists-to-csv/41562434

**Debugging csv file help:**

Ransom, M. (2020, Dec 19). *python 3.2 UnicodeEncodeError: 'charmap' codec can't encode character '\u2013' in position 9629: character maps to <undefined>*. Stack Overflow. https://stackoverflow.com/questions/16346914/python-3-2-unicodeencodeerror-charmap-codec-cant-encode-character-u2013-i

**Csv skipping lines:**

Lanaru. (2020, Dec 19). *csv.write skipping lines when writing to csv*. Stack Overflow. https://stackoverflow.com/questions/11652806/csv-write-skipping-lines-when-writing-to-csv

**Index of a list:**

Programiz. (2020, Dec 19). *Python List index()*. Programiz. https://www.programiz.com/python-programming/methods/list/index

12/19/2020:
Wind speed unit of measure:
https://openweathermap.org/weather-data#current

Getting a value back from loc:
https://stackoverflow.com/questions/55661198/how-to-get-df-loc-to-just-return-the-value-number-from-a-specific-cell-of-a-da

12.20.2020
Substring:
https://www.freecodecamp.org/news/how-to-substring-a-string-in-python/
