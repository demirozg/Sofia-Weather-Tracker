# Sofia Weather Tracker

## Overview

Sofia Weather Tracker is a clean, modern web application for displaying current weather conditions and a 5-day forecast for Sofia, Bulgaria. The application features a responsive design that works well on both desktop and mobile devices.

## Features

- **Current Weather Conditions**: Displays current temperature, weather description, humidity, wind speed, and "feels like" temperature
- **5-Day Forecast**: Shows predicted temperatures with min/max values for the next 5 days
- **Interactive Chart**: Visual representation of temperature trends using Chart.js
- **Auto-Refreshing Data**: Weather information updates every 30 minutes
- **Responsive Design**: Optimized for both desktop and mobile viewing
- **Loading Indicators**: Visual feedback while data is being fetched

## Technologies Used

- HTML5
- CSS3 with modern styling techniques
- Vanilla JavaScript with async/await for API calls
- Chart.js for temperature visualization
- OpenWeatherMap API for weather data

## How It Works

The application fetches real-time weather data from OpenWeatherMap API and displays it in a user-friendly interface. It makes two API calls:
1. Current weather data for Sofia
2. 5-day forecast data

The data is then processed and displayed in both text format and as an interactive chart.

## API Usage

The application uses the free tier of OpenWeatherMap API. The included API key has usage limitations. If you plan to use this code for your own purposes or deploy it publicly, please register for your own API key at [OpenWeatherMap](https://openweathermap.org/api).


## Future Improvements

Potential enhancements for this project could include:
- Adding the ability to search for different locations
- Including additional weather metrics like pressure, visibility, or UV index
- Adding historical weather data
- Implementing a more detailed hourly forecast
- Adding weather alerts for severe conditions

## License

This project is free to use for personal and educational purposes.
