
.. _functional-guide/process/mrp_regenerativematerialplan:

==========================
Regenerative Material Plan
==========================

This process calcualte the demand, approved and open orders for a product.

Help
====
The regenerative material plan process calculates the demands and supply for every product of the organization, warehouse and plant. This process generates a material plan even if there is no changes, since the last time it was executed.

The process check modifications in the lower levels codes, calculate the net requirements, generates planned orders and its corresponding action messages

Parameters
==========

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

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Synchronize with DRP
--------------------
