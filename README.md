# Meteo_France_Radars

---------
> __Warning__:  
<b>For personal use at your own risk !   
This is only an amateur and personal project</b>  
---------

Decoding Bufr file from the french Meteo France data weather service : 
3 types of bufr file that you can decode with this program:
- a mosaic (France metropole) file with : Probability of Rain, Height and Horizontal Reflectivity
  or an individual radar file with : height and reflectivity
- a PAM (Multipolarized / Dual Polarization) file with : Horizontal Reflectivity (ZH), Standard Deviation Reflectivity, Correlation (ρHV), Differential Phase Shift (ΦDP) and Réflectivité Differential Reflectivity (ZDR)
- a PAG (Single Polarization) file with : Horizontal Reflectivity (ZH), Polar Standard Deviation, and True Polar Speed 

STEPS :
- free register at the official API : https://portail-api.meteofrance.fr/web/  
 
- the officials tables can be downloaded here :  
https://donneespubliques.meteofrance.fr/client/document/tables_bufr_361.zip
  --> /!\ BUT, download the tables from my directory because the official tables are not in a good format !

- then you can use my jupyter notebook (MeteoFrance_Bufr_Decoder.ipynb) to decode your bufr file (from the API : Données radar),  
you only need to change the first cell under each PROGRAM cells  
(directory and file name,  directory tables and if you want to print all the infos or only a summary)
If you want to visualize the departements contours, you need to download shapefiles from :
https://www.data.gouv.fr/fr/datasets/contours-des-departements-francais-issus-d-openstreetmap/
(or find your own appropriate shapefile)


