
.. _functional-guide/window/partnerrelation:

================
Partner Relation
================

Maintain Business Partner Relations

Help
====
Business Partner Relation allow to maintain Third Party Relationship rules: who receives invoices for shipments or pays for invoices.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Relation
--------
\ **Description**\ 
 \ *Business Partner Relation*\ 
\ **Help**\ 
 \ *Business Partner Relation allow to maintain Third Party Relationship rules: who receives invoices for shipments or pays for invoices.  If the Location of the Business partner is not defined, the rule applies to all location of that Business Partner*\ 

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

Related Partner
---------------
\ **Description**\ 
 \ *Related Business Partner*\ 
\ **Help**\ 
 \ *The related Business Partner Acts on behalf of the Business Partner - example the Related Partner pays invoices of the Business Partner - or we pay to the Related Partner for invoices received from the Business Partner*\ 

Related Partner Location
------------------------
\ **Description**\ 
 \ *Location of the related Business Partner*\ 

Ship Address
------------
\ **Description**\ 
 \ *Business Partner Shipment Address*\ 
\ **Help**\ 
 \ *If the Ship Address is selected, the location is used to ship goods to a customer or receive goods from a vendor.*\ 

Invoice Address
---------------
\ **Description**\ 
 \ *Business Partner Invoice/Bill Address*\ 
\ **Help**\ 
 \ *If the Invoice Address is selected, the location is used to send invoices to a customer or receive invoices from a vendor.*\ 

Pay-From Address
----------------
\ **Description**\ 
 \ *Business Partner pays from that address and we'll send dunning letters there*\ 
\ **Help**\ 
 \ *If the Pay-From Address is selected, this location is the address the Business Partner pays from and where dunning letters will be sent to.*\ 

Remit-To Address
----------------
\ **Description**\ 
 \ *Business Partner payment address*\ 
\ **Help**\ 
 \ *If the Remit-To Address is selected, the location is used to send payments to the vendor.*\ 
