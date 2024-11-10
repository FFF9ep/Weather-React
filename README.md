# ☀️🌧️ Weather App 🌎

Welcome to the **Weather App**! This 🌐 app lets users 🔍 search for current 🌤️ weather in any 🏙️ city, providing details like 🌡️ temperature, 💧 humidity, and 🌬️ wind speed with a smooth and attractive interface.

---

## 📚 Table of Contents
- [📜 Introduction](#introduction)
- [✨ Features](#features)
- [💻 Technologies Used](#technologies-used)
- [⚙️ Installation](#installation)
- [🛠️ Usage](#usage)
- [🗂️ Project Structure](#project-structure)
- [🤝 Contributing](#contributing)
- [📄 License](#license)

---

## 📜 Introduction
This React-based Weather App 🌦️ provides real-time weather data for various 🌍 locations by integrating with the OpenWeatherMap API. It features a responsive 🖥️ design and displays data such as 🌡️ temperature, weather icons, 💧 humidity, and 🌬️ wind speed, ensuring an engaging user experience.

---

## ✨ Features
- **🔍 Search Functionality**: Users can input any 🏙️ city name to get current weather details.
- **🌡️ Weather Information**: Displays temperature, 💧 humidity, 🌬️ wind speed, and 🏙️ city location.
- **🌥️ Weather Icons**: Adapts based on current conditions.
- **📱 Responsive Design**: Works well on various devices.

---

## 💻 Technologies Used
- **⚛️ React**: Frontend framework for the UI.
- **🎨 CSS**: Styling for an attractive UI.
- **🌐 OpenWeatherMap API**: Provides real-time weather data.

---

## ⚙️ Installation
Follow these steps to get the project up and running locally:

1. **📥 Clone the repository**:
   ```bash
   git clone https://github.com/FFF9ep/Weather-React.git
   ```

2. **📂 Navigate to the project directory**:
   ```bash
   cd Weather-React
   ```

3. **📦 Install dependencies**:
   ```bash
   npm install
   ```

4. **📝 Create an `.env` file** in the root directory and add your API key:
   ```env
   VITE_APP_ID = "your_api_key_here"
   ```
   Replace `your_api_key_here` with your actual API key from [🌐 OpenWeatherMap](https://openweathermap.org/api).

5. **▶️ Run the application**:
   ```bash
   npm run dev
   ```

6. **🌐 Access the app** at [http://localhost:5173](http://localhost:5173).

---

## 🛠️ Usage
- **Initial View**: The app initially shows weather for “Swiss” 🇨🇭.
- **🔎 Searching for a City**:
  - Enter a city name in the 🔍 search bar.
  - Click the 🔍 icon to fetch weather data.
- **Displayed Data**:
  - 🌡️ Temperature (°C)
  - 🏙️ City location
  - 🌥️ Weather icon
  - 💧 Humidity percentage
  - 🌬️ Wind speed (Km/h)

---

## 🗂️ Project Structure
```plaintext
weather-app/
│
├── public/
│   └── assets/        # 🌥️ Contains weather icons
│
├── src/
│   ├── components/
│   │   └── Weather.jsx   # 📦 Main component for displaying weather
│   ├── App.jsx           # 🏗️ Main app file
│   ├── main.jsx          # 🚪 Entry point
│   └── index.css         # 🎨 Global CSS styling
│
├── .env                  # 🔑 Environment variables (API key)
├── package.json          # 📦 Project metadata
└── README.md             # 📄 Project documentation
```

---

## 🤝 Contributing
Contributions are welcome! 🙌 Feel free to open issues or submit pull requests to improve the project.

**Steps to Contribute**:
1. 🪝 Fork the repo.
2. Create a new 🆕 branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a 📝 Pull Request.

---

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### 🌟 Enjoy exploring the weather around the globe with the Weather App!

