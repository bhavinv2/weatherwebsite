Streamlit Weather Dashboard
Project Description

The Streamlit Weather Dashboard is a real-time web application that provides weather information for any city entered by the user. This application is built using Python and Streamlit and fetches weather data from the Weather API.

Features

Enter city name to retrieve weather information.
Displays key weather metrics such as temperature, wind speed, humidity, and more.
Handles errors gracefully, informing the user if weather data cannot be retrieved.
Installation

Clone the repository:

sh
Copy code
git clone https://github.com/your-username/streamlit-weather-dashboard.git
cd streamlit-weather-dashboard
Create and activate a virtual environment:

sh
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Obtain a Weather API key from WeatherAPI and store it in a .env file in the project directory:

env
Copy code
WEATHER_API_KEY=your_api_key_here
Usage

Run the Streamlit app:

sh
Copy code
streamlit run app.py
Open your web browser and go to the URL provided by Streamlit to view the dashboard.

Project Structure

bash
Copy code
streamlit-weather-dashboard/
├── app.py
├── .env
├── requirements.txt
└── README.md
app.py: Contains the Streamlit application code.
.env: Stores the Weather API key.
requirements.txt: Lists the dependencies required for the project.
README.md: Provides an overview of the project and instructions for setup and usage.
