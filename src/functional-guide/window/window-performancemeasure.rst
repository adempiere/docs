
.. _functional-guide/window/window-performancemeasure:

===================
Performance Measure
===================

Define your Performance Measures

Help
====
The Performance Measure Window allows you to define the rules and restrictions for performance measurement.  You can, for example, restrict performance measurement to sales for a certain product category for a defined time frame.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Measure
-------
\ **Description**\ 
 \ *Performance Measure*\ 
\ **Help**\ 
 \ *The Performance Measure Tab defines the date range and method to be used for measuring performance.*\ 

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

Measure Data Type
-----------------
\ **Description**\ 
 \ *Type of data - Status or in Time*\ 
\ **Help**\ 
 \ *Status represents values valid at a certain time (e.g. Open Invoices) - No history is maintained.
Time represents a values at a given time (e.g. Invoice Amount on 1/1) - History is maintained*\ 

Measure Type
------------
\ **Description**\ 
 \ *Determines how the actual performance is derived*\ 
\ **Help**\ 
 \ *The Measure Type indicates how the actual measure is determined.  For example, one measure may be manual while another is calculated.*\ 

Manual Actual
-------------
\ **Description**\ 
 \ *Manually entered actual value*\ 
\ **Help**\ 
 \ *The Manual Active identifies a manually entered actual measurement value.*\ 

Note
----
\ **Description**\ 
 \ *Note for manual entry*\ 
\ **Help**\ 
 \ *The Note allows for entry for additional information regarding a manual entry.*\ 

Measure Calculation
-------------------
\ **Description**\ 
 \ *Calculation method for measuring performance*\ 
\ **Help**\ 
 \ *The Measure Calculation indicates the method of measuring performance.*\ 

Calculation Class
-----------------
\ **Description**\ 
 \ *Java Class for calculation, implementing Interface Measure*\ 
\ **Help**\ 
 \ *The Calculation Class indicates the Java Class used for calculating measures.*\ 

Ratio
-----
\ **Description**\ 
 \ *Performance Ratio*\ 
\ **Help**\ 
 \ *Calculation instruction set  for a performance ratio*\ 

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

Project Type
------------
\ **Description**\ 
 \ *Type of the project*\ 
\ **Help**\ 
 \ *Type of the project with optional phases of the project with standard performance information*\ 

Benchmark
---------
\ **Description**\ 
 \ *Performance Benchmark*\ 
\ **Help**\ 
 \ *Data Series to compare internal performance with (e.g. stock price, ...)*\ 

Reporting Hierarchy
-------------------
\ **Description**\ 
 \ *Optional Reporting Hierarchy - If not selected the default hierarchy trees are used.*\ 
\ **Help**\ 
 \ *Reporting Hierarchy allows you to select different Hierarchies/Trees for the report.
Accounting Segments like Organization, Account, Product may have several hierarchies to accomodate different views on the business.*\ 

Achievement
-----------
\ **Description**\ 
 \ *Performance Achievement*\ 
\ **Help**\ 
 \ *The Performance Achievement Tab defines the Tasks to be achieved.  The performance is measured by the percentage of reached achievements.*\ 

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

Measure
-------
\ **Description**\ 
 \ *Concrete Performance Measurement*\ 
\ **Help**\ 
 \ *The Measure identifies a concrete, measurable indicator of performance.  For example, sales dollars, prospects contacted.*\ 

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Document Date
-------------
\ **Description**\ 
 \ *Date of the Document*\ 
\ **Help**\ 
 \ *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Achieved
--------
\ **Description**\ 
 \ *The goal is achieved*\ 
\ **Help**\ 
 \ *The Achieved checkbox indicates if this goal has been achieved.*\ 

Manual Actual
-------------
\ **Description**\ 
 \ *Manually entered actual value*\ 
\ **Help**\ 
 \ *The Manual Active identifies a manually entered actual measurement value.*\ 
