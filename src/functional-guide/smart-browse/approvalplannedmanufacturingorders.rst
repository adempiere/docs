
.. _functional-guide/smart-browse/approvalplannedmanufacturingorders:

=====================================
Approval Planned Manufacturing Orders
=====================================

This process allows to show  the Planned Manufacturing Orders which can be approved, it is possible to define multiple selection criteria (Plant, Warehouse, Scheduled Start Date, Promised Date, Planner, BOM and Workflow).

Help
====
In the approval process is possible to modify on an individual base,  the Scheduled Start Date, Promised Date, and Quantity for each Manufacturing Order. You can also modify the whole selection,  by using the parameters Priority , BOM and Workflow.

It is possible to convert a Manufacturing Order into a Material Requisition  by using the Order Type and  Business Partner parameters. These parameters  are shown to define the Material Requisition information.

It is possible to convert a Manufacturing Order into a  Distribution Order by using the Order Type, Business Partner , Warehouse in Transit, Shipper, Source Locator and Target  Locator  parameters. These parameters are shown to define the Distribution Order information.


.. seealso::
    :ref:`functional-guidewindow-manufacturingorder`


.. seealso::
    :ref:`functional-guideprocess-mrp_manufacturing_order_approval`


Fields
======


=============================  ===================================================================  =========  ==============  ========  =========  =========
Name                           Description                                                          Displayed  Query Criteria  Order By  Read Only  Mandatory
=============================  ===================================================================  =========  ==============  ========  =========  =========
Material Requirement Planning  MRP ID                                                               Yes        No              No        Yes        Yes      
Resource                       Resource                                                             Yes        Yes             No        Yes        No       
Warehouse                      Storage Warehouse and Service Point                                  Yes        Yes             No        Yes        No       
Start Schedule                 Scheduled start date for this Order                                  Yes        Yes             No        No         No       
Finish Schedule                Scheduled Finish date for this Order                                 Yes        No              No        Yes        Yes      
Date Promised                  Date Order was promised                                              Yes        Yes             No        No         No       
Priority                       Indicates if this request is of a high, medium or low priority.      Yes        No              No        Yes        Yes      
Planner                        Company Agent for Planning                                           Yes        Yes             No        Yes        No       
Is MPS                         Indicates if this product is part of the master production schedule  Yes        Yes             No        Yes        No       
Product                        Product, Service, Item                                               Yes        Yes             No        Yes        No       
UOM                            Unit of Measure                                                      Yes        No              No        Yes        Yes      
BOM & Formula                  BOM & Formula                                                        Yes        Yes             No        Yes        No       
Workflow                       Workflow or combination of tasks                                     Yes        Yes             No        Yes        No       
Quantity                       Quantity                                                             Yes        No              No        No         Yes      
Qty Batchs                                                                                          Yes        No              No        Yes        Yes      
Qty Batch Size                                                                                      Yes        No              No        Yes        Yes      
Description                    Optional short description of the record                             Yes        No              No        Yes        Yes      
=============================  ===================================================================  =========  ==============  ========  =========  =========
