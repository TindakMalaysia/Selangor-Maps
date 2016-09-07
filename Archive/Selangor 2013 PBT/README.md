Selangor 2013 PBT
===================
- The Administrative Boundaries for Local Authorities in Selangor.
Examples include: MBPJ, MBSA, MPSJ ..
- Projection is EPSG:3857

To convert to GeoJSON:
Library/Frameworks/GDAL.framework/Versions/Current/Programs/ogr2ogr -f GeoJSON -s_srs EPSG:3857 -t_srs EPSG:3857 Selangor_2013_PBT.geojson Selangor_2013_PBT.shp 

