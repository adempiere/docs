
.. _functional-guide/window/window-distributionrun:

================
Distribution Run
================

Distribution Run create Orders to distribute products to a selected list of partners

Help
====
Distribution Run defines how Orders are created based on Distribution Lists

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Distribution Run
----------------
\ **Description**\ 
 \ *Distribution Run create Orders to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution Run defines how Orders are created based on Distribution Lists*\ 

.. note::
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

Create Single Order
-------------------
\ **Description**\ 
 \ *For all shipments create one Order*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Create Orders
-------------
\ **Description**\ 
 \ *Create orders based on Distribution List line items*\ 
\ **Help**\ 
 \ *Please note that due to rounding, the total quantity of the order(s) is likely to be higher then the quantity entered.*\ 

Line
----
\ **Description**\ 
 \ *Distribution Run Lines define Distribution List, the Product and Quantiries*\ 
\ **Help**\ 
 \ *The order amount is based on the greater of the minimums of the product or distribution list and the quantity based on the ratio.*\ 

.. note::
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

Distribution Run
----------------
\ **Description**\ 
 \ *Distribution Run create Orders to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution Run defines how Orders are created based on Distribution Lists*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

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

Distribution List
-----------------
\ **Description**\ 
 \ *Distribution Lists allow to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution list contain business partners and a distribution quantity or ratio for creating Orders*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Minimum Quantity
----------------
\ **Description**\ 
 \ *Minimum quantity for the business partner*\ 
\ **Help**\ 
 \ *If a minimum quantity is defined, and the quantity is based on the percentage is lower, the minimum quantity is used.*\ 

Total Quantity
--------------
\ **Description**\ 
 \ *Total Quantity*\ 
