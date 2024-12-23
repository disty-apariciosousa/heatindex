# HEAT INDEX (HI)

The Heat Index (HI) is an index that describes how hot the temperature actually feels to the human body when relative humidity is taken into account. It combines both the air temperature and humidity to provide a more accurate measure of perceived heat, which is often referred to as the apparent temperature or feels-like temperature.

The Heat Index is important for assessing the health risks associated with high temperatures, such as heat stroke, dehydration, and heat exhaustion.

Heat Index Formula
The Heat Index can be calculated using the empirical formula below, which is valid when the temperature is in Fahrenheit (°F) and the relative humidity is in percentage (%).

## Formula:

![Formula HEAT INDEX](https://cdck-file-uploads-global.s3.dualstack.us-west-2.amazonaws.com/flex020/uploads/sws/original/2X/1/107877b6f0aefcbb913cbcf20636d0fe8e1d1438.png)


## Features

- Calculates the Heat Index based on temperature and humidity.
- Retrieves current weather data from a public API.
- Displays weather information with periodic updates.

## Code Example:

```bash
from heat_package.index import main

# coordinates from user actual location
latitude = -8.55309646857836
longitude = 125.5523432617644
main(latitude, longitude)
