🌦️ WEATHER APPLICATION

Experiment 13 | React JS

📌 About the Project

A dynamic Weather Application developed using React.js that fetches real-time weather information from the OpenWeatherMap API. It displays weather details for a selected city with graphical representation using Chart.js.

🎯 Objective

To create a React application that fetches and displays current and historical weather information using an external weather API and graphical charts.

🛠️ Tech Stack

⚛️ Frontend: React.js
💻 Language: JavaScript
🌐 API: OpenWeatherMap API
📊 Data Visualization: Chart.js
🔗 HTTP Requests: Axios
📦 Package Manager: npm
✨ Key Features

🌍 Search weather by city name
🌡️ Display temperature and weather conditions
💧 Show humidity and atmospheric pressure
💨 Display wind speed
📈 Visualize weather data using charts
🔄 Fetch weather information from an external API
⚡ Dynamic updates based on the selected city
🚀 Getting Started

Step 1: Create a React application

npx create-react-app weather-app cd weather-app

Step 2: Install the required packages

npm install axios chart.js react-chartjs-2

Step 3: Configure the API key

Create a ".env" file in the project root and add your OpenWeatherMap API key:

REACT_APP_OPENWEATHER_API_KEY=your_api_key_here

Step 4: Start the application

npm start

🔐 API Configuration

Get an API key from "OpenWeatherMap" (https://openweathermap.org/). Keep your API key private and never upload your ".env" file to GitHub.

📂 Project Structure

weather-app/ ├── public/ ├── src/ │ ├── components/ │ ├── Weather.js │ ├── App.js │ └── index.js ├── .env ├── .gitignore ├── package.json └── README.md

✅ Result

Successfully developed a React-based Weather Application that retrieves weather information from the OpenWeatherMap API and presents the data through an interactive interface with graphical visualization.

