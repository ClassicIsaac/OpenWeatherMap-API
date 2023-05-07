## OpenWeatherMap Weather App
This Python application uses the OpenWeatherMap API to get current weather data for a specified city. The user is prompted to choose an operation - get temperature, get humidity, or get wind speed - and the corresponding information is returned. The code uses the requests library to make HTTP requests to the API and the dotenv library to load an API key from a .env file.

### Prerequisites
Python 3.x
OpenWeatherMap API key (free or paid)
requests library (can be installed using pip)
dotenv library (can be installed using pip)
Installation
Clone or download this repository.
Create a virtual environment for this project (optional but recommended).
Install the required libraries using pip install -r requirements.txt.
Create a .env file in the same directory as the Python code and add the following line to it:
makefile
Copy code
API_KEY=<your-api-key>
Replace <your-api-key> with your actual OpenWeatherMap API key.

### Usage
Run the program using python main.py.
Enter the name of a city when prompted.
Choose an operation by entering a number (1, 2, or 3) when prompted:
Get temperature
Get humidity
Get wind speed
The program will return the corresponding information for the specified city.

#### License
This code is licensed under the MIT License. See LICENSE for more information.