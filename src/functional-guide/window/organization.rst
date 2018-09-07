
.. _functional-guide/window/organization:

============
Organization
============

Maintain Organizations

Help
====
The Organization Window allows you to define and maintain Organizational entities.  An Organization is often a legal entity or sub-unit for which documents and transactions are processed

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Organization
------------
\ **Description**\ 
 \ *Define Organizations*\ 
\ **Help**\ 
 \ *The Organization Tab is used to define an Organization.  Each Organization has a Key and Name and optionally a Description.  
When adding a new organization, you must re-login to be able to access the new organization.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Organization Info
-----------------
\ **Description**\ 
 \ *Organization Detail Information*\ 
\ **Help**\ 
 \ *The Organization Info Tab is used to define an Organization's address, DUNS number and Tax Identification number*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Organization Type
-----------------
\ **Description**\ 
 \ *Organization Type*\ 
\ **Help**\ 
 \ *Organization Type allows you to categorize your organizations for reporting purposes*\ 

Parent Organization
-------------------
\ **Description**\ 
 \ *Parent (superior) Organization*\ 
\ **Help**\ 
 \ *Parent Organization - the next level in the organizational hierarchy.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Drop Ship Warehouse
-------------------
\ **Description**\ 
 \ *The (logical) warehouse to use for recording drop ship receipts and shipments.*\ 
\ **Help**\ 
 \ *The drop ship warehouse will be used for recording material transactions relating to drop shipments to and from this organization.*\ 

D-U-N-S
-------
\ **Description**\ 
 \ *Dun & Bradstreet Number*\ 
\ **Help**\ 
 \ *Used for EDI - For details see   www.dnb.com/dunsno/list.htm*\ 

Tax ID
------
\ **Description**\ 
 \ *Tax Identification*\ 
\ **Help**\ 
 \ *The Tax ID field identifies the legal Identification number of this Entity.*\ 

Supervisor
----------
\ **Description**\ 
 \ *Supervisor for this user/organization - used for escalation and approval*\ 
\ **Help**\ 
 \ *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*\ 

Calendar
--------
\ **Description**\ 
 \ *Accounting Calendar Name*\ 
\ **Help**\ 
 \ *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*\ 

Phone
-----
\ **Description**\ 
 \ *Identifies a telephone number*\ 
\ **Help**\ 
 \ *The Phone field identifies a telephone number*\ 

2nd Phone
---------
\ **Description**\ 
 \ *Identifies an alternate telephone number.*\ 
\ **Help**\ 
 \ *The 2nd Phone field identifies an alternate telephone number.*\ 

Fax
---
\ **Description**\ 
 \ *Facsimile number*\ 
\ **Help**\ 
 \ *The Fax identifies a facsimile number for this Business Partner or  Location*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

CashBook for transfers
----------------------

Bank for transfers
------------------
\ **Description**\ 
 \ *Bank account depending on currency will be used from this bank for doing transfers*\ 

Receipt Footer Msg
------------------
\ **Description**\ 
 \ *This message will be displayed at the bottom of a receipt when doing a sales or purchase*\ 

Logo
----

Accounting
----------
\ **Description**\ 
 \ *Organization Accounting*\ 
\ **Help**\ 
 \ *The Organization Accounting Tab defines the default accounting parameters to be used by this Organization.*\ 

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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Inter-Organization
------------------
\ **Description**\ 
 \ *Organization valid for intercompany documents*\ 
\ **Help**\ 
 \ *The Inter Organization field identifies an Organization which can be used by this Organization for intercompany documents.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Intercompany Due From Acct
--------------------------
\ **Description**\ 
 \ *Intercompany Due From / Receivables Account*\ 
\ **Help**\ 
 \ *The Intercompany Due From account indicates the account that represents money owed to this organization from other organizations.*\ 

Intercompany Due To Acct
------------------------
\ **Description**\ 
 \ *Intercompany Due To / Payable Account*\ 
\ **Help**\ 
 \ *The Intercompany Due To Account indicates the account that represents money owed to other organizations.*\ 

Org Assignment
--------------
\ **Description**\ 
 \ *User Assigment to Organization*\ 
\ **Help**\ 
 \ *Assign Users to Organizations*\ 

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

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 
