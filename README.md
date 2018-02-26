# Shapefiles
Shapefile of Fortaleza City


This shapefile has 118 neighborhoods (it does not have the Parque Santa Maria neighborhood, which in the time the shapefile was made, Parque Santa Maria was part of Ancuri). That is the reason why this shapefile has only 118 neighborhoods and not 119 as is currently accepted as the number of neighborhoods of Fortaleza City.

The shapefile has the following fields:

1. Geometry
2. BoundingBox
3. X
4. Y
5. UI_CODIGO
6. GID
7. NOME
8. ID_SINAN
9. ID_SINANW
10. ID_CADSUS
11. SER
12. COD_IBGE
13. ID_SINANNE
14. CO_SIVITAI
15. ID_FAD
16. ID_MAP_OLD
17. AREAKM2
18. CHICK
19. POP

* The fields X and Y represents, respectively, the longitude and latitude coordinates for each neighborhood. For this case, they are in UTM system coordinates.

* The field NOME contains the number of each neighborhood.

* The field POP contains the number of people living in each neighborhood according to the 2010 IBGE census.


There are lots of tools to work with shapefiles. To handle the shapefiles, we have pyshp (python librariy), which can be found on Python Package Index (PyPi). There are scripts on this projects to do lots of things with shapefiles, like plot the geometry it has, to access its data etc.

Extra tools to handle shapefiles are easily found on MATLAB. Another free software used to visualize shapefiles and its contents is qgis.
