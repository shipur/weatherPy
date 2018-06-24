# weatherPy
Mapping the weather of various cities across the globe.

In this example, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api).

The objective was to build a series of scatter plots to analyze the weather and showcase the following relationships:

### Temperature (F) vs. Latitude
<img width="394" alt="screen shot 2018-06-24 at 5 19 53 pm" src="https://user-images.githubusercontent.com/34551186/41823722-11e78a88-77d3-11e8-953c-26a1e95c98b0.png">
### Humidity (%) vs. Latitude
<img width="403" alt="screen shot 2018-06-24 at 5 20 09 pm" src="https://user-images.githubusercontent.com/34551186/41823724-1568064c-77d3-11e8-9dd8-d1e25408eca4.png">
### Cloudiness (%) vs. Latitude
<img width="402" alt="screen shot 2018-06-24 at 5 20 23 pm" src="https://user-images.githubusercontent.com/34551186/41823725-17562d62-77d3-11e8-8b51-b193ee0aa0ec.png">

### Wind Speed (mph) vs. Latitude
<img width="398" alt="screen shot 2018-06-24 at 5 20 38 pm" src="https://user-images.githubusercontent.com/34551186/41823726-19d6b30e-77d3-11e8-98a6-e58f88751c3c.png">


## Analysis
* As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.
* There is no strong relationship between latitude and cloudiness, however, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.
* There is no strong relationship between latitude and wind speed, however in northern hemispheres there is a flurry of cities with over 20 mph of wind.
