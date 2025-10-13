
# 🌦️ Weather App

A simple and interactive Weather App that allows users to get real-time weather information for any city using the OpenWeatherMap API. The app is built using HTML, CSS, and JavaScript.

# 📋 Table of Contents

-  Introduction

-  Features

- Demo

- Installation

- Usage

- Configuration

- Dependencies

- Project Structure

- Troubleshooting

- Contributors

- License

# 💡 Introduction

This project is a client-side web application that fetches weather data from the OpenWeatherMap API based on the user’s input city. It displays the current temperature, weather condition, and location in a clean, minimal interface.

# ✨ Features

Fetches live weather data using the OpenWeatherMap API

Displays temperature and weather description

Simple and responsive design

Error handling for invalid or empty city input

Lightweight and easy to deploy

# 🧠 Demo

Enter a city name, click “Get Weather”, and view real-time temperature and conditions.

Example:

City: London  
→ Temperature: 15°C  
→ Weather: Scattered Clouds

# ⚙️ Installation

Clone this repository:

git clone https://github.com/your-username/weather-app.git


Navigate into the project folder:

cd weather-app


Open index.html in your browser directly or using a local server (e.g., Live Server in VS Code).

# 🚀 Usage

Open the index.html file.

Enter a city name into the text input field.

Click the Get Weather button.

The app will display the current weather for the city.


# 📦 Dependencies

This project uses:

OpenWeatherMap API for weather data

Standard web technologies (HTML5, CSS3, JavaScript)

No external libraries or frameworks are required.

# 🧩 Project Structure
weather-app/\
|
├── index.html        # Main HTML structure\
├── script.js         # JavaScript logic for fetching and displaying weather data\
├── style.css         # Styling for the UI\

# 🖼️ Screenshots

Main Interface:

            +-------------------------------------------+
            |               Weather App                 |
            |                                           |    
            |  Enter City: [_________] [Get Weather]    |
            |                                           |
            |  London, GB                               |
            |  Temperature: 15°C                        |
            |  Weather: Scattered Clouds                |
            +-------------------------------------------+

# 🛠️ Troubleshooting
| Issue                       | Possible Cause               | Solution                                    |
| --------------------------- | ---------------------------- | ------------------------------------------- |
| “City not found” alert      | Invalid city name            | Check spelling or try another city          |
| “Please enter a city” alert | Empty input field            | Enter a valid city name                     |
| No weather displayed        | API key missing or incorrect | Replace with a valid OpenWeatherMap API key |

# 👥 Contributors

[Swapnil Gupta] – Developer

# 🪪 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this software with attribution.
