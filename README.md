## Enhancement Ratios from TROPOMI and FRP Data from VIIRS S-NPP Used in "Analyzing the Impact of Evolving Combustion Conditions on the Composition of Wildfire Emissions Using Satellite Data"

### Variables in Wildfires_Names_Locations_Sizes.xlsx are described below:
Name: Fire Name

Starting Location (Lat., Long.): Latitude and Longitude of the starting location of the wildfire

Fire Size (Acres): Total burned area reported throughout the entire duration of the wildfire

### Variables in NO2CO_Data.xlsx are described below:
Fire Name

Date: yyyy-mm-dd format

yyyymmdd: yyyymmddThhmmss format where the time (hhmmss) is the TROPOMI observation start time in UTC that can be used to map FRP data to TROPOMI data

Days Since Start: Days since the start of the wildfire defined in Wildfire_Names_Locations_Sizes.xlsx

NO$_2$/CO: Enhancement ratio of TROPOMI NO2 compared with CO	

std dev of fit: Standard deviation of the slope

### Variables in HCHOCO_Data.xlsx are described below:
Fire Name

Date: yyyy-mm-dd format

yyyymmdd: yyyymmddThhmmss format where the time (hhmmss) is the TROPOMI observation start time in UTC that can be used to map FRP data to TROPOMI data

Days Since Start: Days since the start of the wildfire defined in Wildfire_Names_Locations_Sizes.xlsx

HCHO/CO: Enhancement ratio of TROPOMI HCHO compared with CO

std dev of fit: Standard deviation of the slope

### Variables in FRP_Data.xlsx are described below:
#### Please note that the data used to find the statistics for each fire was obtained from VIIRS onboard the S-NPP satellite. The pixel-level Fire Radiative Power (FRP) measurements can be downloaded [here](https://firms.modaps.eosdis.nasa.gov/download/). Only daytime data was used in our analysis.
Fire Name

Date: yyyy-mm-dd format

yyyymmdd: yyyymmddThhmmss format where the time (hhmmss) is the TROPOMI observation start time in UTC that can be used to map FRP data to TROPOMI data

Days Since Start: Days since the start of the wildfire defined in Wildfire_Names_Locations_Sizes.xlsx

mean_frp: Mean FRP (MW)  	

median_frp: Median FRP (MW)	

max_frp: max FRP (MW)	

std_frp: standard deviation of the FRP measurements (MW)	

sum_frp: total FRP (MW)


