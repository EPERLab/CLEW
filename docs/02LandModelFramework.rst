2. Land model: Framework 
=======================================

This documentation has been created in order to provide an overview of CLEW-CR. Therefore, it presents the model structure, and gives a synthesis of the key assumptions of the model, regarding the numerical inputs used for the sets, parameters, and scenario building. First, in this section, we give an insight to the general framework of the model.

2.1 General model structure 
+++++++++

.. figure::  doc_imgs/Land_diagram.PNG
   :align:   center
   :width:   550 px
   
   *Figure: Forest* 


2.2 Sets 
+++++++++

The sets are responsible for defining the structure of the model (i.e. temporal space, geographic space, elements of the system, etc.). In OSeMOSYS, the group of sets include: years, fuels, technologies, emissions and modes of operation. As it going to be further explained, the sets are characterized through parameters. These subsections present the sets that compose the current version of OSeMOSYS-CR.  

2.2.1 Year
---------

This corresponds to the period of analysis. For OSeMOSYS-CR it is from 2015 to 2050. However, the data from 2015 to 2018 is set acccording to historical information. 

2.2.2 Fuels
---------

2.2.3 Technologies
---------

2.2.4 Emissions
---------
+---------------------+--------------------------------------------------+
| Emission            | Description                                      |
+=====================+==================================================+
|CR02_LULUCF_ABS      | L_Forest removals                                |
+---------------------+--------------------------------------------------+
|CR02_LULUCF_EMI      | L_Land use change emissions                      |
+---------------------+--------------------------------------------------+
|CRCO2_EQ_ESTIERCOL   | L_Eq carbon dioxide manure management            |
+---------------------+--------------------------------------------------+
|CRCO2_EQ_FERMEN      | L_Eq carbon dioxide from enteric fermentation    |
+---------------------+--------------------------------------------------+
|CRCO2_ABS_P_FOR      | L_Removals from forest plantations               |
+---------------------+--------------------------------------------------+
|CRCO2_CULTIVOS       | L_Emissions from crops                           |
+---------------------+--------------------------------------------------+
|SE_DRY_Forest        | L_Ecosystem services from dry forest             |
+---------------------+--------------------------------------------------+
|SE_MANGRO_Forest     | L_Ecosystem servoces from Mangroves              |
+---------------------+--------------------------------------------------+
|SE_PALM_Fosrest      | L_Ecosystem services from Palm Forest            |
+---------------------+--------------------------------------------------+
|SE_WET_MOIST_Forest  | L_Ecosystem services from Moist Forest           |
+---------------------+--------------------------------------------------+

2.2.5 Mode of operation
---------
    
The model has one mode of operation, Mode 1, for representing the normal operation of the system.

2.2.6 Region
---------
    
The model has a nationwide scope, therefore it only has one region: Costa Rica (CR). 
  
