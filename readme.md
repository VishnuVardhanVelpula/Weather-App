# 🌤️ Weather App

A simple weather application built using **HTML**, **CSS**, and **JavaScript** that fetches real-time weather data from the **OpenWeatherMap API**.

---

## ✨ Features

- 🔍 Search by city name
- 🌡️ Displays temperature (°C), humidity, and wind speed
- 🗾️ Shows weather condition icons (Clear, Clouds, Rain, etc.)
- 📱 Responsive and user-friendly UI

---

## 🚀 Technologies Used

- HTML
- CSS
- JavaScript (Vanilla JS)
- [OpenWeatherMap API](https://openweathermap.org/api)

---

## 📦 Getting Started

### ✅ Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection
- An API key from [OpenWeatherMap](https://openweathermap.org/api)

### 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Create a config file for your API key:**

   Create a `config.js` file in the project directory and add:

   ```javascript
   // config.js
   const CONFIG = {
     API_KEY: "your_api_key_here"
   };
   ```

   ⚠️ **Important:** Do **not** commit this file to your repo. Add `config.js` to your `.gitignore` file.

3. **Open the app:**

   Open the `index.html` file in a browser:

   ```bash
   open index.html
   ```

---

## 🧪 Usage

1. Enter a **city name** in the input box.
2. Click the **Search** button.
3. Weather details will appear below (or an error message if not found).

---

## 📁 Project Structure

```
weather-app/
├── index.html
├── style.css
├── app.js
├── config.js         <-- Your API key (NOT committed)
└── images/           <-- Weather icons (clouds.png, clear.png, etc.)
```

---

## 🔐 Security Note

This is a frontend-only app for demo purposes. In real-world applications, avoid exposing your API keys on the client side. Use a secure backend to handle API requests.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request with any improvements or bug fixes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/api) for providing free weather data APIs.