# GeoJson api

Simple nodejs api created with mongoDB to create objects with coordinates based at a certain address writen by the user.
This app also renders static files that creates a map with points for the coordinates.
Follow the steps to run the app:

1 - create env variable at ./config/config.env with the name GEOCODER_API_KEY with you current GEOCODER api key.
2 - change the key of map box at ./public/js/map to your current map box key
3 - use at terminal: npm run dev
