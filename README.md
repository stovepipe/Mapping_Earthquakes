# Project Overview
This analysis uses the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of earthquakes from GeoJSON data. Using the Leaflet library, our end result will be to plot the data on a Mapbox map through an API request, creating interactivity for the earthquake data.

## Resources

[mapbox.com](https://www.mapbox.com/)
Mapbox is used to generate the map layers that generate beneath the geoJSON data for earthquakes and tectonic plates. To access the API, you must first create an account, after which, you will be able to access a generated Token or API Key. 

[index.html](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html)
This is the html that is loaded into the webpage and calling our api, js and css files to generate the visualizations. Please see the code snippets below for the calls to various resources embedded in the html.

![css call](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/css.png)

![API call](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/api.png)

![javascript call](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/logic.png)

[challenge_logic.js](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)
This is the javascript that pulls the API data, the geoJSON data, and builds the map object.

[style.css](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css)
This is the styling css that helps to format our html page and fit the map to the page.

### Visualization

![Street Map Base Layer with Earthquakes and Tectonic Plates](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/streets.png)
**Street Map Base Layer with Earthquakes and Tectonic Plates**

![Satellite Street Map Base Layer with Earthquakes and Tectonic Plates](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/satellite_streets.png)
**Satellite Street Map Base Layer with Earthquakes and Tectonic Plates**

![Dark Map Base Layer with Earthquakes and Tectonic Plates](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/dark.png)
**Dark Map Base Layer with Earthquakes and Tectonic Plates**

![Major Earthquake geoJSON Layer](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/major_earthquakes.png)
**Major Earthquake geoJSON Layer**

![Tectonic Plate geoJSON Layer](https://github.com/stovepipe/Mapping_Earthquakes/blob/main/Resources/tectonic_plates.png)
**Tectonic Plate geoJSON Layer**




