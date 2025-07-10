# Weather Forecast Web Application

A clean, modern, and responsive web application that provides users with real-time weather forecasts. Users can search for a city to get the current weather conditions as well as a 5-day forecast.

## ✨ Features

* **Current Weather:** Get up-to-the-minute weather data for any city, including temperature, humidity, wind speed, and a descriptive summary.
* **5-Day Forecast:** View the weather forecast for the next five days, helping you plan your week ahead.
* **City Search:** Easily search for any city in the world to get its weather information.
* **Responsive Design:** A mobile-first design ensures the application looks and works great on all devices, from desktops to smartphones.
* **Dynamic Icons:** Weather conditions are represented by intuitive and dynamic icons.

## 🛠️ Technologies Used

* **Frontend:**
    * HTML5
    * CSS3 (with Flexbox/Grid for layout)
    * JavaScript (ES6+)
* **API:**
    * [OpenWeatherMap API](https://openweathermap.org/api) for fetching weather data.

## ⚙️ Installation

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Horth168/weather-forecast-webapp.git](https://github.com/Horth168/weather-forecast-webapp.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd weather-forecast-webapp
    ```

3.  **Open `index.html` in your browser:**
    You can simply double-click the `index.html` file, or use a live server extension in your code editor (like Live Server for VS Code) for a better development experience with hot reloading.

## 🔑 API Key Configuration

This project requires an API key from OpenWeatherMap to fetch weather data.

1.  **Get your API Key:**
    * Go to [OpenWeatherMap](https://openweathermap.org/appid) and create a free account.
    * Navigate to the 'API keys' tab in your account dashboard to find your default key.

2.  **Configure the API Key:**
    * In the project's `script.js` file, find the following line:
        ```javascript
        const apiKey = 'YOUR_API_KEY';
        ```
    * Replace `'YOUR_API_KEY'` with the actual API key you obtained from OpenWeatherMap.

## 🚀 Usage

Once the project is set up and the API key is configured:

1.  Open the `index.html` file in your web browser.
2.  The application will either ask for your location or show a default city's weather.
3.  Use the search bar to type in the name of a city you want to check.
4.  Press Enter or click the search button.
5.  The current weather and the 5-day forecast for the selected city will be displayed.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  **Fork the Project**
2.  **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the Branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

Don't forget to give the project a star! Thanks again!

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information. (Note: You may need to add a `LICENSE` file to your repository).

---

> GitHub: [@Horth168](https://github.com/Horth168)
