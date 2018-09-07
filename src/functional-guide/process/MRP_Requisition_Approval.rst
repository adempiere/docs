
.. _process-mrp_requisition_approval:

====================
Requisition Approval
====================

This process allows to show the Material Requisitions planned,  which can be approved, multiple selection criterias can be defined (Warehouse, Planner, Scheduled Start Date, Required Date, Product and Business Partner).

Help
====

In the approval process is possible to modify the Scheduled Start Date, Required Date and  Quantity,  by each Material Requisition Line. You can also modify the whole selection by using the Priority and Business Partner parameters.


It is possible to convert a Material Requisition in  a Manufacturing Order , changing the Order Type parameter, The Plant, BOM and Workflow parameters. These parameters are shown so it can be defined the Manufacturing Order information.

It is possible to convert a Material Requisition in a Distribution Order, changing the Order Type, The Business Partner , Warehouse in Transit, Shipper ,  Locator source , Locator Target  parameters. These parameters are shown to define the Distribution Order information.


Parameters
==========

Order Type
----------
\ **Description**\ 
 \ *Type of Order: MRP records grouped by source (Sales Order, Purchase Order, Distribution Order, Requisition)*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Priority
--------
\ **Description**\ 
 \ *Priority of a document*\ 
\ **Help**\ 
 \ *The Priority indicates the importance (high, medium, low) of this document*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

Warehouse in Transit
--------------------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Locator To
----------
\ **Description**\ 
 \ *Location inventory is moved to*\ 
\ **Help**\ 
 \ *The Locator To indicates the location where the inventory is being moved to.*\ 

Resource (Plant)
----------------
\ **Description**\ 
 \ *Resource*\ 

BOM & Formula
-------------
\ **Description**\ 
 \ *BOM & Formula*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 
