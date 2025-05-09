# DS2002Project2

# Weather Data Analysis Project

This project centers on building a weather bot that responds to user prompts by providing real-time weather information for any requested city. To accomplish this, we integrated live API data from weatherstack, which offers real-time and historical weather details globally. Through this API, the bot retrieves data such as temperature, weather conditions, "feels like" temperature, humidity, and moon phase based on the user's query.

In addition to live data, we incorporated a large historical dataset (weather_data.csv) containing over 980,000 rows of U.S.-based weather records. This dataset includes temperature, humidity, precipitation, and wind speed data for various cities across the United States.

By combining these two sources—global real-time data via API and detailed historical U.S. weather data from the CSV—we ensured that our weather bot can provide informative responses for cities both in the U.S. and worldwide.

## Files in This Repository

- `final.ipynb`: The main Jupyter notebook with all the analysis.
- `weather_data.csv.zip`: Compressed CSV file containing the weather dataset.
- `Data Project 2_ Reflection.pdf`: A written reflection on the data project.
- `README.md`: This file.

## Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/corinnakeum1/DS2002Project2
   cd DS2002Project2

2. Install:
   ```bash
   from flask import Flask, render_template, request, jsonify
   import requests  # for API calls
   import pandas as pd
   import json
   import pandas as pd
   import json
   import requests
   import sqlite3
   import calendar

3. Upload Weather_Data.csv to the final.ipynb
4. Set Up Flask App
5. Create HTML Templates
6. Run the Flask App




