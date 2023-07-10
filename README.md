# WeatherApp

This command-line tool provides weather-related information for a given city.

## Prerequisites
- .NET Core SDK (version 6.0.403 or higher) [Installation guide](https://dotnet.microsoft.com/download)

## How to Run
1. Clone the repository or download the source code.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the following command to build the application: dotnet build
4. Run the application by executing the following command: dotnet run
5. Enter the name of the city when prompted.


## How to Use
- The application will prompt you to enter the name of a city.
- It will retrieve the latitude and longitude of the city from the provided city data file.
- Using the latitude and longitude, it will fetch the current weather information from the Open-Meteo API.
- The application will display the temperature, wind speed, wind direction, weather code, and time of the weather data for the specified city.

## Configuration
- The city data file (`city_data.json`) should be placed in the same directory as the application.
- Ensure that you have an internet connection to fetch weather data from the Open-Meteo API.










