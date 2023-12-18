# Weather App

## Overview

The Weather App is a simple web application that fetches and displays real-time weather information based on the user's geolocation using the OpenWeatherMap API. It provides details such as temperature, weather description, and sunrise/sunset times.

## Technologies Used

- HTML
- CSS
- JavaScript

## Project Structure

The project consists of three main components:

### 1. HTML (index.html)

The HTML file defines the structure of the Weather App. It includes placeholders for displaying weather-related information, such as location, temperature, and weather description. The external styles and dynamic behavior are linked through CSS and JavaScript files.

### 2. CSS (style.css)

The CSS file contains styles for the Weather App, providing a visually appealing and responsive design. It sets the font family, background, and styles for various elements such as the main container, weather information, and location details.

### 3. JavaScript (script.js)

The JavaScript file interacts with the OpenWeatherMap API to fetch weather data based on the user's geolocation. It dynamically updates the DOM elements with the received information, including the weather icon, location, temperature (in Celsius and Fahrenheit), weather description, sunrise, and sunset times.

## Usage

To run the Weather App, open the `index.html` file in a web browser. The app will prompt the user for geolocation access to fetch real-time weather data. Note: Ensure that the OpenWeatherMap API key in the JavaScript file (`script.js`) is valid and not shared publicly.

## Acknowledgments

- Weather data is provided by OpenWeatherMap. (API Key is not shared publicly.)
- Icons by Icons8 (<https://icons8.com>).

## License

This project is licensed under the [MIT License](LICENSE).
