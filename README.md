# Neighborhood Engagement & Metrics Map

An interactive geospatial visualization tool built in Python to track nuclei and concentric circles.

## Overview
This map provides a "bullseye" visualization of four key metrics across various neighborhoods:
* **Population:** Total population count of community/nucleus.
* **Conversation:** Number of community members engaged in the conversaion.
* **Participating:** Number participating in core activities.
* **Committed:** Number committed to the process.

## Built With
* **Python** (Pandas, Folium, GeoPandas)
* **GitHub Pages** (Hosting)
* **Leaflet.js** (Mapping Engine)

## How to Read the Map
* **Bullseye Rings:** Each color represents a different metric. The larger the ring, the higher the count for that metric in that specific neighborhood.
* **Stacked Labels:** Look at the adjacent labels for precise counts. 
* **N/A Values:** Where data was unavailable in the source csv file, the label displays "N/A" and no ring is drawn.

## Data Source
The visualization is powered by an csv-based dataset containing geographic coordinates and community metrics.
