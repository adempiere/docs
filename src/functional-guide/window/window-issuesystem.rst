
.. _functional-guide/window/window-issuesystem:

============
Issue System
============

Maintain Systems

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Issue System
------------
\ **Description**\ 
 \ *Maintain Issue Systems*\ 

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

DB Address
----------
\ **Description**\ 
 \ *JDBC URL of the database server*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

System Status
-------------
\ **Description**\ 
 \ *Status of the system - Support priority depends on system status*\ 
\ **Help**\ 
 \ *System status helps to prioritize support resources*\ 

Statistics
----------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics as well as general anonymous statistics*\ 

Profile
-------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics*\ 
