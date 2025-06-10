# Weather App

A modern, responsive weather application that provides real-time weather information for any city worldwide. Features include search suggestions, unit toggling (Celsius/Fahrenheit), and a "Use My Location" feature that fetches weather based on your current location.

## Features

- 🔍 Search for cities with autocomplete suggestions  
- 📍 "Use My Location" to get weather for your current location  
- 🌡️ Toggle temperature units between Celsius and Fahrenheit  
- 🌤️ Displays temperature, wind speed, humidity, and "feels like" temperature  
- 📱 Responsive design for desktop and mobile  
- ⚡ Fast, clean, and user-friendly interface  

## Demo

[Live Demo]

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).**

3. **Create a `config.js` file in the root directory:**
   ```js
   // config.js
   export const apiKey = 'YOUR_API_KEY_HERE';
   ```
   *This file is ignored by `.gitignore` to keep your API key safe.*

4. **Run a local development server (required for ES modules):**
   ```bash
   python -m http.server 8000
   ```
   Or use any local server (like the VS Code Live Server extension).

5. **Open the app in your browser:**
   ```
   http://localhost:8000
   ```
   Or use your local IP address to view it on mobile.

## Usage

- Start typing a city name to see suggestions and select one.
- Click the location icon to get weather for your current location (browser permission required).
- Use the °C/°F toggle to switch between temperature units.

## Technologies Used

- HTML5, CSS3, JavaScript (ES6 Modules)
- [OpenWeatherMap API](https://openweathermap.org/)
- [Font Awesome](https://fontawesome.com/)
- [Feather Icons](https://feathericons.com/)
- Python HTTP server (`python -m http.server`) for local development

## Author

**Shashank Raj**
