# weather-app
this is my screen shot for my app 
![Screen Shot 2022-08-27 at 9 52 34 AM](https://user-images.githubusercontent.com/26325414/187028729-88273174-674a-4b22-b443-a643a126673f.png)

i used a clean archticture for this app that contain 2 layers:
Data Layer

The data layer contains a single weather repository that is used to fetch weather data from the OpenWeatherMap API.

The data is then parsed (using Freezed) and returned using type-safe entity classes (Weather and Forecast).

For more info about this, read this tutorial:

Flutter App Architecture: The Repository Pattern
