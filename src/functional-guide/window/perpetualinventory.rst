
.. _functional-guide/window/perpetualinventory:

===================
Perpetual Inventory
===================

Maintain Perpetual Inventory Rules

Help
====
The Perpetual Inventory defines the rules to be applied when generating Physical Inventory counts.

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Perpetual Inventory
-------------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Number of Inventory counts
--------------------------
\ **Description**\ 
 \ *Frequency of inventory counts per year*\ 
\ **Help**\ 
 \ *The Number of Inventory Counts indicates the number of times per year that inventory counts will be preformed*\ 

Number of Product counts
------------------------
\ **Description**\ 
 \ *Frequency of product counts per year*\ 
\ **Help**\ 
 \ *The Number of Product Count indicates the number of times per year that a product should be counted.*\ 

Count high turnover items
-------------------------
\ **Description**\ 
 \ *Count High Movement products*\ 
\ **Help**\ 
 \ *The Count High Movement checkbox indicates if the those items with a high turnover will be counted*\ 

Number of runs
--------------
\ **Description**\ 
 \ *Frequency of processing Perpetual Inventory*\ 
\ **Help**\ 
 \ *The Number of Runs indicates the number of times that the Perpetual Inventory has be processed.*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Date next run
-------------
\ **Description**\ 
 \ *Date the process will run next*\ 
\ **Help**\ 
 \ *The Date Next Run indicates the next time this process will run.*\ 

Process Now
-----------
