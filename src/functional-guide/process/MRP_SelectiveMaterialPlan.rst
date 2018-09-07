
.. _process-mrp_selectivematerialplan:

=======================
Selective Material Plan
=======================

The process of Selective Material Plan calculates the demands and supplies for the selected products.

Help
====
This process can be executed in net change mode if you select the products with the MRP required flag, or in regenerative mode if you do not select any criteria. This process may be also  selected to figure out the Master production Schedule, selecting the master production planning products, it can be selected a product category, for  purchasing or manufacturing products or for a specific planner.

Parameters
==========

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Synchronize with DRP
--------------------

Is MPS
------
\ **Description**\ 
 \ *Indicates if this product is part of the master production schedule*\ 
\ **Help**\ 
 \ *The independent demand products such as end products or spare parts, should be part of the MPS.


This flag is used to segregate the products to be used in reports and inquiries of the MPS and allows to calculate the MPS by the execution of a selective MRP process.*\ 

Is MRP Required
---------------
\ **Description**\ 
 \ *Is MRP Required*\ 
\ **Help**\ 
 \ *If the MRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e BOM, Orders, Inventory, MPS, etc. and therefore  you need to executed again MRP to adjust the Planned Orders to the new conditions and to get the updated action messages.*\ 

Is DRP Required
---------------
\ **Description**\ 
 \ *Is DRP Required*\ 
\ **Help**\ 
 \ *If the DRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e Network Distribution, Orders, Inventory, MPS, etc. and therefore  you need to executed again DRP to adjust the Planned Orders to the new conditions and to get the updated action messages.*\ 

Bill of Materials
-----------------
\ **Description**\ 
 \ *Bill of Materials*\ 
\ **Help**\ 
 \ *The Bill of Materials check box indicates if this product consists of a bill of materials.*\ 

Purchased
---------
\ **Description**\ 
 \ *Organization purchases this product*\ 
\ **Help**\ 
 \ *The Purchased check box indicates if this product is purchased by this organization.*\ 

Calculate Low Level
-------------------
\ **Description**\ 
 \ *The Low Level is used to calculate the material plan and determines if a net requirement should be exploited*\ 

Planner
-------
\ **Description**\ 
 \ *Company Agent for Planning*\ 
\ **Help**\ 
 \ *The Master Planner indicates the company agent in charge of the MPS management. Any Master Planner must be a valid internal user.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

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
