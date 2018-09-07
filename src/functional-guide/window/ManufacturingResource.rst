
.. _window-manufacturingresource:

======================
Manufacturing Resource
======================

Manufacturing Resource

Help
====
A Manufacturing Resource is defined as anything required for production and its unavailability can affect the Production Plan. Manufacturing Resources can be: Plants, Production lines, Work Centers and Work Stations.

It mainly answers the question: Where is the product made?

A Specific production facility consisting of one or more people and/or machines which can be considered as one unit for purposes of capacity requiremets planning and detailed scheduling.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Manufacturing Resource
----------------------

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Resource Type
-------------

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Available
---------
\ **Description**\ 
 \ *Resource is available*\ 
\ **Help**\ 
 \ *Resource is available for assignments*\ 

Manufacturing Resource
----------------------

Manufacturing Resource Type
---------------------------

Planning Horizon
----------------
\ **Description**\ 
 \ *The planning horizon is the amount of time (Days) an organisation will look into the future when preparing a strategic plan.*\ 
\ **Help**\ 
 \ *The planning horizon is the amount of time (Days) an organisation will look into the future when preparing a strategic plan.*\ 

Queuing Time
------------
\ **Description**\ 
 \ *Queue time is the time a job waits at a work center before begin handled.*\ 
\ **Help**\ 
 \ *Queuing time has no implication on costs, but on Capacity Requirement Planning (CRP) to calculate the total time needed to manufacture a product.*\ 

Waiting Time
------------
\ **Description**\ 
 \ *Workflow Simulation Waiting time*\ 
\ **Help**\ 
 \ *Amount of time needed to prepare the performance of the task on Duration Units*\ 
