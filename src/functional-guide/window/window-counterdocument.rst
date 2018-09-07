
.. _functional-guide/window/window-counterdocument:

================
Counter Document
================

Maintain Counter Document Types

Help
====
When using explicit documents for inter-org transaction (after linking a Business Partner to an Organization), you can determine what document type the counter document is based on the document type of the original transaction.  Example: a "Standard Order" creates a "Standard PO". 
If you define a relationship here, you overwrite the default counter document type in the Document Type definition. This allows you to define a specific mapping.
If not defined, the first matching document type is used (e.g. AR Invoice - first AP Invoice document type)

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Counter Document
----------------
\ **Description**\ 
 \ *Maintain Counter Document Types*\ 
\ **Help**\ 
 \ *When using explicit documents for inter-org transaction (after linking a Business Partner to an Organization), you can determine what document type the counter document is based on the document type of the original transaction.  Example: a "Standard Order" creates a "Standard PO". 
If you define a relationship here, you overwrite the default counter document type in the Document Type definition. This allows you to define a specific mapping.
You can define conter documents for all organizations (of the original transaction) or for a specific organization.*\ 

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

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Create Counter Document
-----------------------
\ **Description**\ 
 \ *Create Counter Document*\ 
\ **Help**\ 
 \ *If selected, create specified counter document.  If not selected, no counter document is created for the document type.*\ 

Counter Document Type
---------------------
\ **Description**\ 
 \ *Generated Counter Document Type (To)*\ 
\ **Help**\ 
 \ *The Document Type of the generated counter document*\ 

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

Validate Document Type
----------------------
