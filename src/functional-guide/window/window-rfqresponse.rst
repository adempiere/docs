
.. _functional-guide/window/window-rfqresponse:

============
RfQ Response
============

Manage RfQ Responses

Window Type
-----------
\ **Transaction**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Response
--------
\ **Description**\ 
 \ *RfQ Response*\ 
\ **Help**\ 
 \ *Request for Quotation Response from a potential Vendor*\ 

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

RfQ
---
\ **Description**\ 
 \ *Request for Quotation*\ 
\ **Help**\ 
 \ *Request for Quotation to be sent out to vendors of a RfQ Topic. After Vendor selection, optionally create Sales Order or Quote for Customer as well as Purchase Order  for Vendor(s)*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

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

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Invited
-------
\ **Description**\ 
 \ *Date when (last) invitation was sent*\ 

Response Date
-------------
\ **Description**\ 
 \ *Date of the Response*\ 
\ **Help**\ 
 \ *Date of the Response*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Price
-----
\ **Description**\ 
 \ *Price*\ 
\ **Help**\ 
 \ *The Price indicates the Price for a product or service.*\ 

Work Start
----------
\ **Description**\ 
 \ *Date when work is (planned to be) started*\ 

Delivery Days
-------------
\ **Description**\ 
 \ *Number of Days (planned) until Delivery*\ 

Work Complete
-------------
\ **Description**\ 
 \ *Date when work is (planned to be) complete*\ 

Invite & Remind
---------------
\ **Description**\ 
 \ *EMail Invite or Remind Vendor to answer RfQ*\ 
\ **Help**\ 
 \ *Send Invitation/Reminder to Vendors to respond to RfQ per email*\ 

Ranking
-------
\ **Description**\ 
 \ *Relative Rank Number*\ 
\ **Help**\ 
 \ *One is the highest Rank*\ 

Selected Winner
---------------
\ **Description**\ 
 \ *The response is the selected winner*\ 
\ **Help**\ 
 \ *The response is the selected winner. If selected on Response level, the line selections are ignored.*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Check Complete
--------------
\ **Description**\ 
 \ *Check if Response is Complete based on RfQ settings*\ 

Complete
--------
\ **Description**\ 
 \ *It is complete*\ 
\ **Help**\ 
 \ *Indication that this is complete*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Response Line
-------------
\ **Description**\ 
 \ *RfQ Response Line*\ 
\ **Help**\ 
 \ *Request for Quotation Response Line from a potential Vendor*\ 

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

RfQ Line
--------
\ **Description**\ 
 \ *Request for Quotation Line*\ 
\ **Help**\ 
 \ *Request for Quotation Line*\ 

RfQ Response
------------
\ **Description**\ 
 \ *Request for Quotation Response from a potential Vendor*\ 
\ **Help**\ 
 \ *Request for Quotation Response from a potential Vendor*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Work Start
----------
\ **Description**\ 
 \ *Date when work is (planned to be) started*\ 

Delivery Days
-------------
\ **Description**\ 
 \ *Number of Days (planned) until Delivery*\ 

Work Complete
-------------
\ **Description**\ 
 \ *Date when work is (planned to be) complete*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Selected Winner
---------------
\ **Description**\ 
 \ *The response is the selected winner*\ 
\ **Help**\ 
 \ *The response is the selected winner. If selected on Response level, the line selections are ignored.*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Response Quantity
-----------------
\ **Description**\ 
 \ *RfQ Line Quantity Response*\ 
\ **Help**\ 
 \ *Request for Quotation Response Line Quantity from a potential Vendor*\ 

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

RfQ Response Line
-----------------
\ **Description**\ 
 \ *Request for Quotation Response Line*\ 
\ **Help**\ 
 \ *Request for Quotation Response Line from a potential Vendor*\ 

RfQ Line Quantity
-----------------
\ **Description**\ 
 \ *Request for Quotation Line Quantity*\ 
\ **Help**\ 
 \ *You may request a quotation for different quantities*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Price
-----
\ **Description**\ 
 \ *Price*\ 
\ **Help**\ 
 \ *The Price indicates the Price for a product or service.*\ 

Discount %
----------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 

Ranking
-------
\ **Description**\ 
 \ *Relative Rank Number*\ 
\ **Help**\ 
 \ *One is the highest Rank*\ 
