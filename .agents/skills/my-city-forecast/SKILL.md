---
name: my-city-forecast
description: Get city weather forecast from the web and format a report out of it
---

# Weather retrieving and report computing logic

## Get th weather forecast
Get the weather forecast for th specified city from https://weather.com/
Then, from that, extract the following forecast data for the next day:
- Date
- forecast description in a one liner
- High and low temperatures

## Formatting the report
From the extracted data format the city weather forecast report as follows:
"In " + <city name> + " tomorrow," + <Date> +", the weather forecast is: " + <forecast description>.
"Maximum temperature will be " + <High temperature> + " and lowest temperature will be " + <low temperature> 

## Create output file
Create an output file with exactly the formatted content, with filename: <city name>_<date>_forecast.txt
Commit and push it at the root of the Github repository. 
