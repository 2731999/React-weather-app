# Weather App

![Capture](https://github.com/2731999/React-weather-app/assets/101728039/7e314f41-52bd-470b-a303-8cde9256f28d)

A simple Weather App built using React and Axios to fetch weather data from the OpenWeatherMap API and display it to the user.

## Features

- User can enter a city name and click the "Search" button to fetch weather data for that city.
- Weather data includes the city name and the current temperature in Celsius.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Axios: A popular HTTP client for making API requests.
- Bootstrap: A CSS framework for responsive web design.

## How to Run

1. Clone the repository to your local machine.
2. Install the required dependencies by running `npm install` in the project directory.
3. Obtain an API key from OpenWeatherMap by signing up for a free account at https://openweathermap.org/api.
4. Replace the `apiKey` variable in `App.js` with your API key.
5. Start the development server by running `npm start`.
6. Open your web browser and navigate to `http://localhost:3000` to see the Weather App.

## API Usage

The app uses the OpenWeatherMap API to fetch weather data. The API documentation can be found at https://openweathermap.org/current.

## Limitations

- As the app makes API requests from the client-side, CORS issues may occur. It is recommended to set up a server-side proxy to handle API requests to avoid these issues in a production environment.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request.

