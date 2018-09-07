
.. _functional-guide/window/cashbook:

========
Cashbook
========

Maintain Cashbook

Help
====
The Cashbook Window defines the bank and account against which cash transactions will be processed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Cashbook
--------
\ **Description**\ 
 \ *Maintain Cashbook*\ 
\ **Help**\ 
 \ *The Cashbook Tab defines a unique cashbook for an organization.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Accounting
----------
\ **Description**\ 
 \ *Cashbook Accounting*\ 
\ **Help**\ 
 \ *The Cashbook Accounting Tab defines the accounting parameters for transaction involving a cashbook.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Cash Book
---------
\ **Description**\ 
 \ *Cash Book for recording petty cash transactions*\ 
\ **Help**\ 
 \ *The Cash Book identifies a unique cash book.  The cash book is used to record cash transactions.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Cash Book Asset
---------------
\ **Description**\ 
 \ *Cash Book Asset Account*\ 
\ **Help**\ 
 \ *The Cash Book Asset Account identifies the account to be used for recording payments into and disbursements from this cash book.*\ 

Cash Book Differences
---------------------
\ **Description**\ 
 \ *Cash Book Differences Account*\ 
\ **Help**\ 
 \ *The Cash Book Differences Account identifies the account to be used for recording any differences that affect this cash book*\ 

Cash Transfer
-------------
\ **Description**\ 
 \ *Cash Transfer Clearing Account*\ 
\ **Help**\ 
 \ *Account for Invoices paid by cash*\ 

Cash Book Expense
-----------------
\ **Description**\ 
 \ *Cash Book Expense Account*\ 
\ **Help**\ 
 \ *The Cash Book Expense Account identifies the account to be used for general, non itemized expenses.*\ 

Cash Book Receipt
-----------------
\ **Description**\ 
 \ *Cash Book Receipts Account*\ 
\ **Help**\ 
 \ *The Cash Book Receipt Account identifies the account to be used for general, non itemized cash book receipts.*\ 
