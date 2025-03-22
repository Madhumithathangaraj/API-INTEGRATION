# API-INTEGRATION
"COMPANY": CODTECH IT SOLUTION
"NAME':MADHUMITHA T
INTERN ID":CTO4WG146
"DOMAIN":FULL STACK WEB DEVELOPMENT
"DURATION":4 WEEKS
"MENTOR":NEELS SANTHOSH
Overview
This code is a webpage that allows users to fetch and display weather data for a specific city using the OpenWeatherMap API. It consists of:

HTML: Structure of the webpage.

CSS: Styling for the webpage.

JavaScript: Logic to fetch data from the API and display it dynamically.

HTML Structure
The HTML defines the structure of the webpage:

Input Field: A text input (<input>) where users can enter a city name.

Button: A button (<button>) to trigger the API request when clicked.

Containers:

#weatherData: Displays the fetched weather data.

#error: Displays error messages if something goes wrong.

CSS Styling
The CSS styles the webpage to make it visually appealing:

Body: Sets a clean font, padding, and background color.

Container: Centers the content, adds padding, and applies a box shadow for a card-like appearance.

Input and Button: Styles the input field and button for a modern look.

Weather Data Container: Adds padding, background color, and borders to the weather data display area.

Error Message: Styles error messages in red and bold.

JavaScript Logic
The JavaScript handles the interaction with the API and updates the DOM dynamically:

Event Listener:

Attaches a click event listener to the "Get Weather" button.

When the button is clicked, the script fetches weather data for the city entered by the user.

API Request:

Constructs the API URL using the city name and API key.

Uses the fetch API to send a request to the OpenWeatherMap API.

Data Handling:

If the API request is successful, the response is parsed as JSON.

The weather data (e.g., temperature, weather description, humidity, wind speed) is extracted and displayed in the #weatherData container.

Error Handling:

If the API request fails (e.g., due to an invalid city name or network error), an error message is displayed in the #error container.

Key Features
Dynamic Data Fetching:

The webpage fetches real-time weather data from the OpenWeatherMap API based on user input.

User-Friendly Interface:

The input field and button make it easy for users to interact with the app.

The weather data is displayed in a clean and readable format.

Error Handling:

If the user enters an invalid city name or the API request fails, an error message is displayed to guide the user.

Responsive Design:

The webpage is styled to look good on both desktop and mobile devices.

How It Works
The user enters a city name (e.g., "London") in the input field.

The user clicks the "Get Weather" button.

The JavaScript sends a request to the OpenWeatherMap API with the city name.

The API responds with weather data for the specified city.

The JavaScript processes the response and displays the data (e.g., temperature, weather description) in the #weatherData container.

If there’s an error (e.g., invalid city name or API issue), an error message is displayed in the #error container.

Example Output
If the user enters "Paris" and clicks the button, the output might look like this:

Copy
Weather in Paris, FR
Temperature: 18°C
Weather: Cloudy
Humidity: 70%
Wind Speed: 5.2 m/s
Code Breakdown
HTML
Defines the structure of the webpage, including input fields, buttons, and containers for displaying data and errors.

CSS
Styles the webpage to make it visually appealing and user-friendly.

JavaScript
Handles user interaction, fetches data from the API, and updates the DOM dynamically.

Potential Improvements
Autocomplete for City Names:

Add an autocomplete feature to help users select valid city names.

Loading Spinner:

Display a loading spinner while the API request is in progress.

Local Storage:

Save the user’s last searched city in local storage for convenience.

Multiple APIs:

Integrate additional APIs (e.g., news, movies) to make the app more versatile.
