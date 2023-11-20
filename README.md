

## Building Energy Analytics: Patterns and Meteorological Drivers

# Description

This project focuses on analyzing the energy consumption of a university building in Bangkok, Thailand. The goal is to identify patterns and understand the meteorological drivers influencing energy usage. To achieve this, we have merged the energy consumption dataset with corresponding meteorological conditions during the period spanning July 2018 to December 2019.

Building Consumption: https://www.kaggle.com/datasets/claytonmiller/cubems-smart-building-energy-and-iaq-data
this data can be downloaded, the files...

Meteorological Data : https://www.visualcrossing.com/weather-api
Purchased using the website's API. There is a separafile file called 'weatherapi' showing the query for this. 


# Description of Columns in Final dataset.

Date: The date of the entry.
Day: The day of the week.
Month: The month of the year.
Year: The year of the entry.
Time: The time of the entry.
Hour: The hour of the entry.
total_light(kW): Total energy consumption for lighting (in kilowatts).
total_ac(kW): Total energy consumption for air conditioning (in kilowatts).
total_plug(kW): Total energy consumption for plugged devices (in kilowatts).
avg_temp(degC): Average temperature in degrees Celsius.
avg_rel_humidity(%): Average relative humidity as a percentage.
datetime: Combined date and time information.
temp: Temperature.
feelslike: "Feels like" temperature.
dew: Dew point temperature.
humidity: Humidity percentage.
precip: Precipitation.
precipprob: Probability of precipitation.
preciptype: Type of precipitation.
windspeed: Wind speed.
winddir: Wind direction.
sealevelpressure: Sea level pressure.
cloudcover: Cloud cover percentage.
visibility: Visibility.
solarradiation: Solar radiation.
solarenergy: Solar energy.
uvindex: UV index.
conditions: Weather conditions.
icon: Weather icon.
wind_direction: Wind direction.
