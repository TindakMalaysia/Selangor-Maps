Selangor 2013 Daerah Mengundi
===============================
- The Shapefiles, GeoJSON and KML for Polling District; the smallest area of 
Electoral Boundaries for Malaysia
- Projection is EPSG:3857

To convert to GeoJSON; use the following command:
/Library/Frameworks/GDAL.framework/Versions/Current/Programs/ogr2ogr -f GeoJSON -s_srs EPSG:3857 -t_srs EPSG:4326 08_Sgr_13_Ori.geojson 08_Sgr_13_Ori.shp 

