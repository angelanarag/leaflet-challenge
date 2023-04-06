# leaflet-challenge
Module 15 Challenge JavaScript and Leaflet 

By A.Narag

April 13, 2023

This challenge is to build a way to visualize the United States Geological Survey (USGS) earthquake data using JavaScript and the Leaflet plugin. 

1. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. 
2. Select which dataset to visualize from the USGS GeoJSON FeedLinks site: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
3. The code is using the dataset for "All Earthquakes for the Past 7 days (updated every minute)":  https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
4. Use the URL of this JSON to pull in the data for the visualization.
5. Using Leaflet, create a map that plots all the earthquakes from the dataset based on their longitude and latitude.
6. The data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
7. Include popups that provide additional information about the earthquake when its associated marker is clicked.
8. Include a legend that will provide context for the map data.


Below is optional and not included in the submitted code.
1. Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. 
2. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates
3. Plot the tectonic plates dataset on the map in addition to the earthquakes.
4. Add other base maps to choose from.
5. Put each dataset into separate overlays that can be turned on and off independently.
6. Add layer controls to your map.

