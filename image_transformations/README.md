# Image Transformations

There are some basic image transformations based on satellital images for weather forecast, vegetation, water or lines detection. We are going to identify wich ones we are going to use as middle layer in our solution.

## Tags

According to current challenge, que have to detect these tags in tiff and jpg satellital images:

* agriculture
* artisinal_mine
* bare_ground
* blooming
* blow_down
* clear
* cloudy
* conventional_mine
* cultivation
* habitation
* haze
* partly_cloudy
* primary
* road
* selective_logging
* slash_burn
* water

We have to research for standard image transformations that will detect each label.

## Indices

### Vegetation detection

### NDVI

Normalized Difference Vegetation Index: The normalized difference vegetation index (NDVI) is a simple graphical indicator that can be used to analyze remote sensing measurements, typically but not necessarily from a space platform, and assess whether the target being observed contains live green vegetation or not.

!https://upload.wikimedia.org/wikipedia/commons/9/94/NDVI_062003.png!

https://pypi.python.org/pypi/landsat-util/0.13.1

#### EVI

#### SAVI

#### MSAVI

### Water detection

#### NDWI

Normalized Difference Water Index (NDWI) may refer to one of at least two remote sensing-derived indexes related to liquid water: 

One is used to monitor changes in water content of leaves, using near-infrared (NIR) and short-wave infrared (SWIR) wavelengths, proposed by Gao in 1996

!http://www.apsdps.ap.gov.in/images/ndwi_june_tumb.png?url=images/ndwi_june.png!

#### MNDWI

#### AWEI

#### ML

#### SVM

### Cloud detection

#### Fmask

Zhu, Z. and Woodcock, C.E. (2012). Object-based cloud and cloud shadow detection in Landsat imagery Remote Sensing of Environment 118 (2012) 83-94.

and

Zhu, Z., Wang, S. and Woodcock, C.E. (2015). Improvement and expansion of the Fmask algorithm: cloud, cloud shadow, and snow detection for Landsats 4-7, 8, and Sentinel 2 images Remote Sensing of Environment 159 (2015) 269-277.

http://pythonfmask.org/en/latest/

#### SPARCS

Spatial Procedures for Automated Removal of Cloud and Shadow. Algorithm that improves Fmask cloud detection (presented in 2014)[www.mdpi.com/2072-4292/6/6/4907/pdf]

#### NESDIS

#### AVHRR

#### MODIS

#### ACCA

### Others

#### NDMI

#### NBR

#### NBR2

#### NIRI

### Line detection

## Resources

* https://github.com/planetlabs/planet-amazon-deforestation
* https://www.kaggle.com/kbalkoski/initial-eda-image-processing
* USGS Guide on Landsat: https://landsat.usgs.gov/sites/default/files/documents/si_product_guide.pdf
* Cloud detection: https://weather.msfc.nasa.gov/sport/journal/pdfs/2009_GRS_Jedlovec.pdf
* Water Detection: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4970121/
* NDWI: https://en.wikipedia.org/wiki/Normalized_difference_water_index
* http://pysptools.sourceforge.net/index.html
* https://en.wikipedia.org/wiki/Normalized_Difference_Vegetation_Index
* http://edo.jrc.ec.europa.eu/documents/factsheets/factsheet_ndwi.pdf
* http://ceeserver.cee.cornell.edu/wdp2/cee6150/Readings/Gao_1996_RSE_58_257-266_NDWI.pdf
* http://www.apsdps.ap.gov.in/NDWI_maps.html
* http://wiki.theoutpost.io/files/remote-sensing/hallahan-prepperneau-geo544-final-abstract.pdf
* http://www.mdpi.com/2072-4292/6/6/4907/pdf
* http://pythonfmask.org/en/latest/
* https://pypi.python.org/pypi/landsat-util/0.13.1
