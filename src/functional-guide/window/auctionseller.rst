
.. _functional-guide/window/auctionseller:

==============
Auction Seller
==============

Maintain Auction Seller Information

Help
====
A seller is a User in the system participating in Auctions

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Seller
------
\ **Description**\ 
 \ *Aution Seller Information*\ 
\ **Help**\ 
 \ *Information about a participant in an Auction as a Seller*\ 

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

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 

Internal
--------
\ **Description**\ 
 \ *Internal Organization*\ 

Funds
-----
\ **Description**\ 
 \ *Seller Funds from Offers on Topics*\ 
\ **Help**\ 
 \ *Available Funds (for Payments) and Committed or Uncommited funds from Offers*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Not Committed Aount
-------------------
\ **Description**\ 
 \ *Amount not committed yet*\ 

Payment
-------
\ **Description**\ 
 \ *Payment identifier*\ 
\ **Help**\ 
 \ *The Payment is a unique identifier of this payment.*\ 

Purchase Order
--------------
\ **Description**\ 
 \ *Purchase Order*\ 
\ **Help**\ 
 \ *The Purchase Order is a control document.  The Purchase Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Offer
-----
\ **Description**\ 
 \ *Offer for a Topic*\ 
\ **Help**\ 
 \ *You can create an offer for a topic.*\ 

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

Seller Funds
------------
\ **Description**\ 
 \ *Seller Funds from Offers on Topics*\ 
\ **Help**\ 
 \ *Available Funds (for Payments) and Committed or Uncommitted funds from Offers*\ 

Topic
-----
\ **Description**\ 
 \ *Auction Topic*\ 
\ **Help**\ 
 \ *Description of the item to sell or create.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Willing to commit
-----------------

Text Message
------------
\ **Description**\ 
 \ *Text Message*\ 

Private Note
------------
\ **Description**\ 
 \ *Private Note - not visible to the other parties*\ 
