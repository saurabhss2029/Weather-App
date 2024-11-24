Tech Stack
HTML: Used for creating the structure of the web pages, including the layout and form elements.
CSS: Used for styling the app and making it visually appealing, ensuring that the app looks good on all screen sizes.
JavaScript: Provides the interactive functionality, including fetching and displaying real-time weather data from an API.
API: OpenWeatherMap API (or any other weather API you're using) to retrieve current weather information based on the city entered by the user.
Features
City Search: Users can search for weather information by typing the name of any city.
Real-Time Weather Data: Displays up-to-date weather information, including:
Current temperature (in Celsius or Fahrenheit, depending on user preference)
Humidity level
Wind speed and direction
Weather condition (e.g., clear sky, rainy, cloudy)
Responsive Design: The app adapts to different screen sizes, ensuring it’s fully functional on both desktop and mobile devices.
User-Friendly Interface: Simple and intuitive interface with minimalistic design to make navigation easy.
Error Handling: Displays user-friendly error messages if the city entered doesn't exist or if there's an issue fetching data from the API.
How It Works
User Input: The user enters the name of a city in the search input field and clicks the "Get Weather" button.

API Call: When the button is clicked or Enter is pressed, a JavaScript function is triggered. This function makes an HTTP request to the weather API (e.g., OpenWeatherMap) using the city name provided by the user.

Data Fetching: The API responds with weather data in JSON format, including information such as the temperature, humidity, wind speed, and weather conditions for the requested city.

Display Data: The JavaScript function processes the data and dynamically updates the webpage to display the weather details. The results are displayed in a user-friendly format, and if any error occurs (e.g., invalid city name), an error message is shown.

Responsive Design: The layout adjusts automatically to ensure that the app remains usable across different screen sizes.
