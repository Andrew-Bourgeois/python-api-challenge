# python-api-challenge
## UNC-CH-DA - Module 6 - Python API Challenge

### **Instructions for Running Scripts**
* Clone the repository to your local machine
* Ensure you cd into the "/python-api-challenge" directory and use first the **WeatherPy_Bourgeois.ipynb** and then **VacationPy_Bourgeois.ipynb** Jupyter Notebooks.
* Note the updated csv and figures output from WeatherPy_Bourgeois.ipynb will be located in the folder "/python-api-challenge/output"

### **BACKGROUND** 

Use knowledge of Python requests, APIs, and JSON traversals to answer the fundamental question: "What is the weather like as we approach the equator?"

While the obvious answer is "It gets hotter.", we will prove it using city and weather data gathered from: OpenWeatherMap API, Geoapify API, and citipy

### **REQUIREMENTS**

**Part 1: WeatherPy**

**Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points)**
* Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)

* Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)

* Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)

* Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)

* Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)

**Compute Linear Regression for Each Relationship (40 points)**
* Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)

* Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)

* Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)

* Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)

* Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

* Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

* Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

* Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

**Part 2: VacationPy**
* Create a map that displays a point for every city in the city_data_df DataFrame (5 points)

* Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)

* For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)

* Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)


### **REFERENCES**
Data Sources:
*   Weather API : https://openweathermap.org/api
*   citipy 0.0.6 : https://pypi.org/project/citipy/
*   Geoapify : https://www.geoapify.com/ 
*   convert timestamp data from api to datetime and date: https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html#pandas.to_datetime 
*   Add additional column data to interactive hover on hvplot map points: https://hvplot.holoviz.org/reference/pandas/scatter.html 
