##Name = Ayush Goyal
##course = Btech CSE (AI and ML)
##roll no = 2501730281




# 🌤️ Async Weather Tracker

## 📌 Project Description

Async Weather Tracker is a simple web application that allows users to search for the current weather of any city. The application fetches real-time weather data using the **OpenWeatherMap API** and displays important information such as temperature, weather condition, humidity, and wind speed.

The project demonstrates the use of **JavaScript Async/Await, Fetch API, DOM manipulation, and API integration**.

---

## 🚀 Features

* Search weather by city name
* Displays real-time weather information
* Shows:

  * Temperature
  * Weather condition
  * Humidity
  * Wind speed
* Recent search history
* Click previous searches to view weather again
* Responsive and attractive UI using CSS

---

## 🛠️ Technologies Used

* **HTML** – Structure of the web page
* **CSS** – Styling and UI design
* **JavaScript** – Functionality and API calls
* **OpenWeatherMap API** – Fetch weather data

---

## 📂 Project Structure

```
Async-Weather-Tracker
│
├── 1.html        # Main HTML file
├── 2.css         # Styling file
└── script.js     # JavaScript logic
```

---

## ⚙️ How to Run the Project

1. Download or clone the project files.
2. Get a free API key from OpenWeatherMap:

   * Visit https://openweathermap.org/api
   * Create an account
   * Generate your API key.
3. Open the **script.js** file.
4. Replace the API key in the following line:

```javascript
const apiKey = "YOUR_API_KEY";
```

5. Open **1.html** in your browser.
6. Enter a city name and click **Search** to view the weather.

---

## 📊 Example Output

When a user searches for a city, the application displays:

* City Name
* Temperature (°C)
* Weather Description
* Humidity (%)
* Wind Speed (m/s)

It also stores the searched cities in the **Recent Searches** section.
