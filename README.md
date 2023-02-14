# Weather Latitude Analysis
Weather.py is an analysis of weather for temperature, humidity, wind speed, and cloudiness by latitude. This program will use api keys stored in a config.py file to build a list of cities and then analyze the weather data returned from openweathermap.org <br><br>
Vacation.py is a search for hotels in cities selected by weather parameters returned in the Weather.py program. Vacation.py will use api keys stored in a config.py file to return a list of hotels from geoapify.com located within 10,000 meters of the filtered city locations.<br><br>
VacationPy and WeatherPy are stored in starter_code folder and will look for and save to "../output_data/cities.csv"<br>
Provide api keys in a config.py file in starter_code folder named weather_api_key (openweathermap.org) and geoapify_key (geoapify.com)<br>
