
.. _functional-guide/window/window-inboundoutbounddefinition:

===========================
Inbound/Outbound Definition
===========================

Maintain Inbound/Outbound Definition

Help
====
Inbound/Outbound Definition window allows defining a set of conditions in order to implement an Inbound(Putaway) and Outbound(Picking) Strategy using different criteria such as:

Product
Product category
Product Group 1
Product Group 2 
Product Classification
Business Partner
Business Partner Group
Warehouse Area Type
Warehouse Section Type
Warehouse Location.
Priority.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Inbound & Outboud Definition
----------------------------
\ **Description**\ 
 \ *Define the Inbound(Putaway) and Outbound(Picking) Strategy*\ 
\ **Help**\ 
 \ *The Inbound(Putaway) and Outbound(Picking) definition tab allow defining a set of conditions in order to select the Inbound(Putaway) and Outbound(Picking) Strategy from a given sequence ordered by priority.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Priority
--------
\ **Description**\ 
 \ *Priority of a document*\ 
\ **Help**\ 
 \ *The Priority indicates the importance (high, medium, low) of this document*\ 

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

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

Warehouse Managamet Strategy
----------------------------

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Group1
------

Group2
------

Classification
--------------
\ **Description**\ 
 \ *Classification for grouping*\ 
\ **Help**\ 
 \ *The Classification can be used to optionally group products.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Warehouse Area Type
-------------------
\ **Description**\ 
 \ *Warehouse Area Type allow grouping the Warehouse Area for Type*\ 

Warehouse Section Type
----------------------

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Sort of the combinations
------------------------
\ **Description**\ 
 \ *The sequence tab allows to set the order of priority for the Inbound (Putaway) and Outbound(Picking) Strategy*\ 

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
