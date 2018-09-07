
.. _functional-guide/window/payrollconceptcatalog:

=======================
Payroll Concept Catalog
=======================

Maintain Payroll Concept Catalog

Help
====
The Payroll  Concept Catalog Window is used to define the concepts for a payroll ie ( salaries, wages, bonuses, and deductions.)

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Concept
-------
\ **Description**\ 
 \ *Maintain Payroll Concept*\ 

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

Tax exempt
----------
\ **Description**\ 
 \ *Business partner is exempt from tax on sales*\ 
\ **Help**\ 
 \ *If a Concept is exempt from tax*\ 

Global Payroll Concept Category
-------------------------------
\ **Description**\ 
 \ *Global Payroll Concept Category allows to grouping of Global Concept to reports and queries*\ 

Global Payroll Concept Type
---------------------------
\ **Description**\ 
 \ *Allows define types for concepts*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Type
----
\ **Description**\ 
 \ *Type of Validation (SQL, Java Script, Java Language)*\ 
\ **Help**\ 
 \ *The Type indicates the type of validation that will occur.  This can be SQL, Java Script or Java Language.*\ 

Account Sign
------------
\ **Description**\ 
 \ *Indicates the Natural Sign of the Account as a Debit or Credit*\ 
\ **Help**\ 
 \ *Indicates if the expected balance for this account should be a Debit or a Credit. If set to Natural, the account sign for an asset or expense account is Debit Sign (i.e. negative if a credit balance).*\ 

Column Type
-----------

Standard Precision
------------------
\ **Description**\ 
 \ *Rule for rounding  calculated amounts*\ 
\ **Help**\ 
 \ *The Standard Precision defines the number of decimal places that amounts will be rounded to for accounting transactions and documents.*\ 

Reference
---------
\ **Description**\ 
 \ *System Reference and Validation*\ 
\ **Help**\ 
 \ *The Reference could be a display type, list or table validation.*\ 

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

Manual
------
\ **Description**\ 
 \ *This is a manual process*\ 
\ **Help**\ 
 \ *The Manual check box indicates if the process will done manually.*\ 

Paid
----
\ **Description**\ 
 \ *The document is paid*\ 

Prepayment
----------
\ **Description**\ 
 \ *The Payment/Receipt is a Prepayment*\ 
\ **Help**\ 
 \ *Payments not allocated to an invoice with a charge are posted to Unallocated Payments. When setting this flag, the payment is posted to the Customer or Vendor Prepayment account.*\ 

Invoiced
--------
\ **Description**\ 
 \ *Is this invoiced?*\ 
\ **Help**\ 
 \ *If selected, invoices are created*\ 

Save In Historic
----------------

No Save In History If Is Null
-----------------------------

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Concept Attributes
------------------
\ **Description**\ 
 \ *Maintain Employee Attributes*\ 
\ **Help**\ 
 \ *The Employee Attributes are used to define aditional data for a employee*\ 

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

Global Payroll Concept
----------------------
\ **Description**\ 
 \ *The Payroll Concept allows to define all the perception and deductions elements needed to define a payroll.*\ 

Column Type
-----------

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

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Payroll Contract
----------------

Payroll
-------

Payroll Department
------------------

Payroll Job
-----------

Job Type
--------
\ **Description**\ 
 \ *The Job Type for a Job Openings*\ 
\ **Help**\ 
 \ *Job Type for Recruitment Management*\ 

Employee Type
-------------
\ **Description**\ 
 \ *Employee Type*\ 

Employee Status
---------------

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Relation
----------------
\ **Description**\ 
 \ *Business Partner Relation*\ 
\ **Help**\ 
 \ *Business Partner Relation allow to maintain Third Party Relationship rules: who receives invoices for shipments or pays for invoices.*\ 

Job Education
-------------
\ **Description**\ 
 \ *The Job Education for this position*\ 
\ **Help**\ 
 \ *Job Education required for this position*\ 

Career Level
------------
\ **Description**\ 
 \ *The Career Level for this position*\ 
\ **Help**\ 
 \ *Career level required for this position*\ 

Race
----
\ **Description**\ 
 \ *Race*\ 
\ **Help**\ 
 \ *Race*\ 

Degree
------
\ **Description**\ 
 \ *Degree for an Employee*\ 
\ **Help**\ 
 \ *The Degree for an Employee*\ 

Grade
-----
\ **Description**\ 
 \ *Grade*\ 
\ **Help**\ 
 \ *Grade*\ 

Skill Type
----------
\ **Description**\ 
 \ *Skill Type for an Employee*\ 
\ **Help**\ 
 \ *The Skill Type for an Employee*\ 

Designation
-----------
\ **Description**\ 
 \ *Designation is a nationally recognized level*\ 
\ **Help**\ 
 \ *Designation is a nationally recognized level of achievement within the field of human resources.*\ 

Salary Structure
----------------
\ **Description**\ 
 \ *Salary Structure of an Employee*\ 
\ **Help**\ 
 \ *The Salary Structure define*\ 

Salary Range
------------
\ **Description**\ 
 \ *The Salary Rage is use in Job Openings*\ 
\ **Help**\ 
 \ *Salary range for Job Opening*\ 

Work Group
----------
\ **Description**\ 
 \ *Work Group*\ 
\ **Help**\ 
 \ *The Work Group provides a way to grouping of Work*\ 

Shift Group
-----------
\ **Description**\ 
 \ *Shift Group*\ 
\ **Help**\ 
 \ *The Shift Group provides a way to grouping of Shifts*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Payroll Rule
------------
\ **Description**\ 
 \ *Payroll Rule*\ 
\ **Help**\ 
 \ *Payroll Rule defined for this atribbute*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Event Type
----------
\ **Description**\ 
 \ *Type of Event*\ 

Rule Type
---------

Script
------
\ **Description**\ 
 \ *Dynamic Java Language Script to calculate result*\ 
\ **Help**\ 
 \ *Use Java language constructs to define the result of the calculation*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Concept Accounting
------------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Global Payroll Concept
----------------------
\ **Description**\ 
 \ *The Payroll Concept allows to define all the perception and deductions elements needed to define a payroll.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Payroll Expense Account
-----------------------

Payroll Revenue Account
-----------------------

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Balancing
---------
\ **Description**\ 
 \ *All transactions within an element value must balance (e.g. cost centers)*\ 
\ **Help**\ 
 \ *The Balancing checkbox indicates the this element must balance in each journal transaction.  For example, if cost centers have been defined as an element which is balance then the debits and credits for each unique cost center must net to 0.00.  This is commonly used to define parts of an organization which report as their own entity.  Balancing is not an option for the Account element.*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Concept Ordering
----------------
\ **Description**\ 
 \ *Concept Ordering*\ 

.. note::
    null
