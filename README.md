udacity_travelappproject
Final project for the Front End NanoDegree at Udacity.

udacity_travelappproject Final project for the Front End NanoDegree at Udacity.

Travel-App This is the last project for the Udacity Front-End Web Developer Course. This project required me to build a travel app to obtain a desired trip destination and date from the user and then updating the UI with the weather forecast and an image of the destination using information obtained from three external APIs indicated by Udacity's Project Rubric (Geonames, Weatherbit and Pixabay).

I developed this application by setting the HTML and CSS, setting up the form to obtaining the data entered by the user (destination, departure date and arrival date) and then setting the connection to the specified APIs in order to get the data required. After that, data was handled in order to update the UI. Considering Weatherbit API would not care for the exact dates, but only the amount of days to travel with a maximum of 16 days from the day the search was being made (today + 16) departure and arrival dates would only be useful to fill the UI and then to handle the final weather data for the user, within those days. I decided to provide with the full 16 day forecast anyway.

Installation Download/clone this repo Run npm install in the terminal to install all required dependencies

Add .env file and input the api keys: GEONAMES_API_KEY= WEATHERBIT_API_KEY= PIXABAY_API_KEY=

npm run build-prod Run npm run start to start the app at port 8010

Extend Options used in this project: Add end date and display length of trip. Pull in an image for the country from Pixabay API when the entered location brings up no results (good for obscure localities).