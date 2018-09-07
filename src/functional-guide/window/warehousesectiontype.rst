
.. _functional-guide/window/warehousesectiontype:

======================
Warehouse Section Type
======================

Maintain Warehouse Section Type

Help
====
The Warehouse Section type is required for picking and putaway the material, it can be defined according to:

*Heavy Parts
*Bulky Materials
*Slow or Fast moving products

Also, these types allow to determine the Operation Type e.g. either picking or putaway within the Warehouse

The Warehouse Section Type also define the Warehouse Section for Inbound or Outbound Operations

Also the Section Type allows to define the type Warehouse Management operation

Picking Section (Inbound)
Putaway Section (Outbound)

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Warehouse Section Type
----------------------
\ **Description**\ 
 \ *Warehouse Section Type*\ 
\ **Help**\ 
 \ *The Warehouse Section Type Tab defines different Warehouse Section used for different purpose in a Warehouse.*\ 

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

Inbound & Outbound Type
-----------------------
\ **Description**\ 
 \ *Inbound & Outbound Type*\ 
\ **Help**\ 
 \ *The Inbound & Outbound Type defines the type of In & Out Operation to be Putaway or Picking.*\ 
