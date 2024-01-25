# Meteo_France_Radars

---------
> __Warning__:  
<b>For personal use at your own risk !   
This is only an amateur and personal project</b>  
---------

Decoding Bufr file from the french Meteo France data weather service : 

- free register at the official API : https://portail-api.meteofrance.fr/web/  
 
- you must download the bufr tables from here :  
https://donneespubliques.meteofrance.fr/client/document/tables_bufr_361.zip  

- then you can use my jupyter notebook (MeteoFrance_Bufr_Decoder.ipynb) to decode your bufr file (from the API : Données radar),  
you only need to change the first cell under the PROGRAM cell  
(directory and file name,  directory tables and if you want to print all the infos or only a summary) 
