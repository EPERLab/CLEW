Water:  Extraction
==================================


Superficial extraction
++++++++++

.. table::
   :align:   center  
   
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

CapitalCost[r,t,y]
---------

The capital cost is given in MUS$ per km3. This information is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA). 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          |1.26 [MUS$/km3]                                            |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

FixCost[r,t,y]
---------

The fix cost is given in MUS$ per km3. This information is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA). 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          |0.07 [MUS$/km3]                                            |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


ResidualCapacity[r,t,y]
---------

It is assumed that the residual capacity is equal to the activity of each technology. 

.. table::
   :align:   center 
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 2.924 [km3]                                               |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
 
TotalAnnualMaxCapacity[r,t,y]
---------

The data is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA).

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 2.924 [km3]                                               |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

OperationalLife[r,t,y]
---------

A 50-year lifespan was assigned to the new technologies. 



Underground extraction
++++++++++


.. table::
   :align:   center  
   
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

CapitalCost[r,t,y]
---------
The capital cost is given in MUS$ per km3. This information is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA). 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 127.6 [MUS$/km3]                                          |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

   
FixCost[r,t,y]
---------

The fix cost is given in MUS$ per km3. In this case, the model assumes a 43% of the capital cost as the fixed cost. 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 6.86 [MUS$/km3]                                           |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+


ResidualCapacity[r,t,y]
---------

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 0.45 [km3]                                                |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+

   
TotalAnnualMaxCapacity[r,t,y]
---------

The data is based on international sources and projects of the Costa Rican Institute of Aqueducts and Sewers (AYA). 

.. table::
   :align:   center  
   
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   | Constant Value                                          | 0.45 [km3]                                                |
   +-------------------------------------------------+-------+--------------+--------------+--------------+--------------+
   

