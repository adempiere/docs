
.. _window-requesttype:

============
Request Type
============

Maintain Request Types

Help
====
Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

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

Status Category
---------------
\ **Description**\ 
 \ *Request Status Category*\ 
\ **Help**\ 
 \ *Category of Request Status enables to maintain different set of Status for different Request Categories*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

EMail when Due
--------------
\ **Description**\ 
 \ *Send EMail when Request becomes due*\ 
\ **Help**\ 
 \ *Send EMail when Request becomes due*\ 

Due Date Tolerance
------------------
\ **Description**\ 
 \ *Tolerance in days between the Date Next Action and the date the request is regarded as overdue*\ 
\ **Help**\ 
 \ *When the Date Next Action is passed, the Request becomes Due. After the Due Date Tolerance, the Request becomes Overdue.*\ 

EMail when Overdue
------------------
\ **Description**\ 
 \ *Send EMail when Request becomes overdue*\ 
\ **Help**\ 
 \ *Send EMail when Request becomes overdue*\ 

Auto Due Date Days
------------------
\ **Description**\ 
 \ *Automatic Due Date Days*\ 
\ **Help**\ 
 \ *If a due date is not defined and the Auto Due Days ins greater then zero, a due date in the number of days is automatically created.*\ 

Invoiced
--------
\ **Description**\ 
 \ *Is this invoiced?*\ 
\ **Help**\ 
 \ *If selected, invoices are created*\ 

Confidentiality
---------------
\ **Description**\ 
 \ *Type of Confidentiality*\ 

Confidential Info
-----------------
\ **Description**\ 
 \ *Can enter confidential information*\ 
\ **Help**\ 
 \ *When entering/updating Requests over the web, the user can mark his info as confidential*\ 

Create Change Request
---------------------
\ **Description**\ 
 \ *Automatically create BOM (Engineering) Change Request*\ 
\ **Help**\ 
 \ *Create automatically a Product Bill of Material  (Engineering) Change Request when the Request Group references a Product BOM*\ 

Update Notification
-------------------
\ **Description**\ 
 \ *List Recipients for to receive Request Updates*\ 

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

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

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

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 
