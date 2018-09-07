
.. _functional-guide/smart-browse/smart-browse-approvalplannedmaterialrequisition:

=====================================
Approval Planned Material Requisition
=====================================

This process allows to show the Material Requisitions planned,  which can be approved, multiple selection criterias can be defined (Warehouse, Planner, Scheduled Start Date, Required Date, Product and Business Partner).

Help
====

In the approval process is possible to modify the Scheduled Start Date, Required Date and  Quantity,  by each Material Requisition Line. You can also modify the whole selection by using the Priority and Business Partner parameters.


It is possible to convert a Material Requisition in  a Manufacturing Order , changing the Order Type parameter, The Plant, BOM and Workflow parameters. These parameters are shown so it can be defined the Manufacturing Order information.

It is possible to convert a Material Requisition in a Distribution Order, changing the Order Type, The Business Partner , Warehouse in Transit, Shipper ,  Locator source , Locator Target  parameters. These parameters are shown to define the Distribution Order information.


.. seealso::
    :ref:`functional-guidewindowwindowwindow-requisition`


.. seealso::
    :ref:`functional-guideprocessprocessprocess-mrp_requisition_approval`


Fields
======


=============================  ==========================================================================  =========  ==============  ========  =========  =========
Name                           Description                                                                 Displayed  Query Criteria  Order By  Read Only  Mandatory
=============================  ==========================================================================  =========  ==============  ========  =========  =========
Material Requirement Planning  MRP ID                                                                      Yes        No              No        Yes        Yes      
Warehouse                      Storage Warehouse and Service Point                                         Yes        Yes             No        Yes        No       
Planner                        Company Agent for Planning                                                  Yes        Yes             No        Yes        No       
Document No                    Document sequence number of the document                                    Yes        No              No        Yes        Yes      
Start Schedule                 Scheduled start date for this Order                                         Yes        Yes             No        No         No       
Document Date                  Date of the Document                                                        Yes        No              No        Yes        No       
Date Required                  Date when required                                                          Yes        Yes             No        No         No       
Priority                       Indicates if this request is of a high, medium or low priority.             Yes        No              No        Yes        Yes      
Product                        Product, Service, Item                                                      Yes        Yes             No        Yes        No       
UOM                            Unit of Measure                                                             Yes        No              No        Yes        Yes      
Quantity                       Quantity                                                                    Yes        No              No        No         Yes      
Business Partner               Identifies a Business Partner                                               Yes        Yes             No        Yes        No       
Description                    Optional short description of the record                                    Yes        No              No        Yes        Yes      
Line Amount                    Line Extended Amount (Quantity * Actual Price) without Freight and Charges  Yes        No              No        Yes        Yes      
=============================  ==========================================================================  =========  ==============  ========  =========  =========
