
.. _functional-guide/window/lotcontrol:

===========
Lot Control
===========

Product Lot Control

Help
====
Definition to create Lot numbers for Products

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Lot Control
-----------
\ **Description**\ 
 \ *Product Lot Control*\ 
\ **Help**\ 
 \ *Definition to create Lot numbers for Products*\ 

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

Start No
--------
\ **Description**\ 
 \ *Starting number/position*\ 
\ **Help**\ 
 \ *The Start Number indicates the starting position in the line or field number in the line*\ 

Increment
---------
\ **Description**\ 
 \ *The number to increment the last document number by*\ 
\ **Help**\ 
 \ *The Increment indicates the number to increment the last document number by to arrive at the next sequence number*\ 

Current Next
------------
\ **Description**\ 
 \ *The next number to be used*\ 
\ **Help**\ 
 \ *The Current Next indicates the next number to use for this document*\ 

Prefix
------
\ **Description**\ 
 \ *Prefix before the sequence number*\ 
\ **Help**\ 
 \ *The Prefix indicates the characters to print in front of the document number.*\ 

Suffix
------
\ **Description**\ 
 \ *Suffix after the number*\ 
\ **Help**\ 
 \ *The Suffix indicates the characters to append to the document number.*\ 

Exclude
-------
\ **Description**\ 
 \ *Exclude the ability to create Lots in Attribute Sets*\ 
\ **Help**\ 
 \ *Create a record, if you want to exclude the ability to create Lots in Product Attribute Set information.
Note that the information is cached. To have effect you may have to re-login or reset cache.*\ 

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

Lot Control
-----------
\ **Description**\ 
 \ *Product Lot Control*\ 
\ **Help**\ 
 \ *Definition to create Lot numbers for Products*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 
