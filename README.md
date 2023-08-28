Weather Application
Table of Contents
Introduction
Features
User Interface
Weather Data
Getting Started
Prerequisites
Installation
Usage
API Key
Contributing
License
Introduction
The Weather Application is a simple web-based tool that enables users to quickly check the weather conditions for various cities. It fetches real-time weather data from the OpenWeatherMap API and presents it in an easy-to-understand format.

Features
User Interface
Clean and intuitive user interface.
Responsive design for seamless usage on different devices and screen sizes.
Background image changes based on the current weather conditions to create a visually engaging experience.
Stylish fonts from Google Fonts to enhance the overall appearance.
Weather Data
Retrieves weather data using the OpenWeatherMap API.
Displays the following information for the searched city:
City name and country code.
Current temperature in Celsius.
Weather type (e.g., Cloudy, Rainy, Clear Sky).
Temperature range (minimum and maximum) for the day.
Getting Started
Prerequisites
Web browser (Google Chrome, Mozilla Firefox, Safari, etc.)
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/Spar1001/weather-app.git
Navigate to the project directory:
bash
Copy code
cd weather-app
Open the index.html file in your web browser to use the application.
Usage
Enter the name of a city in the search input and press Enter or click the "Search" button.
The weather data for the specified city will be fetched and displayed on the page.
Enjoy the real-time weather information and the dynamic background image!
API Key
To fetch weather data, this application uses the OpenWeatherMap API. You need to obtain an API key by following these steps:

Sign up on the OpenWeatherMap website.
Navigate to your account settings and generate a new API key.
Replace the placeholder API key in the weather.js file with your actual API key.
javascript
Copy code
const api_details = {
    url: "http://api.openweathermap.org/data/2.5/",
    api_key: "YOUR_API_KEY"
};
Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or improvements, feel free to submit a pull request.

License
This project is licensed under the MIT License.
