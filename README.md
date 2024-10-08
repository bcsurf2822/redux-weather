# Redux Weather

## Project Overview

Fetch and display a 5-day weather forecast using the OpenWeather API using React and Redux Toolkit to showcase data fetching and state management for a 5-day forecast. Displays temperature, pressure, and humidity data for a specified city.

## Features

- **Search Functionality**:
  - Submits a request to fetch weather data from the OpenWeather API upon form submission.
- **Weather Data Display**:
  - The `WeatherView` component maps through the fetched weather data and displays temperature, pressure, and humidity trends using Bootstrap-styled containers.
  - Uses `Sparklines` to visualize trends for the next 5 days.
- **State Management**:
  - Implements Redux Toolkit's `createSlice` and `createAsyncThunk` to manage the application state and handle asynchronous API calls.
  - Stores weather data for up to 5 cities, including temperature highs/lows, pressure, and humidity.

## Technologies Used

- **Frontend**:
  - **React**
  - **Redux Toolkit**
  - **Bootstrap**
  - **Sparklines**
- **API**: [OpenWeather API](https://openweathermap.org/api)

## Parsity

This project has been created by myself, Ben Corbett, while at Parsity, an online software engineering course. The work in this repository is wholly of the student based on a sample starter project that can be accessed by looking at the repository that this project forks.

If you have any questions about this project or the program in general, visit parsity.io or email hello@parsity.io.
