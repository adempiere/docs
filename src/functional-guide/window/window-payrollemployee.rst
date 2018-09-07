
.. _functional-guide/window/window-payrollemployee:

================
Payroll Employee
================

Maintain Payroll Employee

Help
====
The Payroll Employee Window is used to define the Employees into the Organizational

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Business Partner
----------------
\ **Description**\ 
 \ *Business Partner*\ 
\ **Help**\ 
 \ *The Payroll Employee Window is used to define the Jobs into the Organizational Structure for a Company*\ 

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

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Name 2
------
\ **Description**\ 
 \ *Additional Name*\ 

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

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Tax ID
------
\ **Description**\ 
 \ *Tax Identification*\ 
\ **Help**\ 
 \ *The Tax ID field identifies the legal Identification number of this Entity.*\ 

Payment Rule
------------
\ **Description**\ 
 \ *Purchase payment option*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of purchase payment.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Indicates if  the business partner is a sales representative or company agent*\ 
\ **Help**\ 
 \ *The Sales Rep checkbox indicates if this business partner is a sales representative. A sales representative may also be an employee, but does not need to be.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Gender
------

Blood Group
-----------

Birthday
--------
\ **Description**\ 
 \ *Birthday or Anniversary day*\ 
\ **Help**\ 
 \ *Birthday or Anniversary day*\ 

Place of Birth (Location)
-------------------------
\ **Description**\ 
 \ *Place of Birth (Location)*\ 

Father's Name
-------------
\ **Description**\ 
 \ *Father's Name*\ 

Marital Status
--------------

Employee
--------
\ **Description**\ 
 \ *Maintain Payroll Employee*\ 
\ **Help**\ 
 \ *The Business Partner Tab defines any Entity with whom an organization transacts.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Name 2
------
\ **Description**\ 
 \ *Additional Name*\ 

National Code
-------------

Social Security Code
--------------------

Nationality
-----------
\ **Description**\ 
 \ *Nationality*\ 

Identification Mark
-------------------
\ **Description**\ 
 \ *Identification Mark*\ 
\ **Help**\ 
 \ *Identification Mark*\ 

Marital Status
--------------

Marriage Anniversary Date
-------------------------
\ **Description**\ 
 \ *Marriage Anniversary Date*\ 
\ **Help**\ 
 \ *Marriage Anniversary Date*\ 

Partner's Name
--------------
\ **Description**\ 
 \ *Partner's Name*\ 
\ **Help**\ 
 \ *The Partner's Name of an Employee*\ 

Partners Birth Date
-------------------
\ **Description**\ 
 \ *Partners Birth Date*\ 
\ **Help**\ 
 \ *The Partners Birth Date*\ 

Validation code
---------------
\ **Description**\ 
 \ *Validation Code*\ 
\ **Help**\ 
 \ *The Validation Code displays the date, time and message of the error.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Payroll
-------

Job Type
--------
\ **Description**\ 
 \ *The Job Type for a Job Openings*\ 
\ **Help**\ 
 \ *Job Type for Recruitment Management*\ 

Payroll Department
------------------

Payroll Job
-----------

Start Date
----------
\ **Description**\ 
 \ *First effective day (inclusive)*\ 
\ **Help**\ 
 \ *The Start Date indicates the first or starting date*\ 

End Date
--------
\ **Description**\ 
 \ *Last effective date (inclusive)*\ 
\ **Help**\ 
 \ *The End Date indicates the last date in this range.*\ 

Manager
-------
\ **Description**\ 
 \ *Defines employee as manager*\ 
\ **Help**\ 
 \ *The Manager defines employee as manager*\ 

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

Employee Type
-------------
\ **Description**\ 
 \ *Employee Type*\ 

Employee Status
---------------

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

Job Openings
------------
\ **Description**\ 
 \ *Job Openings for Recruitment Management*\ 
\ **Help**\ 
 \ *The Job Opening required for a Department*\ 

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

Daily Salary
------------
\ **Description**\ 
 \ *Daily Salary*\ 

Monthly Salary
--------------
\ **Description**\ 
 \ *Monthly Salary*\ 
\ **Help**\ 
 \ *The Monthly Salary of an Employee*\ 

