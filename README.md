# 🌦 Advanced Weather Website (Flask)

A modern full-stack weather website built using Python Flask that provides real-time weather data, location-based forecasts, charts, and air quality information.

---

## 🚀 Features

- 🌍 Live weather using current location (Geolocation)
- 🔍 Search weather by city name
- 🌡 Temperature, humidity, wind speed
- 🌫 Air Quality Index (PM2.5)
- 📊 7-day temperature trend graph (Chart.js)
- 🗺 Location view using Google Maps
- 🌙 Dark mode toggle
- ⏳ Loading spinner

---

## 🛠 Tech Stack

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, JavaScript
- **API:** WeatherAPI
- **Charts:** Chart.js
- **Maps:** Google Maps Embed

---

## 📁 Project Structure
weather-website/
│


├── app.py


├── templates/


│ └── index.html


├── static/


│ ├── style.css


│ └── script.js

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
git clone https://github.com/your-username/advanced-weather-website-flask.git

### 2️⃣ Navigate to project folder
cd advanced-weather-website-flask
### 3️⃣ Install dependencies

pip install flask requests


### 4️⃣ Run the project

python app.py


### 5️⃣ Open in browser

http://127.0.0.1:5000


---

## 🔑 API Key Setup

This project uses WeatherAPI.

- Get free API key from: https://www.weatherapi.com/
- Replace in `app.py`:

API_KEY = "your_api_key_here"


OR set environment variable:

set WEATHER_API_KEY=your_api_key_here


---

## 📸 Screenshots

(Add screenshots of your project UI here)

---

## ⚠️ Important Notes

- Location feature works only with:
  - localhost ✅
  - HTTPS (when deployed)
- This project is for educational purposes
- Do not expose API key publicly in production

---

## 🚀 Future Improvements

- 📱 Mobile app version
- 📊 More detailed graphs (humidity, wind)
- 🌍 Multi-city comparison
- ☁ Deployment on cloud (Render / Railway)

---

## 👨‍💻 Author

**Karan Mohanty (B.Tech CST 2nd Year Student)**  
Odisha, India

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
