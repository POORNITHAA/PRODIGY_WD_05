# Atmosphere Weather Web App

A beautiful, single-page weather interface designed with a modern **Glassmorphism** visual style. This application pulls live weather metrics globally from the OpenWeatherMap API based on manual user queries or browser-level precise geolocation data.

## 🌟 Features
* **Glassmorphism UI:** Stunning frosted glass card design utilizing CSS backdrop-filters for a highly tactile web experience.
* **Dual Location Input:** Check weather statistics by typing a specific city or by retrieving your immediate local coordinate positioning via native browser geolocation.
* **Live API Integrations:** Real-time data sync for temperatures, cloud conditions, wind speed, and relative humidity percentages.
* **Responsive Layout:** Automatically scaling components optimized perfectly for desktop monitors, tablets, and smartphone displays.

## 🛠️ Built With
* HTML5
* CSS3 (Flexbox, Grid, Backdrop Filters, Keyframe Animations)
* JavaScript (ES6 Fetch API, Async/Await, Native Geolocation API)

## 🚀 Getting Started

### Prerequisites
To run this application locally, you do not need any local servers or complex installations. You only need a web browser and a free API Key from OpenWeatherMap.

### Setup Instructions
1. Clone or download the repository files to your computer.
2. Sign up or log in to [OpenWeatherMap](https://openweathermap.org/).
3. Navigate to your dashboard, copy your unique API Key from the **API keys** tab.
4. Open the `weather.html` file using any text editor (like VS Code or Notepad).
5. Locate the configuration line near the top of the script tag:
   ```javascript
   const CONFIG_KEY = 'YOUR_API_KEY_HERE';
