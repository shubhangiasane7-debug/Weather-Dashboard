# Weather-Dashboard
Task 4 Weather-Dashboard
# 🌦️ Real-Time Weather Dashboard

## 📌 Project Overview

The Real-Time Weather Dashboard is a web application developed using HTML, CSS, and JavaScript. It allows users to search for a city and view its current weather information using public REST APIs.

This project demonstrates asynchronous JavaScript, API integration, JSON data processing, and error handling.

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Display current temperature in Celsius
- 💧 Show humidity percentage
- 💨 Display wind speed in km/h
- 🌤️ Show weather conditions such as clear sky, cloudy, and rain
- 🌡️ Display feels-like temperature
- 🕒 Show local weather observation time
- ⚠️ Handle invalid city names and network/API errors
- 📱 Responsive design for mobile and desktop screens

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API
- Async/Await
- REST APIs
- JSON

## 🌐 APIs Used

This project uses the following free public APIs from Open-Meteo:

1. **Geocoding API:** Converts city names into geographical coordinates.
2. **Weather Forecast API:** Retrieves current weather information using latitude and longitude.

Website: https://open-meteo.com/

No API key is required for this project.

## 📂 Project Structure

```text
Weather-Dashboard/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Install the Live Server extension if it is not already installed.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. Enter a city name, such as Pune or Mumbai.
7. Click the Search button to view the weather information.

An active internet connection is required to fetch weather data from the APIs.

## 🧪 Testing

The application can be tested using the following inputs:

| Test Case | Input | Expected Result |
|---|---|---|
| Valid city | Pune | Displays Pune weather |
| Another city | Mumbai | Displays Mumbai weather |
| Invalid city | xyzabc123 | Displays an error message |
| Empty search | No city entered | Requests a city name |
| Network/API failure | API unavailable | Displays an error message |

## 📚 Learning Outcomes

Through this project, I learned how to:

- Use the Fetch API to retrieve data from a REST API.
- Implement asynchronous operations using `async` and `await`.
- Parse JSON responses and access nested objects.
- Update webpage content dynamically using the DOM.
- Handle network errors and invalid user inputs.
- Create a responsive user interface using CSS.

## 🔮 Future Enhancements

- Add a seven-day weather forecast.
- Display weather icons and background changes.
- Save recently searched cities.
- Add temperature unit conversion between Celsius and Fahrenheit.
- Improve the dashboard with additional weather information.

## 👩‍💻 Author

**Shubhangi Asane**

## 📄 License

This project was developed for educational and internship purposes.
