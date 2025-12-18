# Weather App 🌤️

A simple and clean weather application that fetches real-time weather data using the OpenWeatherMap API. Just search for a city and get instant weather information including temperature, humidity, and wind speed.

## 🚀 Features

- **Real-Time Weather Data**: Fetches current weather from OpenWeatherMap API.
- **Dynamic Weather Icons**: Shows different icons based on weather conditions (sunny, cloudy, rainy, etc.).
- **Temperature Display**: Shows temperature in Celsius.
- **Humidity & Wind Speed**: Displays additional weather details.
- **Error Handling**: Shows an error message for invalid city names.
- **Responsive Design**: Works smoothly on different screen sizes.

## 🛠️ Tech Stack

- **HTML5**: Structure
- **CSS3**: Styling and layout
- **JavaScript**: API calls and DOM manipulation
- **OpenWeatherMap API**: Real-time weather data

## 📋 What You'll See

The app displays:
- Current temperature
- City name
- Weather condition with matching icon
- Humidity percentage
- Wind speed (km/h)

## 🎨 Supported Weather Conditions

The app recognizes and displays icons for:
- ☀️ Clear sky
- ☁️ Clouds
- 🌧️ Rain
- 💧 Drizzle
- 🌫️ Mist

## 📂 Project Structure

```
weather/
├── index.html        # Main HTML file with embedded JS
├── style.css         # Styling
├── search.png        # Search button icon
├── clear.png         # Clear weather icon
├── clouds.png        # Cloudy weather icon
├── rain.png          # Rainy weather icon
├── drizzle.png       # Drizzle weather icon
├── mist.png          # Misty weather icon
├── humidity.png      # Humidity icon
└── wind.png          # Wind speed icon
```

## 🏃 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/alk231/weather.git
   ```

2. **Open in browser**
   - Just open `index.html` in your browser.
   - No installation or build process needed!

3. **Search for a city**
   - Type a city name in the search box.
   - Click the search button (or press Enter).
   - Wait for the weather data to load.

## 🔑 API Key

The app uses OpenWeatherMap API. The API key is included in the code, so it should work out of the box. If you want to use your own API key:

1. Go to [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up and get your free API key
3. Replace the `apiKey` value in `index.html`

## ⚡ Try It Out

This is a great learning project if you want to understand:
- Async/await in JavaScript
- Fetching data from APIs
- DOM manipulation based on API responses
- Error handling
- Conditional rendering

## 📝 Example Searches

Try searching for:
- London
- New York
- Tokyo
- Sydney
- Any city around the world!

## 👨‍💻 Author

**Alok Kumar**
- GitHub: [@alk231](https://github.com/alk231)

---
*Made with ❤️ and some JavaScript magic.*
