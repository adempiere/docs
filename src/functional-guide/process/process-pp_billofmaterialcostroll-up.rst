
.. _functional-guide/process/process-pp_billofmaterialcostroll-up:

=======================================
Bill of Material & Formula Cost Roll-UP
=======================================

This Process allow integrate Bill of Material & Formula Cost

Help
====
This Process allow integrate Bill of Material & Formula Cost

Element Cost = Element Cost this level + Element Cost this low level 

Total BOM Cost = Sum every Element Cost

Parameters
==========

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Resource Plant
--------------
\ **Description**\ 
 \ *Resource Plant*\ 

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

Product Class
-------------
\ **Description**\ 
 \ *Class of a Product*\ 
\ **Help**\ 
 \ *Identifies the Class which this product belongs to*\ 

Product Group
-------------
\ **Description**\ 
 \ *Group of a Product*\ 
\ **Help**\ 
 \ *Identifies the Group which this product belongs to.*\ 

Product Classification
----------------------
\ **Description**\ 
 \ *Classification of a Product*\ 
\ **Help**\ 
 \ *Identifies the classification which this product belongs to.*\ 

Product Type
------------
\ **Description**\ 
 \ *Type of product*\ 
\ **Help**\ 
 \ *The type of product also determines accounting consequences.*\ 
