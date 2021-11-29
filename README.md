# MARN-5895-Final-Project: Wind driven Ekman upwelling at the Equator

In this project, we are trying to study the equatorial upwelling in the Pacific Ocean. 


So, what drives the upwelling at the equator?

Well, to go further, we need to familiarize ourselves with the concept of Ekman transport first.


So, what is Ekman transport, then?

The general idea is that the net transport of water mass due to the Coriolis effect is 90° (towards the right in the northern hemisphere and towards the south in the southern hemisphere)to the wind stress. Hence, the net transport will be towards the east if the wind is blowing from south to north in the northern hemisphere. 


How the transport towards the right and left in the northern and southern hemispheres, respectively, helps in the equatorial upwelling?

The wind pattern at the equator is easterly(trade wind), i.e., the wind blowing from east to west. This east to west wind will create a net transport towards the north in the northern hemisphere and towards the south in the southern hemisphere, Pulling water at the equator on both north and south ends. Hence following conservation of mass, some water has to fill up the space of leaving water mass at the equator. This water comes from the water below the surface. The stretching of water mass at the equator is called divergence, and the water coming below the surface to fill up the left water mass is known as upwelling. 

What datasets are required to study this process?

First to know whether the divergence is occuring due to wind driven ekman transport we need to look at the wind and surface current data. The surface current will be nearly ~45° to the wind. 


To visualize the upwelling there are various ways

1. Chlorophyll: as the water gets upwelled, the nutirient rich bottom water will create phytoplankton bloom which can be observed from the chlorophyll concentation.
2. SSH: As the divergence is occuring at the equater this will create a low sea surface height at the equator.
3. SST: As the water is also upwelling we can predict a slight cold water right at the upwelling location. 


Hence we need wind, surface current, SSH, and chlorophyll dataset, we did not used the SST for this project. 


The data sets are used from the sources:

Chlorophyll Concentration: [Global Ocean Chlorophyll, PP and PFT (Copernicus-GlobColour) from Satellite Observations: Daily (Reprocessed from 1997) Copernicus Marine Service](https://resources.marine.copernicus.eu/product-detail/OCEANCOLOUR_GLO_CHL_L3_REP_OBSERVATIONS_009_085/INFORMATION)

Sea Surface Height anomaly: [GLOBAL OCEAN GRIDDED L4 SEA SURFACE HEIGHTS AND DERIVED VARIABLES REPROCESSED (1993-ONGOING) Copernicus Marine Service]
(https://resources.marine.copernicus.eu/product-detail/SEALEVEL_GLO_PHY_L4_REP_OBSERVATIONS_008_047/INFORMATION)

Ocean Surface Current: [OSCAR](http://apdrc.soest.hawaii.edu/datadoc/podaac_oscar.php )

Wind: [ECMWF – ERA5](https://www.ecmwf.int/en/forecasts/dataset/ecmwf-reanalysis-v5)


Data Processing:

We first resampled all the data to monthly mean, and we selected the year 2015.

