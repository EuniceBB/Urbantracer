# Urbantracer
UrbanTracer creates urbanized area polygon over a street map. If you don’t have one, you can find street maps for free in Geofabrik: 
http://download.geofabrik.de/

Resolution: is the square size. It defines the quality of the drawing, more or less detailed. 
Intra-urban open spaces are empty areas between streets. You can choose the area value that will be considered as empty, according to your objectives.

Mandatory CRS in meters (Project Properties and Files for a correct calculation of areas). Be careful to use CRS correctly!
Polygon areas could be separated. A simple solution is to change the appearance of the polygons to “No Pen” but if you really want to unify them, please use a Qgis Tool "Dissolve".
