# Weather Application
Made in React library weather application uses data provided by [GeoDB Cities](https://rapidapi.com/wirefreethought/api/geodb-cities/) and [OpenWeather](https://openweathermap.org/)

# Run it locally
1. Install Node.js
2. In the directory of the project run `npm install`
3. Register on [GeoDB Cities](https://rapidapi.com/wirefreethought/api/geodb-cities/) and [OpenWeather](https://openweathermap.org/) and choose the free subscribtion plan
4. Go to GeoDB Cities documentation, find X-RapidAPI-Key and X-RapidAPI-Host 
5. Go to OpenWeather, find My API keys
5. Open `src/api.js`file and fill it according to the template with X-RapidAPI-Key, X-RapidAPI-Host and weather API key
6. Run `npm run start`. It will open the app automatically

Write a city name in the search bar and check the weather for the next 5 days. Due to the technical reasons with the free, and therefore limted, GeoDB API the database is limited to cities above 1 000 000 inhabitants.
