# USGS Earthquake Visualization

## Project Overview

This project aims to provide a way to visualize earthquake data collected by the United States Geological Survey (USGS). It uses an interactive map that visualizes earthquake data based on depth and magnitude, with additional functionality to display tectonic plates and generate heatmaps of earthquake occurrences.

The project allows users to view earthquake data dynamically over different time frames and offers a layer control to choose between map types (Street or Topographic) and other data overlays.

## Features

- **Interactive Map**: Displays earthquake data from USGS in real-time.
- **Layer Control**: Toggle between different map types (Street or Topographic) and additional data overlays.
- **Marker Visualization**: Earthquake data is visualized using circular markers. The color and size of the markers represent the earthquake's depth and magnitude, respectively.
- **Heatmap**: A heatmap layer that shows the density of earthquake occurrences.
- **Tectonic Plates**: Displays the boundaries of tectonic plates.
- **Legend**: Provides a guide to the colors and markers indicating earthquake depth.

## Technologies Used

- **D3.js**: A JavaScript library for manipulating documents based on data.
- **Leaflet.js**: A leading JavaScript library for interactive maps.
- **GeoJSON**: A format for encoding geographical data structures.
- **HTML, CSS**: Standard web technologies for creating the user interface.

## Project Structure

The project is organized as follows:

```
earthquake-app/
│
├── static/
│   ├── css/
│   │   └── style.css         
│   ├── js/
│   │   └── logic.js          
│   │   └── leaflet-heat.js          
├── index.html                
└── README.md                 


### `index.html`
- Contains the basic structure and layout for the web page, including the map container and controls.

### `style.css`
- Provides custom styling for the map, controls, and other page elements.

### `logic.js`
- Contains the JavaScript logic for fetching the earthquake and tectonic plate data, generating the map, and applying interactivity.

