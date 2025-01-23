# Earthquake Visualization Dashboard

This web application visualizes global earthquake data using Leaflet.js to create an interactive map. The visualization includes data from USGS (United States Geological Survey) and displays earthquake locations, magnitudes, and depths from the past week.

## Features

- Interactive map showing global earthquake locations
- Color-coded markers based on earthquake depth
- Marker size corresponds to earthquake magnitude
- Popup information for each earthquake showing:
  - Location
  - Magnitude
  - Depth
- Color-coded legend indicating depth ranges
- Multiple map layer options (OpenStreetMap and Humanitarian OSM)
- Layer controls for toggling different map views

## Technologies Used

- Leaflet.js
- D3.js
- HTML/CSS/JavaScript
- OpenStreetMap API

## Data Source

- USGS Earthquake API: Real-time data for all earthquakes in the past 30 days
  - Endpoint: `https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.geojson`

## Map Features

- Base layers:
  - OpenStreetMap (default)
  - Humanitarian OSM layer
- Interactive markers:
  - Click for detailed earthquake information
  - Size indicates magnitude
  - Color indicates depth
- Legend shows depth ranges and corresponding colors

## Resources
- For this project I used class files for module 15 as well as Claude to create my code