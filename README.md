# Weather Forecast Visualization

## Overview
This Python script fetches weather forecast data for a specified city using the OpenWeatherMap API and visualizes the temperature trends over time using Matplotlib and Seaborn.

## Features
- Retrieves weather forecast data for the next few hours.
- Extracts temperature values and timestamps.
- Plots a temperature trend graph.

## Requirements
Ensure you have the following dependencies installed before running the script:

```bash
pip install requests matplotlib seaborn
```

## Usage
1. Replace `API_KEY` in the script with your OpenWeatherMap API key.
2. Modify the `CITY` variable to fetch data for a different location.
3. Run the script using Python:

```bash
python weather_forecast.py
```

## Expected Output
- The script fetches temperature data for the next few hours.
- A line graph displays the temperature variation over time.
- If an error occurs, an appropriate message is displayed.

## Configuration
You can customize the following parameters:
- `CITY`: Change the city name to get weather data for a different location.
- `units`: Set to `metric` for Celsius or `imperial` for Fahrenheit.
- `cnt`: Adjust the number of forecast points retrieved.

## API Key
To get an OpenWeatherMap API key:
1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Go to "API Keys" and generate a key.
3. Replace `API_KEY` in the script with your generated key.

## License
This project is licensed under the MIT License.

