## Map Description
This map displays vascular plant species richness (species per square mile) by county across North Carolina. It was developed as an example of choropleth mapping. The map draws from the _Vascular Plants of North Carolina_ database, a project that tracks all known vascular plant species occurring in the state.

Users can hover over a county to view the number of plant species per square mile and click to zoom in on that county. The map uses the “Greens” sequential color palette from chroma.js to visualize differences in species richness, with darker greens indicating higher diversity.

## Packages, Stylesheets, and Data
*  Leaflet.js: Core mapping library for visualization and interactivity
* Leaflet-ajax: Loads GeoJSON data asynchronously
* jQuery: Handles DOM manipulation and event handling
* Chroma.js: Color scales
* Leaflet.css: Basemap styling
* Plant data and information provided by the Vascular Plants of North Carolina [web project](https://auth1.dpr.ncparks.gov/flora/index.php){:target="_blank"}
* County boundary data provided by [NC One Map](https://www.nconemap.gov/datasets/NCEM-GIS::north-carolina-state-and-county-boundary-polygons/explore){:target="_blank"}

__Author__: Dakota Wagner
__Last Updated__: October 24, 2025