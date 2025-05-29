# Simple Weather App

A clean and simple web application that displays the current weather conditions for a searched city using the OpenWeatherMap API.

## Features

City-Based Weather Search: Enter any city name to get its current weather.
Dynamic Weather Information Display:
    *   Temperature (in Celsius)
    *   City Name
    *   Humidity percentage
    *   Wind speed (in km/h)
Dynamic Weather Icons: The weather icon changes based on the current conditions (e.g., rain, clouds, clear, drizzle, mist).
User-Friendly Interface: Simple card-based design.
Error Handling: Displays an "Invalid city name" message if the city is not found or if there's an API error.
Responsive Design: Adapts to different screen sizes (though primarily designed for desktop/mobile portrait).

## Get an API Key from OpenWeatherMap:**
    *   Go to [OpenWeatherMap](https://openweathermap.org/appid) and sign up for a free API key if you don't have one.
    *   Once you have your API key, open the `index.html` file in a text editor.
    *   Find the following line in the `<script>` section:
        ```javascript
        const apiKey = "b6178254d29eed3a9f2e647fc9a6839f"; // <-- REPLACE THIS WITH YOUR KEY
        ```
    *   Replace `"b6178254d29eed3a9f2e647fc9a6839f"` with your **actual OpenWeatherMap API key**.
note:I used deault api key
## Use the App:
    *   Type a city name into the search bar.
    *   Click the search button (or press Enter if you implement that).
    *   The weather information for the entered city will be displayed.
## Run the app
start index.html 
