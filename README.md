Assignment 1 - NLP
Roll No: 2301730100
Project 5 – Weather Data

Description:
This project collects weather data (temperature, humidity, wind speed, forecasts) 
for multiple Indian cities by scraping from wttr.in.

Cities covered:
Gurgaon, Delhi, Noida, Rajasthan, Hyderabad, Punjab, Gorakhpur, Goa, Mumbai, 
Jaipur, Jammu, Kerala

Output:
The data is saved into a CSV file (weather_roll100.csv).
Columns include city, date, type (current/forecast), temperature, humidity, wind speed, 
min/max temperature, weather description, timestamp, and source.

How to Run:
1. Install dependencies:
   pip install requests pandas
2. Run the script:
   python weather_scrape_roll100.py
3. The CSV file (weather_roll100.csv) will be generated in the same folder.

Website Used:
https://wttr.in (open weather information service)
