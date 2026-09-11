# Atmos — Live Weather Dashboard

Created by: Suryansh

Atmos is a modern weather web application built with HTML, CSS, and JavaScript. It fetches live weather data from the Open-Meteo API and presents it in a clean, atmospheric dashboard with a dynamic sky background, hourly forecast visualization, and daily weather summary.

## Project Overview

This project is a frontend weather app that lets users:

- Search for any city and view live weather data
- Use their browser location to get local weather conditions
- Switch between Celsius and Fahrenheit
- Check hourly forecast trends for the next 24 hours
- View key weather stats such as humidity, wind speed, pressure, cloud cover, precipitation, and UV index
- See an 8-day forecast
- Enjoy a weather-inspired animated wallpaper background that changes with the current condition

## Key Features

- Real-time weather data from Open-Meteo
- City search with suggestions
- Geolocation support
- Auto-refresh every 10 minutes
- Responsive glassmorphism UI
- Animated weather-based background
- Hourly chart and daily weather cards
- Modern dark theme and mobile-friendly layout

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Open-Meteo Geocoding API
- Open-Meteo Forecast API
- Canvas API for animated background effects

## Project Structure

```text
weather-main/
├── index.html
├── script.js
├── styles.css
├── README.md
└── .gitignore
```

The app is designed as a lightweight static website and does not require a package installation or build process.

## How It Works

1. The app loads with a default location (Ludhiana, Punjab, India).
2. It requests city search or geolocation data from the browser.
3. It fetches forecast data from the Open-Meteo API.
4. The UI renders current conditions, hourly trends, and a daily summary.
5. The background changes dynamically depending on the weather type.

## Prerequisites

To run this project locally, you need:

- A modern browser
- Python 3 (recommended for local serving)
- Internet connection for the live API

## Run the Project Locally

### Method 1: Python HTTP Server

Open the terminal in the project folder and run:

```bash
cd /Users/anil/Desktop/weather-main
python3 -m http.server 8000
```

Then open the app in your browser:

```text
http://localhost:8000
```

### Method 2: VS Code Live Server

- Open the project in VS Code
- Install the Live Server extension
- Right-click on `index.html`
- Select `Open with Live Server`

## API Integration

This project uses the Open-Meteo APIs:

- Geocoding API to find locations by city name
- Forecast API to fetch weather data for latitude and longitude

## Usage Guide

- Enter a city name in the search field.
- Select a city from the suggestions list.
- Use the location icon to fetch weather based on your current position.
- Click the refresh button to reload the latest forecast.
- Click the temperature value to toggle between °C and °F.

## Notes

- Geolocation requires browser permission.
- Weather data is fetched from a remote API and needs internet access.
- The app auto-refreshes every 10 minutes for the selected location.

## Future Improvements

Possible enhancements for this project:

- Add a weather alert section
- Include sunrise and sunset cards
- Add a seven-day forecast with more details
- Support more filters and search features
- Convert the project into React or Next.js later

## License

This project is intended for learning and personal use.

## Summary

Atmos is a polished weather dashboard that demonstrates API integration, dynamic UI updates, and interactive frontend design using only core web technologies.
