
.. _functional-guide/window/performancecolorschema:

========================
Performance Color Schema
========================

Maintain Performance Color Schema

Help
====
Visual representation of performance by color.  The Schema has often three levels (e.g. red-yellow-green).  Adempiere support two levels (e.g. red-green) or four levels (e.g. gray-bronce-silver-gold).  Note that Measures without a goal are represented white.  The percentages could be beween 0 and unlimited (i.e. above 100%).

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Color Schema
------------
\ **Description**\ 
 \ *Performance Color Schema*\ 
\ **Help**\ 
 \ *Visual representation of performance by color.  The Schema has often three levels (e.g. red-yellow-green).  Adempiere support two levels (e.g. red-green) or four levels (e.g. gray-bronce-silver-gold).  Note that Measures without a goal are represented white.  The percentages could be beween 0 and unlimited (i.e. above 100%).*\ 

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

Mark 1 Percent
--------------
\ **Description**\ 
 \ *Percentage up to this color is used*\ 
\ **Help**\ 
 \ *Example 50 - i.e. below 50% this color is used*\ 

Color 1
-------
\ **Description**\ 
 \ *First color used*\ 

Mark 2 Percent
--------------
\ **Description**\ 
 \ *Percentage up to this color is used*\ 
\ **Help**\ 
 \ *Example 80 - e.g., if Mark 1 is 50 - this color is used between 50% and 80%*\ 

Color 2
-------
\ **Description**\ 
 \ *Second color used*\ 

Mark 3 Percent
--------------
\ **Description**\ 
 \ *Percentage up to this color is used*\ 
\ **Help**\ 
 \ *Example 100 - e.g., if Mark 2 is 80 - this color is used between 80% and 100%*\ 

Color 3
-------
\ **Description**\ 
 \ *Third color used*\ 

Mark 4 Percent
--------------
\ **Description**\ 
 \ *Percentage up to this color is used*\ 
\ **Help**\ 
 \ *Example 9999 - e.g., if Mark 3 is 100 - this color is used above 100%*\ 

Color 4
-------
\ **Description**\ 
 \ *Forth color used*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 
