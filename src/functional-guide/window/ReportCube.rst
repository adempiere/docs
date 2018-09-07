
.. _window-reportcube:

===========
Report Cube
===========

Define reporting cube for pre-calculation of summary accounting data.

Help
====
Summary data will be generated for each period of the selected calendar, grouped by the selected dimensions..

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Report Cube
-----------

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

Calendar
--------
\ **Description**\ 
 \ *Accounting Calendar Name*\ 
\ **Help**\ 
 \ *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Product Dimension
-----------------
\ **Description**\ 
 \ *Include Product as a cube dimension*\ 

Business Partner Dimension
--------------------------
\ **Description**\ 
 \ *Include Business Partner as a cube dimension*\ 

Sales Region Dimension
----------------------
\ **Description**\ 
 \ *Include Sales Region as a cube dimension*\ 

OrgTrx Dimension
----------------
\ **Description**\ 
 \ *Include OrgTrx as a cube dimension*\ 

Activity Dimension
------------------
\ **Description**\ 
 \ *Include Activity as a cube dimension*\ 

Campaign Dimension
------------------
\ **Description**\ 
 \ *Include Campaign as a cube dimension*\ 

Project Dimension
-----------------
\ **Description**\ 
 \ *Include Project as a cube dimension*\ 

Project Phase  Dimension
------------------------
\ **Description**\ 
 \ *Include Project Phase as a cube dimension*\ 

Project Task  Dimension
-----------------------
\ **Description**\ 
 \ *Include Project Task as a cube dimension*\ 

GL Budget Dimension
-------------------
\ **Description**\ 
 \ *Include GL Budget as a cube dimension*\ 

Location From Dimension
-----------------------
\ **Description**\ 
 \ *Include Location From as a cube dimension*\ 

Location To  Dimension
----------------------
\ **Description**\ 
 \ *Include Location To as a cube dimension*\ 

Sub Acct Dimension
------------------
\ **Description**\ 
 \ *Include Sub Acct as a cube dimension*\ 

User 1 Dimension
----------------
\ **Description**\ 
 \ *Include User 1 as a cube dimension*\ 

User 2 Dimension
----------------
\ **Description**\ 
 \ *Include User 2 as a cube dimension*\ 

User 3 Dimension
----------------
\ **Description**\ 
 \ *Include User 3 as a cube dimension*\ 

User 4 Dimension
----------------
\ **Description**\ 
 \ *Include User 4 as a cube dimension*\ 

User Element 1 Dimension
------------------------
\ **Description**\ 
 \ *Include User Element 1 as a cube dimension*\ 

User Element 2 Dimension
------------------------
\ **Description**\ 
 \ *Include User Element 2 as a cube dimension*\ 

Last Recalculated
-----------------
\ **Description**\ 
 \ *The time last recalculated.*\ 
