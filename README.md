
# Weather App

This repository contains a simple weather application that allows users to search for current weather conditions by city name. The application fetches real-time data from the [OpenWeatherMap API](https://openweathermap.org)
 and displays the temperature, humidity, wind speed, and weather condition using icons.




## Features

- Real-time weather data: Retrieves temperature, humidity, wind speed, and weather conditions for any city.
- Dynamic icons: Displays different icons based on weather conditions such as rain, clear sky, clouds, etc.
- Error handling: Displays an error message for invalid city names or network issues.
- Smooth animations: Includes animations for displaying weather data and error messages.


## Usage
1. Open the application and use the input box to search for a city by name.
2. The app will display:
- Current temperature in Celsius.
- The name of the city.
- Humidity percentage.
- Wind speed in Km/h.
- An icon representing the current weather (clear, clouds, rain, snow, etc.).
3. If an invalid city is entered, an error message will appear indicating that the city was not found.

## Example
- Enter New York in the search bar.
- The app will display the weather for New York with the appropriate icon and data.

## Technologies
- HTML5: Structure of the web page.
- CSS3: Styling and layout.
- JavaScript (ES6+): Handling user input, fetching data from the API, and updating the DOM dynamically.
- OpenWeatherMap API: Provides real-time weather data.