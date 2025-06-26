# Weather-App
Here’s a professional and clear `README.md` file you can use for your weather app GitHub repository, based on the provided HTML, CSS, and weather PNG files:

---

# 🌦️ Weather App

A clean and simple weather app built using **HTML**, **CSS**, and **JavaScript**. It fetches real-time weather data using the **OpenWeatherMap API** and displays information such as temperature, humidity, wind speed, and weather conditions with corresponding icons.

## 📸 Preview

![image](https://github.com/user-attachments/assets/0138f0e3-ea5b-456e-b038-a799c3f7ec1b)

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature in Celsius
* 💧 Shows humidity and wind speed
* 🌤️ Dynamic weather icons (e.g., rain, clouds, clear sky)
* 🔍 Minimal and responsive design

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **API:** [OpenWeatherMap](https://openweathermap.org/api)

---

## 🔧 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate into the project directory:

   ```bash
   cd weather-app
   ```

3. Open `1.html` in your browser.

> 💡 Make sure to keep the `images/` folder in the same directory as the HTML file and include all required PNGs like:
>
> * `search.png`
> * `rain.png`
> * `clouds.png`
> * `clear.png`
> * `drizzle.png`
> * `mist.png`
> * `humidity.png`
> * `wind.png`

---

## 🔑 API Key Setup

This app uses OpenWeatherMap's free API. Replace the API key in the script section of `1.html`:

```javascript
const apiKey = "your_api_key_here";
```

You can get your API key by signing up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

---

## 🐛 Known Issues

* `"Rainr"` typo in `if` condition. It should be `"Rain"` for the rain icon to show correctly:

  ```javascript
  else if(data.weather[0].main == "Rain"){  // Not "Rainr"
      weatherIcon.src = "images/rain.png";
  }
  ```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you want me to generate a custom preview image, fix the Rainr bug in code, or create an improved version of your UI!
