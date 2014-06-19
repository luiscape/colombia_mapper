Usage
=====

From: http://ben.balter.com/2013/06/26/how-to-convert-shapefiles-to-geojson-for-use-on-github/

Run the following command to convert from shapefile to GeoJSON:

```bash
ogr2ogr -f GeoJSON -t_srs crs:84 [name].geojson [name].shp
```

Running Examples
----------------

ogr2ogr -f GeoJSON -t_srs crs:84 admin_2.geojson ADM_Departamentos.shp
ogr2ogr -f GeoJSON -t_srs crs:84 admin_3.geojson ADM_Municipios.shp


