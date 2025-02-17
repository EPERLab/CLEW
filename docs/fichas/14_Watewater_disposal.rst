Water: Wastewater disposal
==================================

Wastewater disposal
++++++++++

The structure of discharges and wastewater treatment is based on the National Policy on Wastewater Sanitation Sewage. 


.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_wastewater_sewage.png                                                                           |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CRALCURB, CRALCURBFUT                                      |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Sewage                                                     |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

CapitalCost[r,t,y]
---------

The capital cost of wastewater disposal is given in MUS$ per km3. This information is based on the National Sanitation Investment Plan, which applies for both current and future technologies.


.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 723.9 MUS$/km3                                            |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

FixedCost[r,t,y]
---------

The FixedCost is based on data from the Costa Rican Institute of Aqueducts and Sewers (AYA), for current and future technologies.


.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 306.9 US$/km3                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+   

Water treatment of industrial wastewater
++++++++++

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_water_treatment_industrial.png                                                                  |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CRVTRATINDYSERV, CRVTRATFUTINDYSERV                        |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Water treatment of industrial wastewater                   |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


CapitalCost[r,t,y]
---------

The capital cost of wastewater disposal is given in MUS$ per km3. This information is based on the National Sanitation Investment Plan, which applies for both current and future technologies.

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 605.2 MUS$/km3                                            |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   
FixedCost[r,t,y]
---------

The FixedCost is based on data from the Costa Rican Institute of Aqueducts and Sewers (AYA), for current and future technologies.


.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 371.6 US$/km3                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+   
   
EmissionActivityRatio[r,t,e,m,y]
---------

The data of emissions is based on the National Inventory of Greenhouse Gases and Carbon Absorption from the National Meteorological Institute. 


.. figure::  parameters/CRVTRATINDYSERV_Emission_Act_Ratio.png
   :align:   center
   :width:   550 px
   
   *Figure: Emission Activity Ratio of Water treatment of industrial wastewater* :download:`. <csv/CRVTRATINDYSERV_Emission_Act_Ratio.csv>`

ResidualCapacity[r,t,y]
---------

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 0.035 [km3]                                               |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


Septic tank
++++++++++

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_water_septic_tank.png                                                                           |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CRPOZOSRUR, CRPOZOSRURFUT                                  |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Septic Tank                                                |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   
CapitalCost[r,t,y]
---------

The capital cost of wastewater disposal is given in MUS$ per km3. This information is based on the National Sanitation Investment Plan, which applies for both current and future technologies.

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 49.78  MUS$/km3                                           |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   
FixedCost[r,t,y]
---------

The FixedCost is based on data from the Costa Rican Institute of Aqueducts and Sewers (AYA), for current and future technologies.

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 306.9 US$/km3                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

EmissionActivityRatio[r,t,e,m,y]
---------

The data of emissions is based on the National Inventory of Greenhouse Gases and Carbon Absorption from the National Meteorological Institute. 

.. figure::  parameters/CRPOZOSRUR_Emission_Act_Ratio.png
   :align:   center
   :width:   550 px
   
   *Figure: Emission Activity Ratio of Septic tanks* :download:`. <csv/CRPOZOSRUR_Emission_Act_Ratio.csv>`
   

AnnualActivityLowerLimit[r,t,e,m,y]
---------

The Annual Activity is based on information from the National Policy on Wastewater Sanitation, as well as information from the BCCR Water Account 2015. 

.. figure::  parameters/CRPOZOSRURFUT_Activity_Lo.png
   :align:   center
   :width:   550 px
   
   *Figure: Annual Activity Lower Limit of Septic tanks* :download:`. <csv/CRPOZOSRURFUT_Activity_Lo.csv>`
   
Water treatment of wastewater from human consumption
++++++++++


.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_water_treatment_residential.png                                                                 |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CRVTRATCOHUMANO, CRVTRATFUTCOHUMANO                        |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Water treatment of wastewater from human consumption       |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

CapitalCost[r,t,y]
---------

The capital cost of wastewater disposal is given in MUS$ per km3. This information is based on the National Sanitation Investment Plan, which applies for both current and future technologies.


.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 605.2 MUS$/km3                                            |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

FixedCost[r,t,y]
---------

The FixedCost is based on data from the Costa Rican Institute of Aqueducts and Sewers (AYA), for current and future technologies.

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 371.6 US$/km3                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

EmissionActivityRatio[r,t,e,m,y]
---------

The data of emissions is based on the National Inventory of Greenhouse Gases and Carbon Absorption from the National Meteorological Institute. 



.. figure::  parameters/CRVTRATCOHUMANO_Emission_Act_Ratio.png
   :align:   center
   :width:   550 px
   
   *Figure: Emission Activity Ratio of Water treatment of wastewater from human consumption* :download:`. <csv/CRVTRATCOHUMANO_Emission_Act_Ratio.csv>`


ResidualCapacity[r,t,y]
---------

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 0.033 [km3]                                               |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

AnnualActivityLowerLimit[r,t,e,m,y]
---------

.. figure::  parameters/CRVTRATFUTCOHUMANO_Activity_Lo.png
   :align:   center
   :width:   550 px
   
   *Figure: Annual Activity Lower Limit of Water treatment of wastewater from human consumption* :download:`. <csv/CRVTRATFUTCOHUMANOActivity_Lo.csv>`

Water without treatment
++++++++++

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_disposal_no_treatment.png                                                                       |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CRVSINTRATCOHUMANO, CRVSINTRATINDYSERV                     |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Water without treatment                                    |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


EmissionActivityRatio[r,t,e,m,y]
---------

The data of emissions is based on the National Inventory of Greenhouse Gases and Carbon Absorption from the National Meteorological Institute, for both current and future technologies.


.. figure::  parameters/CRVSINTRAT_Emission_Act_Ratio.png
   :align:   center
   :width:   550 px
   
   *Figure: Emission Activity Ratio of Water without treatment* :download:`. <csv/CRVSINTRAT_Emission_Act_Ratio.csv>`


