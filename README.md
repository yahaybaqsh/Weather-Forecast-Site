# Weather Forecast App 🌤️

A simple **Weather Forecast website** built with **HTML, CSS, and JavaScript**.  
Users can search for a location and view weather information in **Celsius** or **Fahrenheit**, with a dynamic interface that changes based on the weather conditions.  

---

## Features

- **Search for Locations**
  - Users can input a city or location to get current weather data.
  
- **Weather Display**
  - Temperature in Celsius or Fahrenheit (toggleable)
  - Weather condition description (e.g., cloudy, sunny, rain)
  - Optional weather icons or GIFs representing the current weather
  - Dynamic background or color changes depending on weather conditions

- **API Integration**
  - Uses **Visual Crossing Weather API** to fetch weather data
  - Optionally integrates **Giphy API** for weather-related GIFs

- **User Interface**
  - Responsive design for desktop and mobile
  - Optional loading spinner while fetching data

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API / async-await for API requests
- Webpack (optional, for dynamic imports)
- Visual Crossing API (for weather data)
- Giphy API (optional, for GIFs)

---

## How to Use

1. Clone the repository or download the files.
2. Open `index.html` in your browser.
3. Enter a location in the search form and press submit.
4. Weather information will appear dynamically.
5. Toggle between Celsius and Fahrenheit to view temperature in your preferred unit.

---

## Notes on API Keys

- **Never expose sensitive API keys** publicly in production.
- For this project, the Visual Crossing API key is used publicly without security risk.
- In production, store API keys on the server using environment variables.
- GitHub may warn about exposed API keys; this is fine for learning purposes but should be avoided in real apps.

---

## Optional Enhancements

- Add loading animations while fetching data
- Display GIFs related to the weather using the Giphy API
- Store recent searches in **localStorage**
- Show hourly or weekly forecast

---

## Screenshots

![Weather Search](screenshots/weather-search.png)  
![Weather Result](screenshots/weather-result.png)  
![Dynamic Background](screenshots/dynamic-background.png)  

---

## License

This project is open-source and free to use.
