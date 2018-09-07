
.. _functional-guide/process/process-m_distributionrunorders:

=======================
Distribution Run Orders
=======================

Create Distribution Run Orders based on Distribution List or The Quantity Demand the Distribution Order and redistribute the quantity into Distribution Plan line items

Help
====
Based in DRP Demand is selected then the  redistribute the quantity is based in % of Demand

Please note that due to rounding, the total quantity of the order(s) is likely to be higher then the quantity entered.

Consolidate to one Document let the distribution in current Documents with ranges dates promised, if do not is selected then a new Order is generate.

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

Date Promised
-------------
\ **Description**\ 
 \ *Date Order was promised*\ 
\ **Help**\ 
 \ *The Date Promised indicates the date, if any, that an Order was promised for.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Distribution List
-----------------
\ **Description**\ 
 \ *Distribution Lists allow to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution list contain business partners and a distribution quantity or ratio for creating Orders*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Consolidate to one Document
---------------------------
\ **Description**\ 
 \ *Consolidate Lines into one Document*\ 

Based in DRP Demand
-------------------
\ **Description**\ 
 \ *Based in DRP Demand*\ 

Test
----
\ **Description**\ 
 \ *Execute in Test Mode*\ 
