# World_Weather_Analysis
The purpose of this project is to plan an itenerary using openWeatherMap API and google maps API.

## How does it work?
1. We are randomly generating a list of 2000 latitudes and longitudes.
2. We are making use of the citypy module to find nearby cities to our list of coordinates.
3. Using the OpenWeather Map API, we are getting all kinds of weather information about these cities like cloudiness, humidity etc.
4. We asking the user to provide minimum and maximum temperatures where they would like to vacation.
5. We are furthur filtering down the cities based on the inputs provided.
6. This list of cities is now fed to the google maps API to find the nearby Hotels. 
7. Once we have all the required information, we are choosing 4 cities  that are in close vicinity to each other and creating Directions maps to give us an idea of our future itenerary.

### Special features
Our maps have markers and information boxes available for ease of use! 
