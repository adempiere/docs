
.. _functional-guide/window/textindex:

==========
Text Index
==========

Maintain Text Search Index

Help
====
Text search index keyword and excerpt across documents

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Index
-----
\ **Description**\ 
 \ *Text Search Index*\ 
\ **Help**\ 
 \ *Text search index keyword and excerpt across documents*\ 

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

Keyword
-------
\ **Description**\ 
 \ *Case insensitive keyword*\ 
\ **Help**\ 
 \ *Case insensitive keyword for matching. The individual keywords can be separated by space, comma, semicolon, tab or new line. Do not use filler words like "a", "the". At this point, there are NO text search operators like "or" and "and".*\ 

Excerpt
-------
\ **Description**\ 
 \ *Surrounding text of the keyword*\ 
\ **Help**\ 
 \ *A passage or segment taken from a document,*\ 

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

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 

Source Updated
--------------
\ **Description**\ 
 \ *Date the source document was updated*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

Web Project
-----------
\ **Description**\ 
 \ *A web project is the main data container for Containers, URLs, Ads, Media etc.*\ 
\ **Help**\ 
 \ *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*\ 
