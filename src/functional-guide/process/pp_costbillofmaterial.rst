
.. _functional-guide/process/pp_costbillofmaterial:

===========================
Cost BOM Multi Level Review
===========================

This report show every cost element to a Multi Level BOM or Formula 

Help
====
This report show every cost element to a Multi Level BOM or Formula 

Parameters
==========

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Costing Method
--------------
\ **Description**\ 
 \ *Indicates how Costs will be calculated*\ 
\ **Help**\ 
 \ *The Costing Method indicates how costs will be calculated (Standard, Average, Lifo, FiFo).  The default costing method is defined on accounting schema level and can be optionally overwritten in the product category.  The costing method cannot conflict with the Material Movement Policy (defined on Product Category).*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
