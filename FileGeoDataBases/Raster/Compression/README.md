# QGIS-ESRI-Testfiles/FileGeoDatabases/Raster/Compression/
A collection of ESRI ArcGIS 10.7.x generated data for testing against GDAL and QGIS.

This folder is comprised of the following:
1) Compacted_RasterTestData.gdb   
   * A freshly compacted/uncompressed geodatabase [baseline dataset]
2) Lossless_RasterTestData.gdb
   * a losslessly compressed version of [1]
3) Lossy_RasterTestData.gdb
   * a lossy compressed version of [1]

In the geodatabases we have:

4) ESRI File GeoDatabse imports with all defaults against a clean/new geodatabase of the reference data downloaded from GitHub.   
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/raster.tif
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/dem.tif
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/custom/grass7/raster_1class.tif
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/custom/grass7/raster_4class.tif
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/custom/grass7/raster_5class.tif
https://github.com/qgis/QGIS/blob/master/python/plugins/processing/tests/testdata/custom/grass7/raster_6class.tif
https://github.com/qgis/QGIS/blob/master/tests/testdata/landsat_4326.tif

   * Reprojections of [4] using EPSG3857 (source were WGS84 already)
   * Copy Raster of [4] into each bitdepth (1/2/4/8/8u/8s/16u/16s/32u/32s/32f/64) for singleband (dem.tif) and multi-band (landsat_4326.tif)
