
.. _functional-guide/window/window-relationtype:

=============
Relation Type
=============


Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Relation Type
-------------

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Directed
--------
\ **Description**\ 
 \ *Tells whether one "sees" the other end of the relation from each end or just from the source*\ 

Type
----
\ **Description**\ 
 \ *Type of Validation (SQL, Java Script, Java Language)*\ 
\ **Help**\ 
 \ *The Type indicates the type of validation that will occur.  This can be SQL, Java Script or Java Language.*\ 

Source Reference
----------------

Source Role
-----------
\ **Description**\ 
 \ *If set, this role will be used as label for the zoom destination instead of the destinations's window name*\ 

Target Reference
----------------

Target Role
-----------
\ **Description**\ 
 \ *If set, this role will be used as label for the zoom destination instead of the destinations's window name*\ 
