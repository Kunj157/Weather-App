# Weather App

A sleek and responsive weather application that provides real-time weather data for any city worldwide. Built with modern web technologies, it features automatic location detection and a search functionality to keep you updated on current weather conditions.

## 🌟 Features

- **Automatic Location Detection**: Uses the browser's Geolocation API to fetch weather data for your current city upon arrival.
- **Global Search**: Search for weather information by city name using the OpenWeatherMap Geocoding API.
- **Detailed Weather Metrics**:
    - Current Temperature (Celsius)
    - Min and Max Temperature
    - "Feels Like" Temperature
    - Weather Description (e.g., Clear, Clouds, Rain)
    - Humidity Percentage
    - Wind Speed (km/h)
- **Responsive Design**: A beautiful, centered weather card with a dynamic background.

## 🚀 Tech Stack

- **HTML5**: Semantic structure for the web app.
- **CSS3**: Custom styling with a focus on modern typography (Inter, Montserrat, Oxygen, Roboto) and a glassmorphism-inspired UI.
- **JavaScript (ES6+)**: Handles API calls, DOM manipulation, and geolocation logic.
- **[OpenWeatherMap API](https://openweathermap.org/api)**: Powers the weather data and geocoding services.

## 🛠️ Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kunj157/Weather-App.git
   ```
2. **Open the project**:
   Navigate to the project directory and open `weather.html` in your favorite web browser.

No build steps or dependencies are required as this is a vanilla JS project!

## 📁 Project Structure

- `weather.html`: The main entry point containing the application structure.
- `weather.css`: Contains all styles including layouts, fonts, and background configurations.
- `weather.js`: Logic for fetching data from OpenWeatherMap and updating the UI.
- `weatherCard.jpg`: Background image used for the weather card UI.

## 🔑 API Configuration

The project uses the OpenWeatherMap API. A default API key is included in `weather.js`, but for production use, it's recommended to sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and use your own key.

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

## 📝 License

This project is open-source and available under the MIT License.
