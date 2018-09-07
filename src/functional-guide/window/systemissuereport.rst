
.. _functional-guide/window/systemissuereport:

===================
System Issue Report
===================

Automatically created or manually entered System Issue Reports

Help
====
System Issues are created to speed up the resolution of any system related issues (potential bugs).  If enabled, they are automatically reported to Adempiere.  No data or confidential information is transferred.

Window Type
-----------
\ **Transaction**\ 


Tabs
====

System Issue
------------
\ **Description**\ 
 \ *Automatically created or manually entered System Issue Reporting*\ 
\ **Help**\ 
 \ *System Issues are created to speed up the resolution of any system related issues (potential bugs).  If enabled, they are automatically reported to Adempiere.  No data or confidential information is transferred.*\ 

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

Created
-------
\ **Description**\ 
 \ *Date this record was created*\ 
\ **Help**\ 
 \ *The Created field indicates the date that this record was created.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Release No
----------
\ **Description**\ 
 \ *Internal Release Number*\ 

Version
-------
\ **Description**\ 
 \ *Version of the table definition*\ 
\ **Help**\ 
 \ *The Version indicates the version of this table definition.*\ 

Vanilla System
--------------
\ **Description**\ 
 \ *The system was NOT compiled from Source - i.e. standard distribution*\ 
\ **Help**\ 
 \ *You may have customizations, like additional columns, tables, etc - but no code modifications which require compiling from source.*\ 

Release Tag
-----------
\ **Description**\ 
 \ *Release Tag*\ 

Source
------
\ **Description**\ 
 \ *Issue Source*\ 
\ **Help**\ 
 \ *Source of the Issue*\ 

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Special Form
------------
\ **Description**\ 
 \ *Special Form*\ 
\ **Help**\ 
 \ *The Special Form field identifies a unique Special Form in the system.*\ 

Issue Summary
-------------
\ **Description**\ 
 \ *Issue Summary*\ 

Reproducible
------------
\ **Description**\ 
 \ *Problem can re reproduced in Gardenworld*\ 
\ **Help**\ 
 \ *The problem occurs also in the standard distribution in the demo client Gardenworld.*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Logger
------
\ **Description**\ 
 \ *Logger Name*\ 

Source Method
-------------
\ **Description**\ 
 \ *Source Method Name*\ 

Source Class
------------
\ **Description**\ 
 \ *Source Class Name*\ 

Line
----
\ **Description**\ 
 \ *Line No*\ 

Stack Trace
-----------
\ **Description**\ 
 \ *System Log Trace*\ 

Error Trace
-----------
\ **Description**\ 
 \ *System Error Trace*\ 
\ **Help**\ 
 \ *Java Trace Info*\ 

Response Text
-------------
\ **Description**\ 
 \ *Request Response Text*\ 
\ **Help**\ 
 \ *Text block to be copied into request response text*\ 

System Status
-------------
\ **Description**\ 
 \ *Status of the system - Support priority depends on system status*\ 
\ **Help**\ 
 \ *System status helps to prioritize support resources*\ 

Known Issue
-----------
\ **Description**\ 
 \ *Known Issue*\ 

Request Document No
-------------------
\ **Description**\ 
 \ *Adempiere Request Document No*\ 

Request
-------
\ **Description**\ 
 \ *Request from a Business Partner or Prospect*\ 
\ **Help**\ 
 \ *The Request identifies a unique request from a Business Partner or Prospect.*\ 

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Issue Project
-------------
\ **Description**\ 
 \ *Implementation Projects*\ 

Support EMail
-------------
\ **Description**\ 
 \ *EMail address to send support information and updates to*\ 
\ **Help**\ 
 \ *If not entered the registered email is used.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Registered EMail
----------------
\ **Description**\ 
 \ *Email of the responsible for the System*\ 
\ **Help**\ 
 \ *Email of the responsible person for the system (registered in WebStore)*\ 

Issue System
------------
\ **Description**\ 
 \ *System creating the issue*\ 

IssueUser
---------
\ **Description**\ 
 \ *User who reported issues*\ 

DB Address
----------
\ **Description**\ 
 \ *JDBC URL of the database server*\ 

Local Host
----------
\ **Description**\ 
 \ *Local Host Info*\ 

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

Remote Host
-----------
\ **Description**\ 
 \ *Remote host Info*\ 

Remote Addr
-----------
\ **Description**\ 
 \ *Remote Address*\ 
\ **Help**\ 
 \ *The Remote Address indicates an alternative or external address.*\ 

Operating System
----------------
\ **Description**\ 
 \ *Operating System Info*\ 

Java Info
---------
\ **Description**\ 
 \ *Java Version Info*\ 

Database
--------
\ **Description**\ 
 \ *Database Information*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Report or Update Issue
----------------------
\ **Description**\ 
 \ *Report Issue to Adempiere*\ 

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 
