# Today's Weather

A simple weather app that displays current conditions for major U.S. cities, with a search feature to check any city’s forecast.

## Features

- View today’s weather for cities like **Boston, Chicago, and Seattle**  
- Search for weather by city and state (e.g., `"Miami, FL"`)  
- Clean, responsive UI with real-time data  

## Tech Stack

- **React** – Frontend framework for building the UI  
- **React Router** – Handles navigation for search functionality  
- **Vanilla CSS** – Custom styles for a lightweight, responsive design  
- **WeatherAPI** – Fetches real-time weather data (powered by [WeatherAPI.com](https://www.weatherapi.com/))  

## Getting Started

### API Key Setup

- Request an API key from [WeatherAPI.com](https://www.weatherapi.com/)
- Add config.js file with the following:
      const API_KEY = 'YOUR API_KEY';
      export default API_KEY;

## Installation

### Clone the repo:
- git clone https://github.com/your-username/todays-weather.git
- cd todays-weather
- npm install
- Create a .env file in the root directory
- Add: REACT_APP_WEATHER_API_KEY=your-api-key
- Add your WeatherAPI key:
  
### Start the app:
- npm start
