# Python + APIs

Python script that creates a representative visualization of weather from 600+ cities across the globe. Script is able to randomly select at least 500 unique cities based on latitude and longitude and perform a weather check on each city using a series of successive API calls. 

Findings: 

![Temp](/WeatherPy/MaxTempvLat.png)

Out of all the graphs produced, the temperature graph (determined by the max-temperature) shows the strongest correlation to Latitude. As expected, the weather becomes significantly warmer as one approaches the equator (0 Degrees Latitude).More interesting, however, is the fact that the southern hemisphere tends to be warmer this time of year (December) than the northern hemisphere, due to the Earth's axial tilt. 

![Clouds](/WeatherPy/CloudinessTempvLat.png)

The cloudiness graph shows the most variability, giving us no clear relationship between latitude and cloudiness. We even see contrasting levels of cloudiness (0% vs 100%) in latitudes near each other. For example, between 20 & 50-degrees latitude we see a high concentration of 0% cloudy, while at 50 to 70-degrees latitude we see a high concentration of 100% cloudy instances.  

![Winds](/WeatherPy/Windspeed.png)

Additionally, there is no strong correlation between latitude and wind speed. However, in northern hemispheres, windspeed appears to be most variable beween 60 & 80-degrees latitude, where there exists a flurry of cities with over 20 mph of wind.
