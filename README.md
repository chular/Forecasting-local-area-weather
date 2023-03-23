# project
This is a Python code that defines a class named City that gets data about the current weather in a city using the OpenWeatherMap API. The class has a constructor method (__init__) that takes in the name of the city, its latitude and longitude, and optionally the units of temperature to use. The default unit is metric.

When a City object is created, it automatically calls the get_data method, which sends a GET request to the OpenWeatherMap API using the provided latitude and longitude to obtain information about the current weather in the specified city. The response is then converted to JSON and stored in an attribute of the City object named response_json.

The get_data method also extracts the temperature, minimum temperature, and maximum temperature from the response JSON and stores them as attributes of the City object.

Finally, the City class defines a method named temp_print that prints out the current temperature, minimum temperature, and maximum temperature of the city.
