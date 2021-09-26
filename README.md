# World Weather Analysis

## Overview of World Weather Analysis
The purpose of the World Weather analysis was to create a "Plan My Trip" app for a travel company that would be able to provide a customized vacation itinerary for customers based on their vacation weather preferences. Below are the steps of the data analysis procedure for this app:

  - A list of 2,000 random cities around the world is generated and stored in a CSV file. 
  - Customers are prompted to enter the maximum and minimum temperature of their ideal vacation weather for their trip. 
  - This information is then used to filter the database containing the 2,000 cities and identify all cities matching the customer's ideal vacation weather. 
  - An API call is then made to identify hotels within a 5,000 meter radius of these potential travel destinations that match the customer's preferences. 
  - A map can be generated with markers of these potential travel destinations that also contain information about the city, country, hotel name, and weather. 
  - From this list of potential travel destinations, the beta tester can choose four cities within the same vicinity to create a travel itinerary.
  - Once four cities are chosen, then a map depicting the routes between these four cities can be generated along with another map depicting information about the four cities  


## Resources
- Data Sources: WeatherPy_database.csv (generated through OpenWeatherMap API), WeatherPy_vacation.csv (generated through Google Maps Platform APIs)
- Software: Python 3.7.10, Anaconda 1.7.2, Jupyter Notebook, Pandas, NumPy, Requests & API keys, GMaps, Matplotlib


## Sample Data
A sample of a hypothetical trip based on weather preferences of a maximum temperature of 90 and a minimum temperature of 75 has been stored and provided for review:

Map depicting potential travel destinations with the above weather criteria:
![image](https://user-images.githubusercontent.com/85533099/134824899-af3172a9-248b-43d0-bcfb-59a85be41b65.png)

The same map as above depicting information boxes that provide detailed information about the markers:
![image](https://user-images.githubusercontent.com/85533099/134824812-7e4d2127-c654-4910-bb5a-ebbf42545fa3.png)

Map depicting the travel route between four chosen cities in Brazil (driving as the method of transportation):
![image](https://user-images.githubusercontent.com/85533099/134824996-7de9e3d0-787d-4f61-9b26-8a7ee5175ca2.png)

Map depicting the four chosen cities along with information boxes that provide detailed information about the markers:
![image](https://user-images.githubusercontent.com/85533099/134825017-a41d1760-5d68-41db-981d-4b9e89f9ea47.png)

A second picture of the same map above that shows Touros that is hidden in the above map, since Touros and Natal are close together:
![image](https://user-images.githubusercontent.com/85533099/134825157-4581b493-8652-410d-b12b-e910445c73e0.png)


