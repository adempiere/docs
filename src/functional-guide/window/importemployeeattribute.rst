
.. _functional-guide/window/importemployeeattribute:

=========================
Import Employee Attribute
=========================

Import Employee Attribute

Help
====
The Import Payroll Attribute is an interim table which is used when importing Employee Attributes into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Payroll Attribute
------------------------

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

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Payroll Employee Attribute
--------------------------
\ **Description**\ 
 \ *Employee Attribute allows to add any metadata of type (text, date , quantity and amount ) of an Employee.*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

Import Employee Attribute
-------------------------
\ **Description**\ 
 \ *Import Employee Attribute*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Concept Value
-------------
\ **Description**\ 
 \ *Value of the Concept*\ 

Global Payroll Concept
----------------------
\ **Description**\ 
 \ *The Payroll Concept allows to define all the perception and deductions elements needed to define a payroll.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

Rule
----

Amount
------
\ **Description**\ 
 \ *Amount in a defined currency*\ 
\ **Help**\ 
 \ *The Amount indicates the amount for this document line.*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Service date
------------
\ **Description**\ 
 \ *Date service was provided*\ 
\ **Help**\ 
 \ *The Service Date indicates the date that the service was provided.*\ 

Text Message
------------
\ **Description**\ 
 \ *Text Message*\ 

Min Value
---------

Max Value
---------

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Payroll Contract Value
----------------------
\ **Description**\ 
 \ *Payroll Contract Value*\ 

Payroll Contract
----------------

Payroll Value
-------------
\ **Description**\ 
 \ *Define the a Search key of a payroll*\ 

Payroll
-------

Department Value
----------------
\ **Description**\ 
 \ *Department Value*\ 

Payroll Department
------------------

Job Value
---------
\ **Description**\ 
 \ *Job Value*\ 

Payroll Job
-----------

Job Type Value
--------------
\ **Description**\ 
 \ *The Job Type Value for a Job Openings*\ 
\ **Help**\ 
 \ *Job Type Value for Recruitment Management*\ 

Job Type
--------
\ **Description**\ 
 \ *The Job Type for a Job Openings*\ 
\ **Help**\ 
 \ *Job Type for Recruitment Management*\ 

Employee Type Value
-------------------
\ **Description**\ 
 \ *Employee Type Value*\ 

Employee Type
-------------
\ **Description**\ 
 \ *Employee Type*\ 

Employee Status
---------------

Job Education Value
-------------------
\ **Description**\ 
 \ *Job Education Value of an Employee*\ 
\ **Help**\ 
 \ *The Job Education Value of an Employee*\ 

Job Education
-------------
\ **Description**\ 
 \ *The Job Education for this position*\ 
\ **Help**\ 
 \ *Job Education required for this position*\ 

Career Level Value
------------------
\ **Description**\ 
 \ *The Career Level Value for this position*\ 
\ **Help**\ 
 \ *Career level value required for this position*\ 

Career Level
------------
\ **Description**\ 
 \ *The Career Level for this position*\ 
\ **Help**\ 
 \ *Career level required for this position*\ 

Race Value
----------
\ **Description**\ 
 \ *Race Value*\ 

Race
----
\ **Description**\ 
 \ *Race*\ 
\ **Help**\ 
 \ *Race*\ 

Degree Value
------------
\ **Description**\ 
 \ *Degree Value for an Employee Import*\ 
\ **Help**\ 
 \ *The Degree for an Employee*\ 

Degree
------
\ **Description**\ 
 \ *Degree for an Employee*\ 
\ **Help**\ 
 \ *The Degree for an Employee*\ 

Grade Value
-----------
\ **Description**\ 
 \ *Grade Value for Impor Employee*\ 
\ **Help**\ 
 \ *Grade Value for Employee*\ 

Grade
-----
\ **Description**\ 
 \ *Grade*\ 
\ **Help**\ 
 \ *Grade*\ 

Skill Type Value
----------------
\ **Description**\ 
 \ *Skill Type Value*\ 

Skill Type
----------
\ **Description**\ 
 \ *Skill Type for an Employee*\ 
\ **Help**\ 
 \ *The Skill Type for an Employee*\ 

Designation Value
-----------------
\ **Description**\ 
 \ *Designation Value is a nationally recognized level*\ 
\ **Help**\ 
 \ *Designation Value is a nationally recognized level of achievement within the field of human resources.*\ 

Designation
-----------
\ **Description**\ 
 \ *Designation is a nationally recognized level*\ 
\ **Help**\ 
 \ *Designation is a nationally recognized level of achievement within the field of human resources.*\ 

Salary Structure Value
----------------------
\ **Description**\ 
 \ *Salary Structure Value of an Employee*\ 
\ **Help**\ 
 \ *The Salary Structure Value define*\ 

Salary Structure
----------------
\ **Description**\ 
 \ *Salary Structure of an Employee*\ 
\ **Help**\ 
 \ *The Salary Structure define*\ 

Salary Range Value
------------------
\ **Description**\ 
 \ *The Salary Rage Value is use in Job Openings*\ 
\ **Help**\ 
 \ *Salary range value for Job Opening*\ 

Salary Range
------------
\ **Description**\ 
 \ *The Salary Rage is use in Job Openings*\ 
\ **Help**\ 
 \ *Salary range for Job Opening*\ 

Work Group Value
----------------
\ **Description**\ 
 \ *Work Group Value used for import*\ 
\ **Help**\ 
 \ *The Work Group provides a way to grouping of Work*\ 

Work Group
----------
\ **Description**\ 
 \ *Work Group*\ 
\ **Help**\ 
 \ *The Work Group provides a way to grouping of Work*\ 

Shift Group Value
-----------------
\ **Description**\ 
 \ *Shift Group Value*\ 
\ **Help**\ 
 \ *The Shift Group provides a way to grouping of Shifts*\ 

Shift Group
-----------
\ **Description**\ 
 \ *Shift Group*\ 
\ **Help**\ 
 \ *The Shift Group provides a way to grouping of Shifts*\ 

Trx Org Key
-----------
\ **Description**\ 
 \ *Key of the Transaction Organization*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Activity Value
--------------

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Project Key
-----------
\ **Description**\ 
 \ *Key of the Project*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Campaign Value
--------------

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 
