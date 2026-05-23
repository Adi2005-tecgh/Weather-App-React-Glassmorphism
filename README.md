# 🌤️ GlassCast — Glassmorphism Weather App

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS-Glassmorphism-1572B6?logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A visually stunning weather app built with **React.js** featuring a **Glassmorphism UI** and **dynamic Star Wars–themed backgrounds** that shift automatically based on real-time temperature and weather conditions.

---

## ✨ Features

- **Live Weather Data** — Fetches real-time temperature, humidity, wind speed, and conditions via the OpenWeatherMap API
- **Auto Location Detection** — Uses the browser's Geolocation API to detect your current city on load
- **Dynamic Backgrounds** — Background changes automatically based on weather type (Stormy, Foggy, Freezing, Hot, etc.) using iconic Star Wars planet imagery
- **Glassmorphism UI** — Frosted-glass card design with blur effects and clean typography
- **City Search** — Search any city worldwide and get instant results
- **Responsive Design** — Clean centered layout that works across screen sizes

---

## 🌍 Weather → Background Mapping

| Condition | Type | Planet Background |
|-----------|------|-------------------|
| Rain / Thunderstorm | Stormy | Kamino |
| Mist / Fog | Foggy | Endor |
| ≤ 2°C | Freezing | Hoth |
| ≤ 13°C | Chilly | Naboo (Warmer) |
| ≤ 18°C | Moderate | Coruscant (Night) |
| ≤ 22°C | Warm | Scarif |
| ≤ 26°C | Hot | Tatooine |
| ≤ 32°C | Very Hot | Bespin |
| > 32°C | Scorching | Kashyyyk |

---

## 🛠️ Tech Stack

- **Frontend** — React.js (Functional Components, Hooks)
- **Styling** — Custom CSS with Glassmorphism effects, Google Fonts (Inter, Orbitron)
- **API** — [OpenWeatherMap](https://openweathermap.org/) REST API
- **Location** — Browser Geolocation API

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- A free API key from [OpenWeatherMap](https://openweathermap.org/api)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/glasscast.git
   cd glasscast
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure your API key**

   Open `src/WeatherApp.jsx` and replace the placeholder:
   ```javascript
   const API_KEY = "YOUR_OPENWEATHERMAP_API_KEY_HERE";
   ```

4. **Add background images**

   Place your planet images inside `public/images/` with these exact filenames:
   ```
   public/
   └── images/
       ├── kamino.png
       ├── endor1.jpg
       ├── hoth.jpg
       ├── Naboo-warmer.jpg
       ├── coruscant-night.jpg
       ├── Scariff.jpg
       ├── tatooine.jpg
       ├── bespin.jpg
       └── kashyyk.jpg
   ```

5. **Run the app**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
glasscast/
├── public/
│   ├── images/          # Planet background images
│   └── index.html
├── src/
│   ├── WeatherApp.jsx   # Main component — logic, API calls, weather mapping
│   ├── WeatherUi.css    # Glassmorphism styles
│   ├── App.jsx
│   └── main.jsx
├── Output/              # Screenshots
├── package.json
└── README.md
```

---

## 📸 Screenshots

| Moderate | Hot | Foggy |
|----------|-----|-------|
| ![Moderate](Output/image-1.png) | ![Hot](Output/image-1.png) | ![Foggy](Output/image-2.png) |

| Stormy | Warm | Very Hot |
|--------|------|----------|
| ![Stormy](Output/image-3.png) | ![Warm](Output/image-4.png) | ![Very Hot](Output/image-5.png) |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Arshiya Attar**

- GitHub: [@iamarshiya](https://github.com/iamarshiya)
- LinkedIn: [Arshiya Attar](https://www.linkedin.com/in/arshiya-attar-91b4ab2b5/)
