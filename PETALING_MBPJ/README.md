Setup for GeoReference and View
=================================

Assumes:
- QGIS
- OpenLayer plugin installed 
- GeoReference plugin installed

Steps:

1. Create new Project (use projection 3857)
2. Load layer Google Street from Open Layer 

To add to the existing Shapefiles:

3. Map points MBPJ_Final.points with MBPJ.jpg.  Run the georeference. 
4. Map points MBPJ_Kawasan_Pentadbiran_Final.points with 
     MBPJ_Kawasan_Pentadbiran.jpg.  Run the georeference.
5. Confirm that the georeference is done correctly 

or Just View Current Vector Shapefile:

3. Load Vector layer; choose from shapefiles/MBPJ_Zon_Pentadbiran.shp 
4. Load Vector layer; choose from shapefiles/PPR_Kota_Damansara.shp
5. Confirm that vector layers loaded correctly and attribute tables has data

and describe the various available raw_raster, shapefiles, georeference_points

By default; projections are 3857 (Google Maps); and only in the final output 
the output of KML if needed should be in 4286

