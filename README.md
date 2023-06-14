# geospatial-python

## INSTALL REQUIREMENTS
- Download or clone this repo
- Install [Python 3.9](https://www.python.org/downloads/)
- Install required libraries: `pip install -r workshops/siglibre-2023/requirements.txt`
- CReate account in [Copernicus Open Access Hub](https://scihub.copernicus.eu/userguide/SelfRegistration)
- Download datasets:
  - [Mapa de cultivos y aprovechamientos de Navarra (2021)](https://idena.navarra.es/descargas/OCUPAC_Pol_MCA_VE2021.zip)

## Topics

* Introduction to geospatial data. Main sources of information, data formats, examples. How to combine geospatial information with other sources of information. Refer to existing content in the Kit

* How to get the data. 

* Basic intro to Python for non-developers

* Introduction to geospatial data analysis in Python, with a focus on tabular vector data. It first focuses on introducing the participants to the different libraries to work with geospatial data and will cover munging geo-data and exploring relations over space. This includes importing data in different formats (e.g. shapefile, GeoJSON), visualizing, combining and tidying them up for analysis, and will use libraries such as pandas, geopandas, shapely, PySAL, or rasterio. 

* Creating interactive maps with Python 

* Analyzing satellite data
  * Copernicus es el programa civil de observación de la Tierra coordinado y gestionado por la Comisión Europea y la Agencia Europea del Medio Ambiente con el objetivo de proporcionar información precisa y actualizada en seis áreas temáticas:
    - cambio climático 
    - seguridad 
    - gestión de emergencias 
    - atmósfera
    - ámbito terrestre
  
  * El satélite Sentinel-5p de la Agencia Espacial Europea lleva a bordo el sensor TROPOMI. Este sensor permite monitorizar concentraciones de gases como el ozono, el metano, el monóxido de carbono, el dióxido de nitrógeno o el óxido de azufre. Con una resolución espacial de unos 7kmx7km, Sentinel-5p cubre diariamente toda la superfície terrestre. De este modo puede hacerse un seguimiento exhaustivo de la evolución de estos gases, y analizar episodios muy concretos.

  * Acceso a Planet como empresa proveedora de imágenes de satélite y se enseñará paso a paso como usar Python notebooks en combinación con librerías de Planet y otras de tratamiento de imágenes para obtener un índice de vegetación (NDVI).

## Exposing the invisible Kit

- [Using Maps to See Beyond the Obvious](https://kit.exposingtheinvisible.org/en/how/maps.html)
- [Maps for advocacy](https://exposingtheinvisible.org/resources/maps-advocacy) [Booklet](https://www.civicspace.eu/upload/library/maps-for-advocacy-5d628d1228e69.pdf)
- [Seeing the world through Google's eyes](https://exposingtheinvisible.org/resources/seeing-the-world-through-googles)
- [Starting satellite investigations](https://exposingtheinvisible.org/resources/obtaining-evidence/starting-satellite-investigations)

## Using Datawrapper

* How to visualize information using maps with [Datawrapper](https://www.datawrapper.de/maps/). Discuss point, bubble and choropleth map types, their uses, etc

![Maps with Datawrapper](https://raw.githubusercontent.com/alabarga/geospatial-python/master/img/datawrapper_maps.png)

## References
- [Python for Journalists](https://github.com/winnydejong/pythonforjournalists)
- [Coding for journalists](https://coding-for-journalists.readthedocs.io/en/latest/)
- [Copernicus, el programa de observación de la Tierra](https://www.unigis.es/copernicus-observacion-tierra/)
- [Mapping for Advocacy](https://www.opensocietyfoundations.org/publications/mapping-advocacy)
- [Micro-satellite Data: Measuring Impact from Space](https://www.poverty-action.org/sites/default/files/publications/Goldilocks-Deep-Dive-Micro-satellite-Data-Measuring-Impact-from-Space_4.pdf)
- [Teledetección y Python para analizar los efectos de la COVID-19](https://www.unigis.es/teledeteccion-y-python-para-analizar-los-efectos-de-la-covid-19/)
- Introduction to Geospatial Data Analysis with Python ([video](https://www.youtube.com/watch?v=kJXUUO5M4ok&feature=youtu.be)) [Code](https://github.com/geopandas/scipy2018-geospatial-data)
- [Análisis de imágenes de satélite con Python notebooks](https://www.unigis.es/webinar-analisis-de-imagenes-de-satelite-con-python-notebooks/) [Video](https://vimeo.com/427998599) [Code](https://github.com/ramiroaznar/ndvi-analysis)
- [Geographic Data Science](http://darribas.org/gds19/)
 
