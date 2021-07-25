# World_Weather_Analysis

## Overview

In this module we learned how to use APIs to retrieve data.  We then applied the retrieved data into various formats such as heat maps, travel destinations and Itineraries.

## Key Take Aways

The new tools that we learned during this module was the use of numpy, APIs, json, setting params, using info box templates and mapping

The use of random from Numpy:
`lats = np.random.uniform(low=-90.000, high=90.000, size=2000)`

URL to call an API and creating a mask for the API:
`url = "http://api.openweathermap.org/data/2.5/weather?units=Imperial&APPID=" + weather_api_key`

json:
`city_url = url + "&q=" + "ushuaia"
city_weather = requests.get(city_url)
city_weather.json()`

Setting params:
`params = {
    "radius": 5000,
    "type": "lodging",
    "key": g_key
}`

Using info box templates:
`<dl>
<dt>City</dt><dd>{City}</dd>
<dt>Country</dt><dd>{Country}</dd>
<dt>Current_Description</dt><dd>{Current_Description}</dd>
<dt>Max Temp</dt><dd>{Max Temp} °F</dd>
</dl>
"""`

![WeatherPy_Map](/Vacation_Search/WeatherPy_vacation_map.png)

