
# Weather App

This is a simple weather application that allows users to search for the current weather of any city. It fetches data from the OpenWeatherMap API and displays weather conditions like temperature, humidity, wind speed, and an appropriate weather icon.

## Features

- Search for the weather by city name
- Displays temperature, humidity, wind speed, and weather conditions
- Dynamic background and weather icon based on the weather condition
- Responsive design for mobile, tablet, and desktop screens

## Tech Stack

- HTML5, CSS3, JavaScript
- OpenWeatherMap API
- Font Awesome for icons

## Prerequisites

Before running the project, make sure you have the following tools installed:

- A modern web browser
- Internet connection to fetch data from the API

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Weather-app.git
```

2. Navigate to the project directory:

```bash
cd Weather-app
```

3. Open the `index.html` file in your preferred web browser.

4. In the search box, enter a city name and click the search button to fetch the weather information.

## API Integration

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data.

You can replace the API key in the JavaScript file if needed:

```js
const apiKey = "your-api-key-here";
```

Make sure to get your API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and replace it in the script.

## File Structure

```bash
.
├── index.html           # Main HTML file
├── style.css            # Stylesheet
├── script.js            # JavaScript file for fetching weather data and UI interaction
└── images/              # Contains weather condition images
```


## Future Enhancements

- Add forecast for the next few days
- Show weather for the current location using geolocation
- Improve error handling for invalid city names

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own projects.

---

