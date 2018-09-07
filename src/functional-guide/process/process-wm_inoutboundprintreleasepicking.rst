
.. _functional-guide/process/process-wm_inoutboundprintreleasepicking:

==============================
Release & Print Outbound Order
==============================

This process generate the Picking lists in order to prepare for shipping, thus allowing one or serveral distribution orders to be generated as a result of the Inbound/Outbound Strategies previously defined in the Inbound/Outbound Definition window.

Help
====
Those Distribuition Orders are generated from different locations based on the Picking rules from the Inbound/Outbound Strategy.

Once the Picking process is completed the process to generate shipments can be fulfilled.

Parameters
==========

Warehouse Area Type
-------------------
\ **Description**\ 
 \ *Warehouse Area Type allow grouping the Warehouse Area for Type*\ 

Warehouse Section Type
----------------------

Outbound Locator
----------------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located to pick.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Delivery Rule
-------------
\ **Description**\ 
 \ *Defines the timing of Delivery*\ 
\ **Help**\ 
 \ *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*\ 

Delivery Via
------------
\ **Description**\ 
 \ *How the order will be delivered*\ 
\ **Help**\ 
 \ *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*\ 

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Freight Cost Rule
-----------------
\ **Description**\ 
 \ *Method for charging Freight*\ 
\ **Help**\ 
 \ *The Freight Cost Rule indicates the method used when charging for freight.*\ 

Freight Category
----------------
\ **Description**\ 
 \ *Category of the Freight*\ 
\ **Help**\ 
 \ *Freight Categories are used to calculate the Freight for the Shipper selected*\ 

Is Print Pick List
------------------
\ **Description**\ 
 \ *Indicate if a Pick List is print*\ 
\ **Help**\ 
 \ *When you select this checkbox a Pick list is printed*\ 

Is Create Supply
----------------
\ **Description**\ 
 \ *Create supply for product not available*\ 
\ **Help**\ 
 \ *Allow create Manufacturing Order or Requisition Material for product not available*\ 
