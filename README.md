# 🌦️ Weather Dashboard with Chatbot Integration

## Introduction
This project is a **fully responsive weather dashboard** that displays real-time weather data using the **OpenWeather API** and interactive visualizations with **Chart.js**. Additionally, it integrates a chatbot using the **Gemini API** to respond to both weather-related and general queries. 🤖

## Features
- **🌍 Weather Widget**: Displays real-time weather for a user-searched city.
- **🎨 Dynamic Backgrounds**: Changes widget background based on weather conditions (e.g., cloudy, rainy).
- **📊 Interactive Charts**:
  - **🌡️ Bar Chart**: 5-day temperature trend.
  - **🍩 Doughnut Chart**: Weather condition percentages.
  - **📈 Line Chart**: Temperature changes over time.
- **📅 Tables with Pagination**: 5-day forecast with up to 10 entries per page.
- **🔍 Filters**: Sort and filter weather data (e.g., rainy days, highest temperature).
- **💬 Chatbot Integration**: Handles weather and general queries using the Gemini API.

## How to Run the Project Locally
1. **📥 Download the Project Files**:
   - Download the zip file and extract it to a folder on your computer.
   
2. **💻 Open the Project in Visual Studio Code**:
   - Launch Visual Studio Code.
   - Click on **File > Open Folder...** and select the extracted project folder.
   
3. **📂 Explore the Project Files**:
   - `index.html`: Home page with links to the dashboard and tables.
   - `dashboard.html`: Displays weather information, charts, and dynamic backgrounds.
   - `tables.html`: Contains a table with forecasts and chatbot integration.

4. **🔑 API Keys Configuration**:
   - Replace placeholder keys with your own **OpenWeather** and **Gemini API** keys in the JavaScript code.

5. **▶️ Run the Project**:
   - Right-click `index.html` and select 'Open with Live Server' (if installed).
   - Or open `index.html` directly in a browser.

## API Usage
This project utilizes two APIs:
- **☁️ OpenWeather API**: Fetches current weather and 5-day forecast data.
- **💬 Gemini API**: Handles chat responses for general queries.

> **⚠️ Note**: Ensure API rate limits are respected (60 calls/minute for OpenWeather free tier).

## Dependencies
The following libraries are required:
- **📈 Chart.js**: For generating visual charts. Included via CDN.
- **📊 chartjs-plugin-datalabels**: For adding chart animations.

## Project Screens
- **🏠 Home Page (`index.html`)**: Provides quick access to the Dashboard and Tables pages.
- **📊 Dashboard (`dashboard.html`)**: Displays weather data with charts and interactive elements.
- **📋 Tables (`tables.html`)**: Provides detailed forecasts, chatbot interaction, pagination, and sorting.

## Troubleshooting
- **❌ City Not Found**: Ensure the city name is spelled correctly.
- **🔑 API Key Issues**: Verify that your API keys are valid and correctly added.
- **🌐 Geolocation Issues**: Allow location permissions in your browser if using geolocation.

## Key Learning Outcomes
- 🌐 Working with RESTful APIs (OpenWeather and Gemini).
- 📊 Creating data visualizations using Chart.js.
- ⚠️ Handling API errors and invalid inputs effectively.
- 🖥️ Building responsive and interactive web interfaces.

---

**🎉 Enjoy Using Your Weather Dashboard!**
