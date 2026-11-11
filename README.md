# Async-Weather-Tracker

🌤️ Async Weather Tracker

<img width="1919" height="1079" alt="Screenshot 2026-03-05 101426" src="https://github.com/user-attachments/assets/7e630427-af89-4d1c-95aa-01f5df9d3d18" />
<img width="1919" height="1079" alt="Screenshot 2026-03-05 101439" src="https://github.com/user-attachments/assets/fa75352e-39d0-4f7b-bdd5-cebe87d282f7" />

An asynchronous weather tracking web application built using HTML, CSS, and JavaScript that fetches real-time weather data from the OpenWeatherMap API.

The application demonstrates the JavaScript Event Loop, Promises, Async/Await, and Local Storage while providing a functional weather search interface.

📌 Project Overview

Async Weather Tracker allows users to search for a city and instantly view its current weather conditions.

The project also visually demonstrates how JavaScript handles asynchronous operations by logging events such as:

Synchronous execution

Promise microtasks

setTimeout macrotasks

API fetch requests

This makes the project both a functional weather application and a learning tool for JavaScript asynchronous behavior.

⚙️ Features
🌍 City Weather Search

Users can enter a city name and retrieve real-time weather information including:

Temperature

Weather condition

Humidity

Wind speed

Country location

🧠 Event Loop Demonstration

The application logs JavaScript execution order inside the Console – Event Loop section, showing:

Sync operations

Promise microtasks

setTimeout macrotasks

Async API responses

📜 Search History

Stores previously searched cities using Local Storage

Displays the last 8 searched cities

Users can click a previous city to search again instantly

⚠️ Error Handling

The application handles:

Invalid city names

Network errors

API failures

🛠️ Technologies Used
Technology	Purpose
HTML5	Structure of the web page
CSS3	Styling and responsive layout
JavaScript (ES6+)	Application logic
Fetch API	Fetching weather data
Async/Await	Handling asynchronous operations
Local Storage	Saving search history
OpenWeatherMap API	Real-time weather data

🔑 API Used

This project uses the OpenWeatherMap API to retrieve real-time weather data.

API Endpoint Example:

https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric

You need your own API key from:

https://openweathermap.org/api

▶️ How to Run the Project

Clone the repository

git clone https://github.com/your-username/async-weather-tracker.git

Open the project folder

Open index.html in your browser

Enter a city name and click Search

🧠 Concepts Demonstrated

This project demonstrates several core JavaScript concepts:

Event Loop

Microtasks vs Macrotasks

Promises

Async/Await

Fetch API

DOM Manipulation

Local Storage

📸 Application Sections

The application contains four main sections:

Search City – Input field for city search

Search History – Previously searched cities

Weather Info – Displays weather data in table format

Console – Event Loop – Shows execution order of asynchronous operations


👨‍💻 Author

Rahul Kumar

B.Tech Student – Artificial Intelligence & Machine Learning

📜 License

This project is for educational and learning purposes.
