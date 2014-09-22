# UK Counties

GeoJSON files representing UK counties from the Office of National Statistics. This data was derived from the ONS County Boundaries file (https://geoportal.statistics.gov.uk/geoportal/catalog/main/home.page) and modified with the ogr2ogr tool, and split into indivudal files.

e.g.

```
ogr2ogr -t_srs "EPSG:4326" -f GEOJSON uk.json CTY_DEC_2012_EN_BGC.shp
```