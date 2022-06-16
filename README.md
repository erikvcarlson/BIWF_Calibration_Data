# Calibration Data for Deployed Stations Overlooking the Block Island Wind Farm
## Overview: 
The files contained in this repository include the calibration data collected in the late summer of 2021. Details outlining the methods of calibration are in the accompanying paper. 

## Files:
BRR_Tags_Edited_Corrected_Ports.csv -> RF Calibration Data from Black Rock Beach, RI
Montauk_Tag.csv -> RF Calibration Data from Montauk, NY 
SE_Light_Tag.csv -> RF Calibration Data from South East Lighthouse, RI 
Turbine_Data - Turbine_Tags_Edited.csv -> RF Calibration Data from BIWF Turbine 2, RI
GPS_Data_apr17_aug30_aug31_sep18_sep26_sep27.csv -> GPS Points collected from all calibration surveys. 

## RF Calibration Format: 
Each Station is built with four yagi antennas offset by 90 degrees placed in ports 1-4 with an omni-directional antenna representing port 5 in each of the calibration files. 

RSSI has units dBm 

motusTagID is the calibration tag id as denoted in MOTUS. 

time is the coordinated universal time

## GPS Data Format:
The critical columns are: 

X is the Longitude

Y is the Latitude

ele is the Elevation of the GPS

time is the coordinated universal time

## Correspondence: 
Please email erikvcarlson@uri.edu with any questions or comments. 
