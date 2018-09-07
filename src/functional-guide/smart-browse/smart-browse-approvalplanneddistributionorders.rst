
.. _functional-guide/smart-browse/smart-browse-approvalplanneddistributionorders:

=====================================
Approval  Planned Distribution Orders
=====================================

This process allows to show  the planned Distribution Orders which can be approved.

Help
====
Can define multiple selection criteria (Warehouse, Planner, Business Partner, Delivery Via, Delivery Rule, Shipper, Promised Date,  Source Location, Target Location and Product).

 In the approval process is possible to modify on an individual base,  the Promised Date, Quantity and Confirmed Quantity of the Distribution Order Line, it is also possible to modify the whole selection,  by using the parameters Priority, Shipper and Business Partner.

It is possible to change a Distribution Order into  a Manufacturing  Order, by using the Order Type, Business Partner, Plant, BOM and Workflow parameters. These parameters are shown to define the Manufacturing Order information.

It is possible to change a Manufacturing Order into a Material Requisition by using the Order Type and Business Partner parameters. These  parameters are shown to define the Material Requisition information.

.. seealso::
    :ref:`functional-guidewindowwindowwindow-distributionorder`


.. seealso::
    :ref:`functional-guideprocessprocessprocess-mrp_distribution_order_approval`


Fields
======


=============================  ===============================================================  =========  ==============  ========  =========  =========
Name                           Description                                                      Displayed  Query Criteria  Order By  Read Only  Mandatory
=============================  ===============================================================  =========  ==============  ========  =========  =========
Material Requirement Planning  MRP ID                                                           Yes        No              No        Yes        Yes      
Warehouse                      Storage Warehouse and Service Point                              Yes        Yes             No        Yes        No       
Planner                        Company Agent for Planning                                       Yes        Yes             No        Yes        No       
Business Partner               Identifies a Business Partner                                    Yes        Yes             No        Yes        No       
Delivery Via                   How the order will be delivered                                  Yes        Yes             No        Yes        No       
Delivery Rule                  Defines the timing of Delivery                                   Yes        Yes             No        Yes        No       
Shipper                        Method or manner of product delivery                             Yes        Yes             No        Yes        No       
Document No                    Document sequence number of the document                         Yes        No              No        Yes        Yes      
Date Ordered                   Date of Order                                                    Yes        No              No        Yes        No       
Date Promised                  Date Order was promised                                          Yes        Yes             No        Yes        No       
Priority                       Indicates if this request is of a high, medium or low priority.  Yes        No              No        Yes        Yes      
Locator                        Warehouse Locator                                                Yes        Yes             No        Yes        No       
Locator To                     Location inventory is moved to                                   Yes        Yes             No        Yes        No       
Product                        Product, Service, Item                                           Yes        Yes             No        Yes        No       
UOM                            Unit of Measure                                                  Yes        No              No        Yes        Yes      
Quantity                       Quantity                                                         Yes        No              No        No         Yes      
Confirmed Quantity             Confirmation of a received quantity                              Yes        No              No        No         Yes      
Description                    Optional short description of the record                         Yes        No              No        Yes        Yes      
=============================  ===============================================================  =========  ==============  ========  =========  =========
