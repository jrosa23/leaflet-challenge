# leaflet-challenge
**Earthquake Map**

This project uses Leaflet.js to visualize recent earthquake data and tectonic plate boundaries on an interactive map.

**Features**

Displays earthquake data from the USGS GeoJSON feed.

Shows tectonic plate boundaries from a GeoJSON source.

Includes a legend indicating earthquake depth.

Provides layer controls for toggling between basemap styles and overlay layers.

**Setup**

Prerequisites:

A web browser

Internet connection

**Installation**

Clone or download this repository.

Open the HTML file in a web browser.

**Data Sources:**

Earthquake Data: USGS GeoJSON Feed

Tectonic Plate Data: Fraxen Tectonic Plates GeoJSON

**Layers**

Basemap: Default OpenStreetMap basemap.

Street Layer: Alternative OpenStreetMap tile layer.

Earthquakes: Displays earthquake locations with circle markers based on magnitude and depth.

Tectonic Plates: Displays tectonic plate boundary lines.

Legend

The legend color codes earthquake depth levels:

Green: <10 km

Yellow-Green: 10-30 km

Yellow: 30-50 km

Orange: 50-70 km

Red-Orange: 70-90 km

Red: >90 km

Usage

Zoom in/out using map controls.

Toggle layers using the control box in the top right.

Click on markers to see earthquake details (magnitude & location).

**Dependencies**

Leaflet.js

D3.js

**License**

This project is open-source and available under the MIT License.