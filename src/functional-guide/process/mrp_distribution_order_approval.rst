
.. _functional-guide/process/mrp_distribution_order_approval:

===========================
Distribution Order Approval
===========================

This process allows to show  the planned Distribution Orders which can be approved.

Help
====
Can define multiple selection criteria (Warehouse, Planner, Business Partner, Delivery Via, Delivery Rule, Shipper, Promised Date,  Source Location, Target Location and Product).

 In the approval process is possible to modify on an individual base,  the Promised Date, Quantity and Confirmed Quantity of the Distribution Order Line, it is also possible to modify the whole selection,  by using the parameters Priority, Shipper and Business Partner.

It is possible to change a Distribution Order into  a Manufacturing  Order, by using the Order Type, Business Partner, Plant, BOM and Workflow parameters. These parameters are shown to define the Manufacturing Order information.

It is possible to change a Manufacturing Order into a Material Requisition by using the Order Type and Business Partner parameters. These  parameters are shown to define the Material Requisition information.

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

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

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
