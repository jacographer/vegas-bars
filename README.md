# Questionable Cocktails
### Las Vegas area bars displayed by number of demerits on their most recent health inspection. 
<br>

**1. Data**: [Restaurant Inspection Open Data](https://opendataportal-lasvegas.opendata.arcgis.com/datasets/restaurant-inspections-open-data/explore) downloaded as a CSV from Las Vegas Open Data. 

**2. Processing**: Filtered data down to 'Bar / Tavern' venues and removed non-essential attributes using Microsoft Excel. Exported to geojson format using QGIS. Visualized using [Leaflet API](https://leafletjs.com/) and classified with [Simple Statistics ckmeans clustering](https://simplestatistics.org/docs/#ckmeans).

**3. Tools**: Leaflet 1.7.1; macOS 12.1; QGIS 3.20; Microsoft Excel 15.56

