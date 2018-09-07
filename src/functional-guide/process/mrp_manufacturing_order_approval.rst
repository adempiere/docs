
.. _functional-guide/process/mrp_manufacturing_order_approval:

============================
Manufacturing Order Approval
============================

This process allows to show  the Planned Manufacturing Orders which can be approved, it is possible to define multiple selection criteria (Plant, Warehouse, Scheduled Start Date, Promised Date, Planner, BOM and Workflow).

Help
====
In the approval process is possible to modify on an individual base,  the Scheduled Start Date, Promised Date, and Quantity for each Manufacturing Order. You can also modify the whole selection,  by using the parameters Priority , BOM and Workflow.

It is possible to convert a Manufacturing Order into a Material Requisition  by using the Order Type and  Business Partner parameters. These parameters  are shown to define the Material Requisition information.

It is possible to convert a Manufacturing Order into a  Distribution Order by using the Order Type, Business Partner , Warehouse in Transit, Shipper, Source Locator and Target  Locator  parameters. These parameters are shown to define the Distribution Order information.


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

Warehouse In Transit
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
