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


Data
----
Admin 2 boundaries can be found in the data folder. Admin 3 are too big for GitHub, but are available [here](http://ec2-54-86-59-119.compute-1.amazonaws.com/owncloud/public.php?service=files&t=d47e7b44039c405b4425a82578385fb1).


On the geoJSON file, **CODANEDEP** == p-code from the national government ([Divipola](http://www.dane.gov.co/Divipola/)).