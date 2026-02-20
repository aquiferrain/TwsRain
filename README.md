# TwsRain

This is which data files we are using
This is where we put the gee code for downloading the data into csv
This is for the csv files that we create
This is for python programs that run var and granger causality


DATA

We use GLDAS-2.2 for getting soil moisture 0-2m, and tws_groundwater. Its measured in mm

In GEE - TWS2mGLDAS2.2 . This uses the CLSM GLDAS2.2 to calc the tws_200_mm (there is also a tws_200_grace_mm which uses the tws from the Grace part), it also calcs rain_mm, et_mm,t_mm,tws_mm (from grace)

DATA CSV FILES
A.BF_Gldas2.2_13.5N2.5E_2003-07_2025-12  contains the calc from TWS2mGLDAS2.2 . With the tws_200_mm from GLDAS2.2, rain from CHIRPS, et, T from GLDAS2.2, tws from grace, tws_200_grace_mm from tws(grace) subtract soil(0-2m) from gldas2.2

LOCATIONS

We are looking at 13.5N latitude line

Congo .5N 20E

PROCESSED DATASETS

GEE- TWS2mGLDASNOAH  gives data from GLDAS NOAH for tws >2m depth. it also printed out soil moisture up to 2m. 'tws_200-mm' and 'soil_200_m'

ChadGLdNoa_13.5_18.5_2001-01-2019-01


