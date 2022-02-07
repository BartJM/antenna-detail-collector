# antenna-detail-collector
Collect antenna details from the dutch antenneregister (https://antenneregister.nl/Html5Viewer/Index.html?viewer=Antenneregister_extern).

- Input is a csv with a ID column that contains the id of the basestation.
- Output is a json with all antenna data.

## Basestation data
The information in thee csv is hosted as an ArcGIS feature server (https://gisextern.dictu.nl//arcgis/rest/services/Antenneregister/). This can be loaded into GIS software (ex. QGIS). From there the csv can be created.
