# Weather App Django Project

A simple and functional weather web application built with Python and Django. This app allows users to search for current weather information of any city with a clean interface.

---

🚀 **Features**

* ✅ Search weather by city name
* ☁️ Displays weather icon (e.g., clouds, sun) representing current conditions
* 📅 Shows the current date alongside weather details
* 📸 Fetches and shows relevant weather images automatically
* 🔍 Uses Google’s Programmable Search Engine to retrieve weather-related images
* 🧼 Clean and minimal UI with responsive design (Bootstrap optional)
* 📦 Easily deployable to cloud platforms

---

🛠️ **Tech Stack**

* **Backend:** Django (Python)
* **Database:** SQLite (default) – no persistent data storage needed
* **Frontend:** Django Templates + HTML/CSS
* **API:** OpenWeatherMap API for weather data (including weather icons)
* **Image Search:** Google Programmable Search Engine API for weather images

---

📁 **Project Structure (Descriptive Format)**

Main Django app: **weather\_app** – Handles all weather-related features:

 views.py
  Fetches weather data (temperature, weather description), current date, and weather icons from OpenWeatherMap API, and passes them to templates.

 urls.py
  Routes URLs to views for the home page and search results.

 templates/
  Contains HTML templates that display weather info along with cloud/sun icons and date dynamically.

 static/
  Holds CSS and JavaScript files for the clean UI and responsiveness.
