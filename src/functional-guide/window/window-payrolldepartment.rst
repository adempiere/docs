
.. _functional-guide/window/window-payrolldepartment:

==================
Payroll Department
==================

Maintain Payroll Department

Help
====
The Payroll Departament Window is used to define the Organizational Structure for Company

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Department
----------
\ **Description**\ 
 \ *Payroll Department definition*\ 
\ **Help**\ 
 \ *The Payroll Department Tab defines the Value,  Name, Description for a Payroll Department*\ 

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

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Manager
-------
\ **Description**\ 
 \ *Identifies a Manager*\ 
\ **Help**\ 
 \ *Identifies a Manager. The Manager must be identified as a business partner*\ 

Current Strength
----------------
\ **Description**\ 
 \ *Current Strength*\ 

Stregth Required
----------------
\ **Description**\ 
 \ *Stregth Required*\ 
\ **Help**\ 
 \ *The Stregth Required*\ 

Consumption Limit
-----------------
\ **Description**\ 
 \ *Product Consumption Limit for the Department*\ 
\ **Help**\ 
 \ *Product Consumption Limit for the Department*\ 

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

Payroll Department
------------------

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Expected Consumption
--------------------
\ **Description**\ 
 \ *Planned Quantity*\ 
\ **Help**\ 
 \ *Planned Quantity*\ 

Actual Consumption
------------------
\ **Description**\ 
 \ *The actual quantity*\ 
\ **Help**\ 
 \ *The Actual Quantity indicates the quantity as referenced on a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
