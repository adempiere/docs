
.. _functional-guide/window/window-workshift:

==========
Work Shift
==========

Maintain Work Shift

Help
====
The Work Shift Window is used to define and maintain the Work Shift.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Work Shift
----------
\ **Description**\ 
 \ *Work Shift definition*\ 
\ **Help**\ 
 \ *The Work Shift Tab defines the Name, Description for a Work Shift.*\ 

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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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

Shift Group
-----------
\ **Description**\ 
 \ *Shift Group*\ 
\ **Help**\ 
 \ *The Shift Group provides a way to grouping of Shifts*\ 

Shift From Time
---------------
\ **Description**\ 
 \ *Shift Starting Time*\ 

Shift To Time
-------------
\ **Description**\ 
 \ *Shift Ending At Time*\ 

Number of Hours
---------------
\ **Description**\ 
 \ *Number of Hours This Shift Contains*\ 

Over Time Applicable
--------------------
\ **Description**\ 
 \ *Is over time applicable to this Shift?*\ 

Over Time Amount
----------------
\ **Description**\ 
 \ *Is Over time Applicable  Then How Much Amount*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
