# openweather-icons-to-emoji
Simple JSON to convert [OpenWeather icons](https://openweathermap.org/weather-conditions) to emoji, acceptable in CLI, or text representation. Available in plain text or Unicode
# Usage
For using in different languages just import JSON, and retrieve value from map
# JavaScript

```
const icons = require("./icons.json");
var emoji_icon = icons['01d'] //return emoji equal to 01d - clear sky ☀️

```
# Python

``` 
import json
with open('icons.json', 'r') as f:
	icons = json.load(f)
emoji_icon = icons['01d'] #return emoji equal to 01n - clear sky 🌑

```
