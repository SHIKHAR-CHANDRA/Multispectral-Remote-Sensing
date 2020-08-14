**Mulitspectral Remote Sensing**

This project aims to calculate two vegetation indices from NAIP and Landsat Remote Sensing data.

The first index is Normalized Difference Vegetation Index or NDVI.
NDVI is a measure of the difference between Near Infrared Light(reflected by vegetation) and Red Light(absorbed by vegetation). NDVI ranges from -1 to +1. Therefore, region of land having NDVI values close to +1 indicate dense vegetation, whereas values close to -1 highly indicate presence of water. 

The second index is Difference Normalized Burn Ratio or dNBR.

The Normalized burn ratio (NBR) is used to identify burned areas. The formula is similar to normalized difference vegetation index (NDVI), except that it uses Near-Infrared (NIR) and ShortWave-Infrared (SWIR) portions of the electromagnetic spectrum. 

A fire scar which contains scarred woody vegetation and earth will reflect more strongly in the SWIR part of the electromagnetic spectrum and beyond. Alternatively, healthy vegetation reflects strongly in the NIR region of the electromagnetic spectrum and weakly in the SWIR.

To calculate the difference NBR (dNBR), you subtract the post-fire NBR raster from the pre-fire NBR raster.
