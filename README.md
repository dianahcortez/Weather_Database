# Weather_Database
## Overview
This assignment consists of three technical analyses.  
- Deliverable 1: Retrieve Weather Data
- Deliverable 2: Create a Customer Travel Destinations Map
- Deliverable 3: Create a Travel Itinerary Map

## Resources
- CSV Files: Weather_Database.csv, WeatherPy_vacation.csv
- Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb
- Python: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON

## Sample Trip Itinerary Results
<img width="500" alt="Customer Input" src="https://user-images.githubusercontent.com/104927745/180665254-f509eb9f-4616-48ab-8046-edee6ad8e51f.PNG">

<img width="500" alt="Hotel Weather DataFrame" src="https://user-images.githubusercontent.com/104927745/180665255-4d898ba9-17be-4eaa-92d4-3d7b04aaf8fd.PNG">

<img width="1000" alt="WeatherPy_vacation_map (Deliverable 2)" src="https://user-images.githubusercontent.com/104927745/180664809-fb363b7e-3384-439b-8dcd-6efc0b71c77c.PNG">

<img width="1000" alt="Weather_Py_travel_map (Deliverable 3)" src="https://user-images.githubusercontent.com/104927745/180664810-62dfc87f-cde3-4e07-91cb-dc55ba51a399.PNG">

<img width="1000" alt="WeatherPy_travel_map_markers (Deliverable 3)" src="https://user-images.githubusercontent.com/104927745/180664812-da94a686-0a27-4a9a-b4be-797e2b2b02fb.PNG">


## Summary
I began this project by generating a set of 2,000 random latitudes and longitudes, retrieving the nearest city, and performing an API call with the OpenWeatherMap to retrieve the current weather description for each city, this data was then saved into a new DataFrame for subsequent steps.  Next up was to use input statements to retrieve customer weather preferences (such as max and minimum temperature), and to use those preferences to identify potential travel destinations and nearby hotels. Lastly I showed those locations by adding in a marker layer map with pop-up markers.  The final step in this project was creating the Travel Itinerary Map by utilizing google directions API to create a travel Itinerary.
