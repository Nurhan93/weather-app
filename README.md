# weather-app
This is my screen shot for my app by using WeatherAPI 
https://openweathermap.org/appid




https://user-images.githubusercontent.com/26325414/189605851-30e917ca-933c-484d-b503-7910d2c99136.mov





i used a clean archticture for this app that contain 2 layers:

# App Architecture

# Data Layer

The data layer contains a single weather repository that is used to fetch weather data from the OpenWeatherMap API.

The data is then parsed (using Freezed) and returned using type-safe entity classes (Weather and Forecast).

# Presentation Layer

This layer holds all the widgets, along with their controllers.

Widgets do not communicate directly with the repository.

Instead, they watch some controllers that extend the StateNotifier class (using Riverpod).

This allows to map the data from the layer above to AsyncValue objects that can be mapped to the appropriate UI states (data, loading, error).

# Supported Features

 1- Current weather (condition and temperature) 
 2- 5-day weather forecast 
 3- Search by city 