Payment Rule
------------
\ **Description**\ 
 \ *How you pay the invoice*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of invoice payment.*\ 

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

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Employee Image
--------------
\ **Description**\ 
 \ *Employee Image*\ 
\ **Help**\ 
 \ *Employee Image*\ 

Thumb Image
-----------
\ **Description**\ 
 \ *Thumb Image*\ 
\ **Help**\ 
 \ *Thumb Image*\ 

Image URL
---------
\ **Description**\ 
 \ *URL of  image*\ 
\ **Help**\ 
 \ *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*\ 

Logo
----

Employee Accounting
-------------------
\ **Description**\ 
 \ *Define Employee Accounting*\ 
\ **Help**\ 
 \ *The Employee Accounting Tab defines the default accounts to use when this business partner is referenced on a expense reimbursement.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Employee Expense
----------------
\ **Description**\ 
 \ *Account for Employee Expenses*\ 
\ **Help**\ 
 \ *The Employee Expense Account identifies the account to use for recording expenses for this employee.*\ 

Employee Prepayment
-------------------
\ **Description**\ 
 \ *Account for Employee Expense Prepayments*\ 
\ **Help**\ 
 \ *The Employee Prepayment Account identifies the account to use for recording expense advances made to this employee.*\ 

Attribute
---------
\ **Description**\ 
 \ *Business Partner*\ 
\ **Help**\ 
 \ *The Business Partner Tab defines any Entity with whom an organization transacts.*\ 

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

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Max Value
---------

Min Value
---------

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

Bank Account
------------
\ **Description**\ 
 \ *Define Bank Account*\ 
\ **Help**\ 
 \ *The Define Bank Account Tab defines the banking information for this business partner.  This data is used for processing payments and remittances.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Payroll Account
---------------
\ **Description**\ 
 \ *Used for mark a bank account defined for payment of payroll*\ 
\ **Help**\ 
 \ *If you mark a business partner bank account like payroll account, it can be used for generate payment of payroll*\ 

ACH
---
\ **Description**\ 
 \ *Automatic Clearing House*\ 
\ **Help**\ 
 \ *The ACH checkbox indicates if this Bank Account accepts ACH transactions.*\ 

Bank
----
\ **Description**\ 
 \ *Bank*\ 
\ **Help**\ 
 \ *The Bank is a unique identifier of a Bank for this Organization or for a Business Partner with whom this Organization transacts.*\ 

Bank Account Type
-----------------
\ **Description**\ 
 \ *Bank Account Type*\ 
\ **Help**\ 
 \ *The Bank Account Type field indicates the type of account (savings, checking etc) this account  is defined as.*\ 

Account Usage
-------------
\ **Description**\ 
 \ *Business Partner Bank Account usage*\ 
\ **Help**\ 
 \ *Determines how the bank account is used.*\ 

Routing No
----------
\ **Description**\ 
 \ *Bank Routing Number*\ 
\ **Help**\ 
 \ *The Bank Routing Number (ABA Number) identifies a legal Bank.  It is used in routing checks and electronic transactions.*\ 

Account No
----------
\ **Description**\ 
 \ *Account Number*\ 
\ **Help**\ 
 \ *The Account Number indicates the Number assigned to this bank account.*\ 

Credit Card
-----------
\ **Description**\ 
 \ *Credit Card (Visa, MC, AmEx)*\ 
\ **Help**\ 
 \ *The Credit Card drop down list box is used for selecting the type of Credit Card presented for payment.*\ 

Number
------
\ **Description**\ 
 \ *Credit Card Number*\ 
\ **Help**\ 
 \ *The Credit Card number indicates the number on the credit card, without blanks or spaces.*\ 

Verification Code
-----------------
\ **Description**\ 
 \ *Credit Card Verification code on credit card*\ 
\ **Help**\ 
 \ *The Credit Card Verification indicates the verification code on the credit card (AMEX 4 digits on front; MC,Visa 3 digits back)*\ 

Exp. Month
----------
\ **Description**\ 
 \ *Expiry Month*\ 
\ **Help**\ 
 \ *The Expiry Month indicates the expiry month for this credit card.*\ 

