
.. _functional-guide/window/location:

========
Location
========

Maintain Location Address

Help
====
The Location Window defines the address data within the system.  This window is for System Admin only.  Users would access location entries using the location button or tab on the appropriate window (i.e Order Entry or Business Partner)

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Location
--------
\ **Description**\ 
 \ *Define Location*\ 
\ **Help**\ 
 \ *The Location Tab defines the location of an Organization.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Address 1
---------
\ **Description**\ 
 \ *Address line 1 for this location*\ 
\ **Help**\ 
 \ *The Address 1 identifies the address for an entity's location*\ 

Address 2
---------
\ **Description**\ 
 \ *Address line 2 for this location*\ 
\ **Help**\ 
 \ *The Address 2 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

Address 3
---------
\ **Description**\ 
 \ *Address Line 3 for the location*\ 
\ **Help**\ 
 \ *The Address 2 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

Address 4
---------
\ **Description**\ 
 \ *Address Line 4 for the location*\ 
\ **Help**\ 
 \ *The Address 4 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

City
----
\ **Description**\ 
 \ *Identifies a City*\ 
\ **Help**\ 
 \ *The City identifies a unique City for this Country or Region.*\ 

City
----
\ **Description**\ 
 \ *City*\ 
\ **Help**\ 
 \ *City in a country*\ 

ZIP
---
\ **Description**\ 
 \ *Postal code*\ 
\ **Help**\ 
 \ *The Postal Code or ZIP identifies the postal code for this entity's address.*\ 

Additional Zip
--------------
\ **Description**\ 
 \ *Additional ZIP or Postal code*\ 
\ **Help**\ 
 \ *The Additional ZIP or Postal Code identifies, if appropriate, any additional Postal Code information.*\ 

Region
------
\ **Description**\ 
 \ *Identifies a geographical Region*\ 
\ **Help**\ 
 \ *The Region identifies a unique Region for this Country.*\ 

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 
