# Weather Update Site

## Project Overview

The Weather Update Site is a Django-based web application that allows users to check the current weather for various cities. It fetches real-time weather data and displays temperature, humidity, and other weather conditions in an easy-to-read format.

## Features

1. Search Weather by City: Enter any city to get real-time weather updates.
   
2. Live Weather Data: Fetches accurate weather details using an API.
   
3. User-Friendly Interface: Simple and interactive UI for a smooth experience.
   
4. Built with Django: A powerful web framework for easy scalability.

## Tech Stack
1. Python
2. Django
3. Weather API(openweathermap)
4. HTML
   

## Installation & Setup

### Prerequisites

Ensure you have Python 3.8+ and Django installed.

### Steps to Run the Project
**1. Clone the repository**
git clone https://github.com/Dipti-24/Weather-Update-Site.git  

cd Weather-Update-Site  
**2. Install dependencies**
pip install -r requirements.txt  
**3. Run migrations**
python manage.py migrate  
**4. Start the Django server**
python manage.py runserver  
**5.Access the application**
Open your browser 

## Working

1. User Inputs City Name: The user enters a city name in the search bar.

2. Form Submission: The application sends a request to the Django backend.

3. Weather Data Fetching: Django makes an API request to OpenWeatherMap with the entered city name.

4. Processing API Response:

  + Extracts temperature, humidity, wind speed, and weather description.
  + Formats the current date and time.

5.  Rendering Data: The weather details are sent to the frontend and displayed dynamically on the home page.

6. Error Handling:

  + If an invalid city is entered, a 404 error page is displayed.

  + Handles API errors gracefully to avoid crashes.


## 🔗 License
This project is licensed under the MIT License.

## Contact
For any queries or collaboration opportunities, feel free to reach out:

**Email**: mishradipti2402@gmail.com


 
