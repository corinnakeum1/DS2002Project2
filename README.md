# DS2002Project2
Weather Data Analysis & Chatbot
This project combines local CSV-based weather data analysis, live weather API integration, and a simple Flask web chatbot. It allows users to:

View average historical weather data for select cities.

Fetch real-time weather information using the Weatherstack API.

Merge and clean global historical weather data.

Store the cleaned and enriched data into a SQLite database.

Interact with a basic chatbot via a Flask web interface.

weather-project/
├── weather_data.csv                # Local city-level weather data
├── GlobalWeatherRepository.csv     # Global weather dataset (raw)
├── weatherDB.sqlite                # SQLite database for storing data
├── app.py                          # Flask chatbot web app
├── templates/
│   └── home.html                   # Homepage template
├── requirements.txt                # Required Python packages
└── README.md                       # This documentation

Features
Historical Weather Data
Reads and processes a local CSV of weather data.

Calculates city-wise averages for temperature, humidity, wind, and precipitation.

Live Weather via API
Uses Weatherstack API to fetch:

Current temperature, humidity, condition

Feels-like temperature

Air quality and moon phase

Chatbot via Flask
Web-based chatbot interface that responds to:

Average weather queries: average weather in Houston

Live weather queries: current weather in New York

Data Cleaning & Enrichment
Cleans and corrects country/city names in global weather data.

Filters valid observations.

Merges cleaned historical data with current API results.

🗄SQLite Integration
Stores cleaned data in a local weatherDB.sqlite database with a global table.

Installation
Clone this repo:

bash
Copy
Edit
git clone https://github.com/your-username/weather-chatbot.git
cd weather-chatbot
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Add your Weatherstack API key in app.py:

python
Copy
Edit
api_key = "YOUR_API_KEY_HERE"
Run the Flask app:

bash
Copy
Edit
python app.py
Visit http://127.0.0.1:5000 in your browser.
