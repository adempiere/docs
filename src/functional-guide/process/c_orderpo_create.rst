
.. _functional-guide/process/c_orderpo_create:

============================
Generate PO from Sales Order
============================

Create Purchase Order from Sales Orders

Help
====
After completing sales orders, you can create one or more purchase orders for each sales order. A purchase order references always only one sales order (i.e. no consolidation of sales orders). 
The Organization of the Sales Order is used to create the Purchase Order. If a (default) PO document type is defined on Organization level, that is used instead of the document types defined on Client level.

POs are created for all sales order lines where the product has a current vendor, the vendor has a Vendor Price List with all Products on the most current Price List Version. The Unit of Measure is copied; PO and SO can have different currencies.

Once the process is run, you need to synchronize the SO/PO manually (e.g. in case of additional lines and changed lines (product & quantity).

Parameters
==========

Date Ordered
------------
\ **Description**\ 
 \ *Date of Order*\ 
\ **Help**\ 
 \ *Indicates the Date an item was ordered.*\ 

.. note::
    The Range checkbox indicates that this parameter is a range of values.

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Vendor
------
\ **Description**\ 
 \ *The Vendor of the product/service*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Drop Shipment
-------------
\ **Description**\ 
 \ *Drop Shipments are sent from the Vendor directly to the Customer*\ 
\ **Help**\ 
 \ *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*\ 
