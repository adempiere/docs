
.. _process-transactionvaluation:

=====================
Transaction Valuation
=====================

Transaction Valuation

Help
====
This report shows the history  transactions with quantities and cost for each product for any Cost Type, such as Standard, Average, FIFO / LIFO


Parameters
==========

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

.. note::
    The Range checkbox indicates that this parameter is a range of values.

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

.. note::
    The Range checkbox indicates that this parameter is a range of values.

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 
