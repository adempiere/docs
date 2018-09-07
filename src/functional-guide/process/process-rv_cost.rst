
.. _functional-guide/process/process-rv_cost:

============
Product Cost
============

Product Cost Report

Help
====
The Product Cost  report lists the product costs for the product, cost type and cost element

Parameters
==========

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

.. note::
    The Range checkbox indicates that this parameter is a range of values.

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 
