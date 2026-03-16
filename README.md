# CloudSun
"A sleek, responsive weather application built with vanilla JavaScript, HTML, and CSS that fetches real-time weather data for any city worldwide using the OpenWeatherMap API."

# 🌤️ Weather App

This project is a web application with a modern interface that allows users to quickly and easily check the current weather information for any city they choose. 

The application first converts the entered city name into latitude and longitude coordinates using a Geocoding API, and then uses these coordinates to fetch and display real-time weather data.

## ✨ Features

* **City-Based Search:** Instantly check the weather for any city in the world.
* **Detailed Data:** Displays the current temperature (in Celsius), a brief weather description, and corresponding dynamic weather icons.
* **Error Handling:** Provides informative UI messages for empty inputs or invalid/incorrect city names.
* **Responsive Design:** Fully optimized to look great on both desktop screens and mobile devices.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and layout.
* **CSS3:** Modern, flexible (Flexbox), and responsive visual design.
* **JavaScript (ES6+):** Asynchronous data fetching (`async/await`) and dynamic DOM manipulation.
* **OpenWeatherMap API:** * *Geocoding API:* To convert city names into geographical coordinates (Lat/Lon).
  * *Current Weather Data API:* To fetch weather data based on those coordinates.

## 🚀 Setup and Usage

To run this project on your local machine, follow these steps:

1. Download or clone this repository to your local machine.
2. Go to [OpenWeatherMap](https://openweathermap.org/), create a free account, and get your own **API Key**.
3. Open the project folder in your preferred code editor (e.g., VS Code).
4. Locate the `apiKey` variable at the top of the JavaScript code (or in the `script.js` file):
   ```javascript
   const apiKey = "REPLACE WITH YOUR API KEY";
