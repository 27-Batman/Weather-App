🌦️ **Weather App**

A sleek and responsive weather application that delivers real-time weather updates for cities worldwide.

---

## 📖 Overview

The Weather App allows users to search for any city and instantly fetch live weather data using the OpenWeatherMap API. It displays the current temperature in Celsius, humidity percentage, a short weather description, and a corresponding weather emoji for a more engaging user experience.

---

## ✨ Features

- 🔍 City-based weather search
- 📡 Real-time data powered by OpenWeatherMap API
- 🌡️ Current temperature displayed in Celsius
- 💧 Humidity percentage display
- 🎭 Visual representation of weather with emojis
- ⚠️ Error handling for invalid searches or network issues

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **Fetch API**
- **OpenWeatherMap API**

---

## 🚀 Getting Started

1. Clone this repository:
    ```bash
    git clone https://github.com/27-Batman/Weather-App.git
    ```
2. Open the project folder.
3. Launch `index.html` in your preferred web browser.
4. Search for any city by entering its name in the input field.
5. Click on **"Get Weather"** or press **Enter** to view the live weather information.

---

## 🔑 API Information

This project uses the OpenWeatherMap API to fetch weather data.

⚠️ **Note:** The API key previously used in this project has been disabled.  
To use this application:  
- Obtain your own API key from [OpenWeatherMap](https://openweathermap.org/).  
- Securely store your API key (e.g., using environment variables or backend proxies).  
- Update the source code with your new API key where required.  

For example, in the `index.js` file, update the following line (line 4):  
```javascript
const apiKey = "YOUR_NEW_API_KEY";
```

---

## 🚧 Future Enhancements

- 🌡️ Add a Celsius ↔️ Fahrenheit toggle option
- 📅 Integrate a 5-day weather forecast
- 📍 Implement geolocation to automatically detect and show weather for the user's current location
- 🌗 Dark/Light mode theme toggle
- 🕒 Search history feature to revisit past queries

---

## 📜 License

This project is open-sourced under the **MIT License**.  
Feel free to use, modify, and distribute it.

---
