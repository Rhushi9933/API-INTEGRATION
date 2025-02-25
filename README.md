# API-INTEGRATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Gaikwad Rhushabh Navnath

*INTERN ID*: CT6WLNC

*DOMAIN*: Full Stack Web Development

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH

*DISCRIPTION*:

*Weather App – API Integration and Data Display*

  Project Overview:
  
  This project is a simple, interactive weather application that fetches and displays real-time weather data from the OpenWeatherMap API. The application allows users to enter a city name and receive current weather details, including temperature, humidity, wind speed, and weather conditions. The data is dynamically loaded using JavaScript, making the webpage responsive and user-friendly.
  This project demonstrates how to integrate a third-party API into a web application using JavaScript and fetch real-time data. It also emphasizes handling API responses, error messages, and dynamically updating the UI based on user input.
  

Technologies Used

  The project is built using:
  
  •	HTML: For the webpage structure
  
  •	CSS: For styling and responsiveness
  
  •	JavaScript: For API integration, fetching data, and handling user interactions
  
  •	OpenWeatherMap API: To fetch real-time weather data
  

Key Features

  1)	Search Functionality

  •	Users can enter a city name in the input box to get weather details.
  •	A search button triggers an API request to fetch weather data.
  
  3)	Dynamic Data Fetching
    •	Uses the fetch() method to request data from the OpenWeatherMap API.
    •	Data is retrieved in JSON format and parsed to extract relevant weather details.
  
  4)	Weather Details Display
    •	Displays the city name, temperature (in Celsius), humidity percentage, and wind speed (in km/h).
    •	Dynamically updates the weather information when a user enters a new city.
  
  5)	Weather Condition Icons
    •	The app updates the weather icon dynamically based on the weather condition returned by the API.
    •	Different weather conditions like clear, clouds, rain, drizzle, and mist have corresponding images displayed.
  
  6)	Error Handling
    •	If a user enters an invalid city name, an error message is displayed.
    •	The error handling ensures a smooth user experience by preventing crashes and displaying a user-friendly error message.

Code Explanation
  HTML Structure
    The HTML file consists of a simple structure with a search box for user input and a card section displaying weather details. The key elements include:
    •	An input box for city name entry.
    •	A search button with an icon.
    •	A weather display section, including temperature, city name, humidity, and wind speed.
    •	A hidden error message that appears when an invalid city name is entered.

CSS Styling
  The external CSS file (style.css) is linked to ensure a responsive and visually appealing design. The CSS styles the search bar, weather details, and overall card layout to create a clean and professional look.

JavaScript Functionality
  •	API Integration: The OpenWeatherMap API is accessed using an API key. The base URL is defined:
      const apiKey = "c2521633d7cff346ae1e45697fd01dd2";
      const apiUrl = "http://api.openweathermap.org/data/2.5/weather?&units=metric&q=";
  •	Fetching Data: The checkWeather(city) function makes an asynchronous request to the API and retrieves weather details in JSON format.
  •	Error Handling: If an invalid city is entered, an error message is displayed, and weather details are hidden.
  •	Updating UI: Extracted weather data updates the HTML elements dynamically using JavaScript.
  •	Weather Icons: A series of conditional checks ensure that the correct weather icon is displayed based on the weather condition.

Event Handling
  An event listener is attached to the search button:
      searchBtn.addEventListener("click", ()=>{checkWeather(searchBox.value);})
  When the button is clicked, the app fetches and updates the weather data accordingly.

Conclusion
  This project effectively demonstrates API integration, dynamic data handling, and front-end development techniques. It is a useful beginner-friendly project for learning JavaScript, working with APIs, and improving UI/UX with real-time data updates. The Weather App can be further enhanced by adding features such as geolocation-based weather detection, extended forecasts, and improved UI animations.


#OUTPUT
![Image](https://github.com/user-attachments/assets/d1dc5bb8-943d-428e-ab0d-e82da948f926)
![Image](https://github.com/user-attachments/assets/958bcbb3-9808-4fc6-b65f-1ce648c2a517)
