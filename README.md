# Geolocation API 📍

Geolocation API is a web application that dynamically fetches and displays information about a user's current country and its neighboring countries using geolocation data.

## Features

• Geolocation-based country detection: Automatically detects the user's location and retrieves the current country data.  

• Neighboring country display**: Fetches and displays information about the neighboring country, if available.  

• Dynamic data visualization: Displays country details, including the following:  
  - Flag  
  - Name  
  - Region  
  - Population  
  - Primary language  
  - Currency

• Error handling: Provides informative messages if an error occurs (e.g., geolocation denied, API failure). 

• Interactive button**: A simple button click triggers the geolocation and data fetching process.

## How It Works 

1. User's Location Detection  
   - The app uses the browser's `Geolocation API` to determine the user's latitude and longitude.
  
2. Reverse Geocoding  
   - Coordinates are sent to the [Big Data Cloud API](https://www.bigdatacloud.com/) to retrieve the user's country name.

3. Country Data Retrieval  
   - The app queries the [REST Countries API](https://restcountries.com/) to fetch details about the user's current country.  
   - If the country has neighbors, their data is also fetched and displayed.

4. Error Handling  
   - Handles geolocation errors, API failures, and missing data gracefully with user-friendly error messages.
  
## Technologies Used

- Frontend: HTML, CSS, Vanilla JavaScript  
- APIs:  
  - [REST Countries API](https://restcountries.com/)  
  - [Big Data Cloud Reverse Geocoding API](https://www.bigdatacloud.com/)  
- Browser Geolocation API

# How to test the Project

### The link created by the github, to test the project live version.

https://zukakharati.github.io/Geolocation-API/

### 📷 Screenshots

Main Page





