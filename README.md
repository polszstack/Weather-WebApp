# 🌤️ Weather • Local Forecast

A beautiful, modern weather application that provides real-time weather data and hourly forecasts using the OpenWeatherMap API. Features automatic location detection, city search, and a stunning glassmorphism UI design.

![Weather App Preview](https://img.shields.io/badge/Status-Active-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **📍 Automatic Location Detection** - Get weather for your current location with one click
- **🔍 City Search** - Search for weather in any city worldwide
- **🌡️ Real-time Weather Data** - Current temperature, feels like, humidity, wind speed, pressure, and visibility
- **⏰ Hourly Forecast** - 24-hour forecast with temperature, weather icons, and descriptions
- **🎨 Modern Glassmorphism UI** - Beautiful frosted glass design with gradient backgrounds
- **📱 Fully Responsive** - Optimized for all devices from mobile to desktop
- **🔒 Privacy-Focused** - Location permission handling with clear user guidance
- **💾 Persistent Preferences** - Remembers your location permission choice
- **⚠️ Browser Compatibility Warnings** - Alerts users when using in-app browsers with limited functionality

## 🚀 Live Demo

[View Live Demo](https://your-username.github.io/Weather.png) <!-- Replace with your actual demo link -->

## 📸 Screenshots

<!-- Add screenshots here -->



## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Advanced styling with:
  - Glassmorphism effects (backdrop-filter)
  - CSS Grid & Flexbox layouts
  - Custom animations and transitions
  - CSS variables for theming
- **JavaScript (ES6+)** - Core functionality:
  - Fetch API for HTTP requests
  - Geolocation API for location services
  - Local Storage for user preferences
  - DOM manipulation for dynamic content
- **OpenWeatherMap API** - Weather data source:
  - Current Weather Data API
  - 5 Day / 3 Hour Forecast API
  - Geocoding API (reverse geocoding)
- **Font Awesome 6** - Icon library
- **Google Fonts** - Inter font family

## 📋 API Reference

This app uses the following OpenWeatherMap API endpoints:

| Endpoint | Description |
|----------|-------------|
| `api.openweathermap.org/data/2.5/weather` | Current weather data |
| `api.openweathermap.org/data/2.5/forecast` | 5-day forecast (3-hour intervals) |
| `api.openweathermap.org/geo/1.0/reverse` | Reverse geocoding (coordinates to location name) |

**Note:** You'll need your own API key. Get one free at [OpenWeatherMap](https://openweathermap.org/api).

## 🚀 Installation & Setup

### Option 1: Direct Use
1. Clone the repository:
```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app