
.. _functional-guide/window/window-inboundoutboundrule:

=====================
Inbound/Outbound Rule
=====================

Maintain Warehouse Inbound/Outbound Rule

Help
====
The Inbound(Putaway) and Outbound(Picking)  Rules define the business logic according to a previously implemented algorithm, these rules are used by the Inbound(Putaway) and Outbound(Picking)  Strategy to determine the business logic and the operation type within the warehouse.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Inbound/Outbound Rule
---------------------
\ **Description**\ 
 \ *Define Inbound/Outbound Rule*\ 
\ **Help**\ 
 \ *The Inbound(Putaway) and Outbound(Picking)  Rules define the business logic according to a previously implemented algorithm, these rules are used by the Inbound(Putaway) and Outbound(Picking)  Strategy to determine the business logic and the operation type within the warehouse.*\ 

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

Inbound & Outbound Rule
-----------------------
\ **Description**\ 
 \ *Inbound & Outbound Rule determinated the putaway or pick location for goods stocked in the warehouse*\ 
\ **Help**\ 
 \ *Inbound & Outbound Rule are used to define which locators should be considered for putaway or picking.*\ 

Inbound & Outbound Type
-----------------------
\ **Description**\ 
 \ *Inbound & Outbound Type*\ 
\ **Help**\ 
 \ *The Inbound & Outbound Type defines the type of In & Out Operation to be Putaway or Picking.*\ 

Inbound & Outbound Class
------------------------
\ **Description**\ 
 \ *Custom class to implemeted new Inbound & Outbound Rule logic*\ 
\ **Help**\ 
 \ *If you select a custom Inbound & Outbound type, you need to create a class implementing org.eevolution.util.IInOutboundRule and set that on Inbound & Outbound Rule.*\ 

Rule
----
