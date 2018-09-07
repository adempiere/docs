
.. _functional-guide/smart-browse/forecastsimulationresult:

==========================
Forecast Simulation Result
==========================

The forecast simulation browser allows to compare base period data with the simulation result of the target period, after executing a forecast simulation.

Help
====
The goal of this query is to validate that the results are considered in the company plans.

.. seealso::
    :ref:`functional-guidewindow-forecastsimulation`


.. note::
    Flag to indicate if is collapsible by default

Fields
======


======================  =========================================================================================  =========  ==============  ========  =========  =========
Name                    Description                                                                                Displayed  Query Criteria  Order By  Read Only  Mandatory
======================  =========================================================================================  =========  ==============  ========  =========  =========
Forecast Run            Create the forecast simulation based on the forecast definition                            Yes        Yes             No        Yes        Yes      
Organization            Organizational entity within client                                                        Yes        No              No        Yes        No       
Document No             Document sequence number of the document                                                   Yes        No              No        Yes        No       
Description             Optional short description of the record                                                   Yes        No              No        Yes        No       
Past Period Definition  Period Definition, allows to define time cycles for the Operational Calendar               Yes        Yes             No        Yes        Yes      
Current Period          Period Definition, allows to define time cycles for the Operational Calendar               Yes        Yes             No        Yes        Yes      
Source Warehouse        Optional Warehouse to replenish from                                                       Yes        No              No        Yes        No       
Periods of History      Number Period of History                                                                   Yes        No              No        Yes        No       
Warehouse               Storage Warehouse and Service Point                                                        Yes        No              No        Yes        No       
Forecast Rule           Forecast Rules define the business logic according to a previously implemented algorithm.  Yes        No              No        Yes        No       
Product                 Product, Service, Item                                                                     Yes        Yes             No        Yes        No       
Product Category        Category of a Product                                                                      Yes        Yes             No        Yes        No       
Product Group           Group of a Product                                                                         Yes        Yes             No        Yes        No       
Product Classification  Classification of a Product                                                                Yes        Yes             No        Yes        No       
Product Class           Class of a Product                                                                         Yes        Yes             No        Yes        No       
Factor Alpha            Identifies an Factor Alpha                                                                 Yes        No              No        Yes        No       
Factor Gamma            Identifies a Factor Gamma                                                                  Yes        No              No        Yes        No       
Factor Multiplier       Identifies a Factor Multiplier                                                             Yes        No              No        Yes        No       
Factor Scale            Identifies a Factor Scale                                                                  Yes        No              No        Yes        No       
Past Period             Forecast Definition Periods.                                                               Yes        No              No        Yes        Yes      
Operational Period      Forecast Definition Periods.                                                               Yes        No              No        Yes        Yes      
======================  =========================================================================================  =========  ==============  ========  =========  =========
