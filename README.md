🌤️ Multi-Page Weather System

A multi-page weather application built using vanilla JavaScript, HTML, and CSS.
This project demonstrates authentication flow, API integration, local storage usage, and responsive UI design — without any frameworks.

🔗 Live Demo: https://codebyniranjan.github.io/weatherapp/

✨ Features
🔐 Authentication

User Registration & Login

Client-side validation

Session handling with localStorage

Protected navigation

🌦️ Weather System

Real-time current weather

5-day forecast

Weather alerts system

Geolocation support

Search history tracking

⚙️ Customization

Dark mode toggle

Default city setting

°C / °F temperature switch

Alert preferences

🧰 Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6+)

API: OpenWeatherMap

Storage: localStorage

Design: Responsive Mobile-First UI

Architecture: Multi-Page Vanilla JS (No frameworks)

📁 Project Structure
weather-system/
│
├── index.html        # Home (Current Weather)
├── login.html        # Login Page
├── register.html     # Registration
├── forecast.html     # 5-Day Forecast
├── history.html      # Search History
├── alerts.html       # Weather Alerts
├── settings.html     # User Settings
├── about.html        # Documentation
│
├── css/
│   ├── main.css
│   ├── auth.css
│   └── weather.css
│
└── js/
    ├── auth.js
    ├── weather.js
    ├── settings.js
    ├── history.js
    └── navbar.js

🚀 Quick Start
1️⃣ Clone Repository
git clone https://github.com/Kesav005-coder/Weather_app.git
cd Weather_app

2️⃣ Run Local Server
VS Code Live Server

Right-click login.html → Open with Live Server

Python
python -m http.server 8000

Node
npx http-server

3️⃣ Open App
http://localhost:8000/login.html

📄 Pages Overview
Page	Purpose
login.html	User authentication
register.html	New account creation
index.html	Current weather
forecast.html	Extended forecast
history.html	Search history
alerts.html	Weather warnings
settings.html	User preferences
about.html	Documentation
🎓 Academic Concepts Demonstrated

✅ Authentication logic
✅ Fetch API & async/await
✅ DOM manipulation
✅ JSON data handling
✅ Responsive CSS (Grid & Flexbox)
✅ Event-driven JavaScript
✅ Client-side state management

🌐 API Usage
Base URL
https://api.openweathermap.org/data/2.5

Endpoints
/weather?q={city}&appid={API_KEY}
/forecast?q={city}&appid={API_KEY}
/weather?lat={lat}&lon={lon}&appid={API_KEY}

🎨 Customization
Change API Key

Edit:

js/weather.js

const WEATHER_CONFIG = {
  API_KEY: "YOUR_API_KEY"
};

Theme Colors

Modify CSS variables in:

css/main.css

🐛 Troubleshooting

401 Error → Invalid API Key
404 Error → Wrong City Name
429 Error → API Rate Limit

If UI breaks:

Ctrl + F5 (Hard Refresh)

🔒 Security Notice

⚠️ This is an educational project.

Passwords stored in localStorage

API key exposed client-side

No backend authentication

Do not use in production.

🚀 Future Improvements

Node.js + Express backend

Database integration

JWT Authentication

Weather Maps & Radar

Progressive Web App (PWA)

Push Notifications

📝 License

Academic project — free to use for learning and submissions.

👨‍💻 Author

Kesav Kishore
GitHub: https://github.com/Kesav005-coder

⭐ If you like this project, consider starring the repository!
