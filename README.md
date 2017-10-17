# Okavango_NDVI

Final project for GEOG 371, Fall 2017

Interactive web-map that displays distribution of NDVI and monthly precipitation in the Okavango Delta in nothern Botswana. The goal of this web map is to communicate to the map viewer the spatial disparity in where precipitation occurs and where vegetation becomes more lush or green as result. Including a DEM (digital elevation model) will help to illustrate how elevation in watersheds affect the level of NDVI (Normalized Difference Vegetation Index) or "greeness" and the Evapotranspiration (ET) rate based on proximity to boundary of watersheds/slope of surface. Essentially, the goal is to have a visual representation of vegetation as a result of precip and elevation. The main challenge of this topic, is finding the suitable system architecture to host and efficiently display the changing distribution of NDVI based on the extent and zoom level of the map. The tentative plan is to use Python to run the NDVI analysis, and hosting this app-like interaction on Heroku to provide a web map that responds quickly to the viewers extent and zoom level of the imagery. Depending on the size of the files, the data may need to be hosted in a GeoDatabase like PostgreSQL. If the files are small enough, the data will be hosted in a File Server. Web-mapping features that I plan on incorporating are graphs displaying the NDVI and ET distribution using d3. As for the style and feel of the webmap, I plan to keep it simplistic and minimal, using a small array of colors and having most of the color displayed as the NDVI values.



|          Name           |   Description    | URL  | Attribute | Size |
| :---------------------: | :--------------: | :--: | :-------: | :--: |
|          NDVI           | 30 m resoluttion |      |           |      |
| Evapotranspiration (ET) |                  |      |           |      |
|                         |                  |      |           |      |

![][Okavango_NDVI](https://github.com/hannahfriedrich/Okavango_NDVI)/[img](https://github.com/hannahfriedrich/Okavango_NDVI/tree/master/img)/**GEE_NDVI.png**

![][Okavango_NDVI](https://github.com/hannahfriedrich/Okavango_NDVI)/[img](https://github.com/hannahfriedrich/Okavango_NDVI/tree/master/img)/**QGIS_DataPic.png**