Water: Precipitation
==================================

Precipitation
++++++++++

.. table::
  :align:   center  
  
  +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
  | .. figure:: img/img_precipitation.png                                                                               |
  |    :align:   center                                                                                                 |
  |    :width:   500 px                                                                                                 |
  +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
  | Set codification:                                       |CRENPRECIP                                                 |
  +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
  | Description:                                            |Precipitation                                              |
  +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
  | Set:                                                    |Technology                                                 |
  +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
  
TotalTechnologyAnnual Activity[r,t,y]
---------

Homogeneous precipitation per station is assumed at national level, in units of cubic kilometers per megahectare (km3/Mha). The data is based on the Regional Climate Model of the Center for Geophysical Research (CIGEFI).


.. figure::  parameters/Precipitation_TotalTechnologyAnnualActivity.png
   :align:   center
   :width:   550 px
   
   *Figure: Total Technology Annual Activity Capacity Factor* :download:`. <csv/Precipitation_TotalTechnologyAnnualActivity.csv>`

CapacityFactor[r,t,y]
---------

The Capacity Factor is the relationship given between the accumulated precipitation of each season (dry or wet) and the annual amount. This parameter is based on the following equation:

.. math::

   Capacity factor = \frac{Accumulated Annual precipitation}{Accumulated precipitation per season}
   

.. figure::  parameters/Preci_CapacityFactor.png
   :align:   center
   :width:   550 px
   
   *Figure: Precipitation Capacity Factor* :download:`. <csv/Preci_CapacityFactor.csv>`

FixCost[r,t,y]
---------

The fix cost is given in MUS$ per km3. In this case, the model assumes a 43% of the capital cost as the fixed cost. 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 188.2 [MUS$/km3]                                          |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


