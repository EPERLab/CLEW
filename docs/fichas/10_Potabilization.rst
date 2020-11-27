Water: Potibilization
==================================

The water treatment inputs correspond to the proportion of superficial and underground extraction that is carried out for this activity. Similarly, the activity requires an energy component, which is entered in units of petajoules per cubic kilometer (PJ/km3). These data is assigned to current and future technologies and remained constant throughout the time series. 

Potabilization
++++++++++

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | .. figure:: img/img_potabilization.png                                                                              |
   |    :align:   center                                                                                                 |
   |    :width:   500 px                                                                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set codification:                                       |CREPOT                                                     |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Description:                                            |Potabilization                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Set:                                                    |Technology                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

CapitalCost[r,t,y]
---------

The capital cost is given in MUS$ per km3. This information is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA). 

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 49.62 [km3]                                               |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

FixedCost[r,t,y]
---------

The FixedCost is based on data from the Costa Rican Institute of Aqueducts and Sewers (AYA), for current and future technologies.


.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 188.2 US$/km3                                             |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

ResidualCapacity[r,t,y]
---------

It is assumed that the residual capacity is equal to the activity of each technology. 

.. table::
   :align:   center  

   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 0.7 [km3]                                                 |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


EmissionActivityRatio[r,t,e,m,y]
---------

The data of emissions is based on the National Inventory of Greenhouse Gases and Carbon Absorption from the National Meteorological Institute (IMN). 


.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 1 [MtonCO2eq/km3]                                         |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

