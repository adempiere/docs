
.. _functional-guide/window/window-replenishplanrun:

==================
Replenish Plan Run
==================


Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Run
---

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Date Start
----------
\ **Description**\ 
 \ *Date Start for this Order*\ 

Finish Date
-----------
\ **Description**\ 
 \ *Finish or (planned) completion date*\ 
\ **Help**\ 
 \ *The finish date is used to indicate when the project is expected to be completed or has been completed.*\ 

Delete Unconfirmed Production
-----------------------------

Delete Planned Purchase Orders
------------------------------

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Planned Mfg Order Doc Type
--------------------------

Confirmed Mfg Order Doc Type
----------------------------

Replenish Plan Requisition Doc Type
-----------------------------------

Purchase Order Doc Type
-----------------------

Replenish Plan Initial Setup
----------------------------
\ **Description**\ 
 \ *Initial setup to get you started in Replenish Plan*\ 

Replenish Plan Report
---------------------
\ **Description**\ 
 \ *Replenish Plan Report*\ 
\ **Help**\ 
 \ *Replenish Plan Calculation*\ 

Replenish Plan Generate Report
------------------------------

Replenish Plan Production Report
--------------------------------
\ **Description**\ 
 \ *Showing report of Planned Production generated from current Replenish Plan Run.*\ 

Replenish Plan Requisition Report
---------------------------------
\ **Description**\ 
 \ *Showing report of Suggested Requisition generated from current Replenish Plan Run.*\ 

Lines
-----

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

M_ReplenishPlan ID
------------------

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Date Start
----------
\ **Description**\ 
 \ *Date Start for this Order*\ 

Finish Date
-----------
\ **Description**\ 
 \ *Finish or (planned) completion date*\ 
\ **Help**\ 
 \ *The finish date is used to indicate when the project is expected to be completed or has been completed.*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Production
----------
\ **Description**\ 
 \ *Plan for producing a product*\ 
\ **Help**\ 
 \ *The Production uniquely identifies a Production Plan*\ 

Requisition
-----------
\ **Description**\ 
 \ *Material Requisition*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Name
------------
\ **Description**\ 
 \ *Name of the Product*\ 

RecordType
----------

Week1
-----

Week2
-----

Week3
-----

Week4
-----

Week5
-----

Week6
-----

Week7
-----

Week8
-----

Week9
-----

Week10
------

Week11
------

Week12
------

Week13
------

Week14
------

Week15
------

Week16
------

Week17
------

Week18
------

Week19
------

Week20
------

Week21
------

Week22
------

Week23
------

Week24
------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
