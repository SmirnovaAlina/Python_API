# Python_API 
# Weather API project

Useing data analysis libraries try to answer the question "What's the weather like as we approach the equator?"
## Usage

```python
import matplotlib.pyplot as plt
import pandas as pd
import numpy sd np
import requests 
import time
import json
```
## Description

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To rendom select (lat, lon) pairs use ```python  np.random.uniform ```,  for API  
[OpenWeatherMap API] (https://openweathermap.org/api/).

To answer a question build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

## Analysis

* As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.
* There is no strong relationship between latitude and cloudiness. However, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.
* There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a flurry of cities with over 20 mph of wind.
