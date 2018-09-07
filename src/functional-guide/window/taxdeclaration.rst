
.. _functional-guide/window/taxdeclaration:

===============
Tax Declaration
===============

Define the declaration to the tax authorities

Help
====
The tax declaration allows you to create supporting information and reconcile the documents with the accounting

Window Type
-----------
\ **Transaction**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Declaration
-----------
\ **Description**\ 
 \ *Define the declaration to the tax authorities*\ 
\ **Help**\ 
 \ *The tax declaration allows you to create supporting information and reconcile the documents with the accounting*\ 

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

Transaction Date
----------------
\ **Description**\ 
 \ *Transaction Date*\ 
\ **Help**\ 
 \ *The Transaction Date indicates the date of the transaction.*\ 

Date From
---------
\ **Description**\ 
 \ *Starting date for a range*\ 
\ **Help**\ 
 \ *The Date From indicates the starting date of a range.*\ 

Date To
-------
\ **Description**\ 
 \ *End date of a date range*\ 
\ **Help**\ 
 \ *The Date To indicates the end date of a range (inclusive)*\ 

Create Tax Declaration
----------------------
\ **Description**\ 
 \ *Create Tax Declaration from Documents*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Line
----
\ **Description**\ 
 \ *Tax Declaration Lines*\ 
\ **Help**\ 
 \ *The lines are created by the create process. You can delete them if you do not want to include them in a particular declaration.  You can create manual adjustment lines.*\ 

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

Tax Declaration
---------------
\ **Description**\ 
 \ *Define the declaration to the tax authorities*\ 
\ **Help**\ 
 \ *The tax declaration allows you to create supporting information and reconcile the documents with the accounting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Manual
------
\ **Description**\ 
 \ *This is a manual process*\ 
\ **Help**\ 
 \ *The Manual check box indicates if the process will done manually.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Tax base Amount
---------------
\ **Description**\ 
 \ *Base for calculating the tax amount*\ 
\ **Help**\ 
 \ *The Tax Base Amount indicates the base amount used for calculating the tax amount.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for a document*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount for a document.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Invoice Line
------------
\ **Description**\ 
 \ *Invoice Detail Line*\ 
\ **Help**\ 
 \ *The Invoice Line uniquely identifies a single line of an Invoice.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Accounting
----------
\ **Description**\ 
 \ *Tax Accounting Reconciliation*\ 
\ **Help**\ 
 \ *Displays all accounting related information for reconcilation with documents. It includes all revenue/expense and tax entries as a base for detail reporting*\ 

Fields
======

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

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

Tax Declaration
---------------
\ **Description**\ 
 \ *Define the declaration to the tax authorities*\ 
\ **Help**\ 
 \ *The tax declaration allows you to create supporting information and reconcile the documents with the accounting*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

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

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Accounted Debit
---------------
\ **Description**\ 
 \ *Accounted Debit Amount*\ 
\ **Help**\ 
 \ *The Account Debit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

Accounted Credit
----------------
\ **Description**\ 
 \ *Accounted Credit Amount*\ 
\ **Help**\ 
 \ *The Account Credit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Source Debit
------------
\ **Description**\ 
 \ *Source Debit Amount*\ 
\ **Help**\ 
 \ *The Source Debit Amount indicates the credit amount for this line in the source currency.*\ 

Source Credit
-------------
\ **Description**\ 
 \ *Source Credit Amount*\ 
\ **Help**\ 
 \ *The Source Credit Amount indicates the credit amount for this line in the source currency.*\ 
