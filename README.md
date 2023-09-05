# City Weather

City Weather is a Python program that allows you to fetch and display weather information for specific cities using the OpenWeatherMap API.

## Features

- Retrieve real-time weather data for cities.
- Display current temperature, minimum temperature, and maximum temperature in Celsius (°C).
- User-friendly and informative output.
- Built-in error handling for network issues.

## Usage

1. **Installation**

   - Clone the repository to your local machine:

     ```bash
     git clone https://github.com/your-username/city-weather.git
     ```

   - Navigate to the project directory:

     ```bash
     cd city-weather
     ```

2. **Fetch Weather Data**

   To fetch weather data for a city, create an instance of the `CityWeather` class and provide the city name, latitude, and longitude as arguments:

   ```python
   from city_weather import CityWeather

   city = CityWeather("City Name", latitude, longitude)
