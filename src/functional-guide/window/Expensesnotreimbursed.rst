
.. _window-expensesnotreimbursed:

=========================
Expenses (not reimbursed)
=========================

View expenses and charges not reimbursed

Help
====
Before reimbursing expenses, check the open expense items

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Employee, Vendor
----------------
\ **Description**\ 
 \ *Business Partner to be reimbursed*\ 
\ **Help**\ 
 \ *Select the business partner to be reimbursed.*\ 

.. note::
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

Name 2
------
\ **Description**\ 
 \ *Additional Name*\ 

Vendor
------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Vendor*\ 
\ **Help**\ 
 \ *The Vendor checkbox indicates if this Business Partner is a Vendor.  If it is selected, additional fields will display which further identify this vendor.*\ 

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

PO Payment Term
---------------
\ **Description**\ 
 \ *Payment rules for a purchase order*\ 
\ **Help**\ 
 \ *The PO Payment Term indicates the payment term that will be used when this purchase order becomes an invoice.*\ 

Open Balance
------------
\ **Description**\ 
 \ *Total Open Balance Amount in primary Accounting Currency*\ 
\ **Help**\ 
 \ *The Total Open Balance Amount is the calculated open item amount for Customer and Vendor activity.  If the Balance is below zero, we owe the Business Partner.  The amount is used for Credit Management.
Invoices and Payment Allocations determine the Open Balance (i.e. not Orders or Payments).*\ 

Report Line
-----------
\ **Description**\ 
 \ *Time and Expense Report Line (not reimbursed)*\ 
\ **Help**\ 
 \ *View and modify Time and Expense Report Lines. It lists expense items for the business partner on the expense header where the expense lines were not invoiced yet.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Expense Report
--------------
\ **Description**\ 
 \ *Time and Expense Report*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Expense Date
------------
\ **Description**\ 
 \ *Date of expense*\ 
\ **Help**\ 
 \ *Date of expense*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Time Report
-----------
\ **Description**\ 
 \ *Line is a time report only (no expense)*\ 
\ **Help**\ 
 \ *The line contains only time information*\ 

Invoice Line
------------
\ **Description**\ 
 \ *Invoice Detail Line*\ 
\ **Help**\ 
 \ *The Invoice Line uniquely identifies a single line of an Invoice.*\ 

Invoiced
--------
\ **Description**\ 
 \ *Is this invoiced?*\ 
\ **Help**\ 
 \ *If selected, invoices are created*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Quantity Reimbursed
-------------------
\ **Description**\ 
 \ *The reimbursed quantity*\ 
\ **Help**\ 
 \ *The reimbursed quantity is derived from the entered quantity and can be overwritten when approving the expense report.*\ 

Expense Amount
--------------
\ **Description**\ 
 \ *Amount for this expense*\ 
\ **Help**\ 
 \ *Expense amount in currency*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Converted Amount
----------------
\ **Description**\ 
 \ *Converted Amount*\ 
\ **Help**\ 
 \ *The Converted Amount is the result of multiplying the Source Amount by the Conversion Rate for this target currency.*\ 

Price Reimbursed
----------------
\ **Description**\ 
 \ *The reimbursed price (in currency of the employee's AP price list)*\ 
\ **Help**\ 
 \ *The reimbursed price is derived from the converted price and can be overwritten when approving the expense report.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for a document*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount for a document.*\ 

Line Amount
-----------
\ **Description**\ 
 \ *Line Extended Amount (Quantity * Actual Price) without Freight and Charges*\ 
\ **Help**\ 
 \ *Indicates the extended line amount based on the quantity and the actual price.  Any additional charges or freight are not included.  The Amount may or may not include tax.  If the price list is inclusive tax, the line amount is the same as the line total.*\ 

Line Total
----------
\ **Description**\ 
 \ *Total line amount incl. Tax*\ 
\ **Help**\ 
 \ *Total line amount*\ 

Time Type
---------
\ **Description**\ 
 \ *Type of time recorded*\ 
\ **Help**\ 
 \ *Differentiate time types for reporting purposes (In parallel to Activities)*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Project Task
------------
\ **Description**\ 
 \ *Actual Project Task in a Phase*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 
