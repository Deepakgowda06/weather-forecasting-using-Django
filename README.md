# Weather Dashboard 🌦️

A weather dashboard application that fetches and displays real-time weather data using the OpenWeather API. The app provides users with a user-friendly interface featuring interactive charts and maps to visualize weather trends in their selected location. The backend is powered by Django to handle API requests and serve data efficiently.

## Features 🚀

- **Real-time Weather Data**: Fetches current weather information from the OpenWeather API.
- **Interactive Visualizations**: Displays temperature, humidity, wind speed, and more through easy-to-understand charts and graphs.
- **Dynamic Map Integration**: Visualize weather data on a map for selected regions or cities.
- **User-Friendly Interface**: Simple and intuitive UI designed for a smooth user experience.
- **REST API Integration**: Real-time data updates using OpenWeather API’s REST endpoints.
- **Backend Powered by Django**: A robust and scalable backend architecture built with Django.

## Technologies Used 🛠️

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django (Python), Django REST Framework
- **API**: [OpenWeather API](https://openweathermap.org/api)


## Installation & Setup 💻

### Create and activate a virtual environment:

#### On MacOS/Linux/Windows:
```bash
python3 -m venv venv
source venv/bin/activate
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Deepakgowda06/weather-forecasting-using-Django
   cd weather-dashboard
2. **Migrate the database**:
   ```bash
    python manage.py migrate
3. **Start the Django development server**:
  ```bash
    python manage.py runserver
