
.. _window-resourcetype:

=============
Resource Type
=============

Maintain Resource Types

Help
====
Maintain Resource types and their principal availability. it is used to calculate the available time in a resource. It allows input of starting time and end time for the slot according to the working days.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Resource Type
-------------
\ **Description**\ 
 \ *Maintain Resource Types*\ 
\ **Help**\ 
 \ *Maintain Resource types and their principal availability.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Allow UoM Fractions
-------------------
\ **Description**\ 
 \ *Allow Unit of Measure Fractions*\ 
\ **Help**\ 
 \ *If allowed, you can enter UoM Fractions*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Tax Category
------------
\ **Description**\ 
 \ *Tax Category*\ 
\ **Help**\ 
 \ *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*\ 

Tax Type
--------
\ **Description**\ 
 \ *Tax Type*\ 

Single Assignment only
----------------------
\ **Description**\ 
 \ *Only one assignment at a time (no double-booking or overlapping)*\ 
\ **Help**\ 
 \ *If selected, you can only have one assignment for the resource at a single point in time.   It is also  not possible to have overlapping assignments.*\ 

Time Slot
---------
\ **Description**\ 
 \ *Resource has time slot availability*\ 
\ **Help**\ 
 \ *Resource is only available at certain times*\ 

Slot Start
----------
\ **Description**\ 
 \ *Time when timeslot starts*\ 
\ **Help**\ 
 \ *Starting time for time slots*\ 

Slot End
--------
\ **Description**\ 
 \ *Time when timeslot ends*\ 
\ **Help**\ 
 \ *Ending time for time slots*\ 

Day Slot
--------
\ **Description**\ 
 \ *Resource has day slot availability*\ 
\ **Help**\ 
 \ *Resource is only available on certain days*\ 

Sunday
------
\ **Description**\ 
 \ *Available on Sundays*\ 

Monday
------
\ **Description**\ 
 \ *Available on Mondays*\ 

Tuesday
-------
\ **Description**\ 
 \ *Available on Tuesdays*\ 

Wednesday
---------
\ **Description**\ 
 \ *Available on Wednesdays*\ 

Thursday
--------
\ **Description**\ 
 \ *Available on Thursdays*\ 

Friday
------
\ **Description**\ 
 \ *Available on Fridays*\ 

Saturday
--------
\ **Description**\ 
 \ *Available on Saturday*\ 
