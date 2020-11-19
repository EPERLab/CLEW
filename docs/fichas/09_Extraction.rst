Water:  Extraction
==================================

Superficial extraction
++++++++++

+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| .. figure:: img/img_extraction.png                                                                                  |
|    :align:   center                                                                                                 |
|    :width:   500 px                                                                                                 |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Set codification:                                       |CREXTSUP                                                   |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Description:                                            |Superficial extraction                                     |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Set:                                                    |Technology                                                 |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

OutputActivityRatio[r,t,y]
---------

This parameter represents the crop yield. This parameter is based on historical data from reports of the Executive Secretariat for Agricultural Sector Planning. In the BAU scenario, the crop yield increase according to the historical data. In the NDP scenario, the increase is greater since better production practices are put into place.  

.. figure::  parameters/Rice_OAR.png
   :align:   center
   :width:   550 px
   
   *Figure: Output Activity Ratio of Rice Production* :download:`. <csv/Rice_OAR.csv>`

ResidualCapacity[r,t,y]
---------


.. math::

   \frac{Area(year-1) -  Area(year)}{Operational\ life}. 
   
In the case of rice crops, their operational life is 1 year. 

+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Constant Value                                                                                                      |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| 1.2                                                                                                                 |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

.. note:: This is a note.

.. warning:: Beware of dragons.

Underground extraction
++++++++++

+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| .. figure:: img/img_extraction_underground.png                                                                      |
|    :align:   center                                                                                                 |
|    :width:   500 px                                                                                                 |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Set codification:                                       |CREXTSUB                                                   |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Description:                                            |Underground extraction                                     |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
| Set:                                                    |Technology                                                 |
+-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
