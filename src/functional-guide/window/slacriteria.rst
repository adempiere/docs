
.. _functional-guide/window/slacriteria:

============
SLA Criteria
============

Service Level Agreement Criteria

Help
====
Define a criteria to measure service level agreements (e.g. Quality, Delivery meets Promised date, ..)

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

SLA Criteria
------------
\ **Description**\ 
 \ *Service Level Agreement Criteria*\ 
\ **Help**\ 
 \ *Define a criteria to measure service level agreements (e.g. Quality, Delivery meets Promised date, ..). If you define a process class, it need to implement org.compiere.sla.SLACriteria (see example)*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Manual
------
\ **Description**\ 
 \ *This is a manual process*\ 
\ **Help**\ 
 \ *The Manual check box indicates if the process will done manually.*\ 

Classname
---------
\ **Description**\ 
 \ *Java Classname*\ 
\ **Help**\ 
 \ *The Classname identifies the Java classname used by this report or process.*\ 

SLA Goal
--------
\ **Description**\ 
 \ *Service Level Agreement Goal*\ 
\ **Help**\ 
 \ *Individual Goal for the SLA criteria for the Business Partner*\ 

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

SLA Criteria
------------
\ **Description**\ 
 \ *Service Level Agreement Criteria*\ 
\ **Help**\ 
 \ *Criteria to measure service level agreements (e.g. Quality, Delivery meets Promised date, ..)*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 

Measure Target
--------------
\ **Description**\ 
 \ *Target value for measure*\ 
\ **Help**\ 
 \ *The Measure Target indicates the target or goal for this measure.  It is used as in comparing against the actual measures*\ 

Measure Actual
--------------
\ **Description**\ 
 \ *Actual value that has been measured.*\ 
\ **Help**\ 
 \ *The Measure Actual indicates the actual measured value. The measured values are used in determining if a performance goal has been met*\ 

Capture + Calculate Measures
----------------------------
\ **Description**\ 
 \ *Capture and Calculate Measures*\ 
\ **Help**\ 
 \ *If automatic, capture measures - and calculate/update the actual measure.*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

SLA Measure
-----------
\ **Description**\ 
 \ *Service Level Agreement Measure*\ 
\ **Help**\ 
 \ *View/Maintain the individual actual value / measure for the business partner service level agreement goal*\ 

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

SLA Goal
--------
\ **Description**\ 
 \ *Service Level Agreement Goal*\ 
\ **Help**\ 
 \ *Goal for the SLA criteria for the Business Partner*\ 

Transaction Date
----------------
\ **Description**\ 
 \ *Transaction Date*\ 
\ **Help**\ 
 \ *The Transaction Date indicates the date of the transaction.*\ 

Measure Actual
--------------
\ **Description**\ 
 \ *Actual value that has been measured.*\ 
\ **Help**\ 
 \ *The Measure Actual indicates the actual measured value. The measured values are used in determining if a performance goal has been met*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 

Calculate Measures
------------------
\ **Description**\ 
 \ *Calculate the Measure*\ 
\ **Help**\ 
 \ *Calculate/update the actual measure.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