Exp. Year
---------
\ **Description**\ 
 \ *Expiry Year*\ 
\ **Help**\ 
 \ *The Expiry Year indicates the expiry year for this credit card.*\ 

Account Name
------------
\ **Description**\ 
 \ *Name on Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Name of the Credit Card or Account holder.*\ 

Account Country
---------------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *Account Country Name*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Account City
------------
\ **Description**\ 
 \ *City or the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Account City indicates the City of the Credit Card or Account holder*\ 

Account Street
--------------
\ **Description**\ 
 \ *Street address of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Street Address of the Credit Card or Account holder.*\ 

Account Zip/Postal
------------------
\ **Description**\ 
 \ *Zip Code of the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Zip Code of the Credit Card or Account Holder.*\ 

Account EMail
-------------
\ **Description**\ 
 \ *Email Address*\ 
\ **Help**\ 
 \ *The EMail Address indicates the EMail address off the Credit Card or Account holder.*\ 

Driver License
--------------
\ **Description**\ 
 \ *Payment Identification - Driver License*\ 
\ **Help**\ 
 \ *The Driver's License being used as identification.*\ 

Social Security No
------------------
\ **Description**\ 
 \ *Payment Identification - Social Security No*\ 
\ **Help**\ 
 \ *The Social Security number being used as identification.*\ 

Address verified
----------------
\ **Description**\ 
 \ *This address has been verified*\ 
\ **Help**\ 
 \ *The Address Verified indicates if the address has been verified by the Credit Card Company.*\ 

Zip verified
------------
\ **Description**\ 
 \ *The Zip Code has been verified*\ 
\ **Help**\ 
 \ *The Zip Verified indicates if the zip code has been verified by the Credit Card Company.*\ 

Location
--------
\ **Description**\ 
 \ *Define Location*\ 
\ **Help**\ 
 \ *The Location Tab defines the physical location of a business partner.  A business partner may have multiple location records.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Phone
-----
\ **Description**\ 
 \ *Identifies a telephone number*\ 
\ **Help**\ 
 \ *The Phone field identifies a telephone number*\ 

2nd Phone
---------
\ **Description**\ 
 \ *Identifies an alternate telephone number.*\ 
\ **Help**\ 
 \ *The 2nd Phone field identifies an alternate telephone number.*\ 

Fax
---
\ **Description**\ 
 \ *Facsimile number*\ 
\ **Help**\ 
 \ *The Fax identifies a facsimile number for this Business Partner or  Location*\ 

Contact (User)
--------------
\ **Description**\ 
 \ *Maintain User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

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

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Birthday
--------
\ **Description**\ 
 \ *Birthday or Anniversary day*\ 
\ **Help**\ 
 \ *Birthday or Anniversary day*\ 

Phone
-----
\ **Description**\ 
 \ *Identifies a telephone number*\ 
\ **Help**\ 
 \ *The Phone field identifies a telephone number*\ 

2nd Phone
---------
\ **Description**\ 
 \ *Identifies an alternate telephone number.*\ 
\ **Help**\ 
 \ *The 2nd Phone field identifies an alternate telephone number.*\ 

Fax
---
\ **Description**\ 
 \ *Facsimile number*\ 
\ **Help**\ 
 \ *The Fax identifies a facsimile number for this Business Partner or  Location*\ 

Is In Payroll
-------------
\ **Description**\ 
 \ *Defined if any User Contact will be used for Calculate Payroll*\ 

Interest Area
-------------
\ **Description**\ 
 \ *Business Partner Contact Interest Area*\ 
\ **Help**\ 
 \ *Interest Area can be used for Marketing Campaigns*\ 

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

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Interest Area
-------------
\ **Description**\ 
 \ *Interest Area or Topic*\ 
\ **Help**\ 
 \ *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Subscribe Date
--------------
\ **Description**\ 
 \ *Date the contact actively subscribed*\ 
\ **Help**\ 
 \ *Date the contact subscribe the interest area*\ 

Opt-out Date
------------
\ **Description**\ 
 \ *Date the contact opted out*\ 
\ **Help**\ 
 \ *If the field has a date, the customer opted out (unsubscribed) and cannot receive mails for the Interest Area*\ 
