
.. _window-edidefinition:

==============
EDI Definition
==============

Maintain EDI Definition

Help
====
The EDI Definition Window defines the parameters to be used when processing EDI Transactions

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

EDI Definition
--------------
\ **Description**\ 
 \ *Maintain EDI Definition*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

EDI Type
--------

Send Inquiry
------------
\ **Description**\ 
 \ *Quantity Availability Inquiry*\ 

Received Inquiry Reply
----------------------

Send Order
----------

Receive Order Reply
-------------------

Customer No
-----------
\ **Description**\ 
 \ *EDI Identification Number*\ 

Sequence
--------
\ **Description**\ 
 \ *Document Sequence*\ 
\ **Help**\ 
 \ *The Sequence defines the numbering sequence to be used for documents.*\ 

To EMail
--------
\ **Description**\ 
 \ *EMail address to send requests to - e.g. edi@manufacturer.com*\ 

From EMail
----------
\ **Description**\ 
 \ *Full EMail address used to send requests - e.g. edi@organization.com*\ 

From EMail User ID
------------------
\ **Description**\ 
 \ *User ID of the sending EMail address (on default SMTP Host) - e.g. edi*\ 

From EMail Password
-------------------
\ **Description**\ 
 \ *Password of the sending EMail address*\ 

Activate Audit
--------------
\ **Description**\ 
 \ *Activate Audit Trail of what numbers are generated*\ 
\ **Help**\ 
 \ *The Activate Audit checkbox indicates if an audit trail of numbers generated will be kept.*\ 

Error EMail
-----------
\ **Description**\ 
 \ *Email address to send error messages to*\ 

Send Info
---------
\ **Description**\ 
 \ *Send informational messages and copies*\ 

Info EMail
----------
\ **Description**\ 
 \ *EMail address to send informational messages and copies*\ 
\ **Help**\ 
 \ *The Info EMail address indicates the address to use when sending informational messages or copies of other messages.*\ 
