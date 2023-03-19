# Leaflet Map

This project is a web-based interactive map using [Leaflet.js](https://leafletjs.com/) library. It is centered on Tabriz, Iran and uses OpenStreetMap as the base map.

[![Live Preview](https://img.shields.io/badge/Live%20Preview-View%20Now-brightgreen)](https://go2gps.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/0e1762b4-bde9-40f5-b655-d4a30928b2ef/deploy-status)](https://app.netlify.com/sites/go2gps/deploys)

## Features
- Allows users to enter latitude and longitude or UTM coordinates and it will locate the point on the map.
- Includes a UTM input field and a function that converts UTM to latitude and longitude and sets the view of the map to those coordinates.
- Allows users to add a marker at the entered location.
- Displays a message if the location is not found.
- Allows users to click on the map and it will display a toolbox showing the latitude and longitude and also the UTM of that point
- Allows to clear the markers added by clicking on a button.
- When the user click on a point on the map, it adds a marker to that point and displays the Latitude and longitude and also the UTM of the marker in a Popup.

## Usage
- Open the index.html file in your browser.
- Use the form to enter coordinates (latitude and longitude or UTM).
- Click on "Go to Location" button to center the map on the provided coordinates and add a marker to that location.
- Click on "Show forms" button to show forms for entering coordinates as a popup.
- Click on "Clear Markers" button to remove all markers from the map.

## Requirements
- A web browser with JavaScript enabled.
- An internet connection for loading the Leaflet.js library and the OpenStreetMap tiles.

## Dependencies
- [Leaflet.js](https://leafletjs.com/) - An open-source JavaScript library for creating maps.
- [OpenStreetMap](https://www.openstreetmap.org/) - A free editable map of the world.
- [proj4js](https://proj4js.org/) - A JavaScript library to transform coordinates from one coordinate system to another.
