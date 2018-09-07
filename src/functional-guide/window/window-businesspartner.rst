
.. _functional-guide/window/window-businesspartner:

================
Business Partner
================

Maintain Business Partners

Help
====
The Business Partner window allows you do define any party with whom you transact.  This includes customers, vendors and employees.  Prior to entering or importing products, you must define your vendors.  Prior to generating Orders you must define your customers.  This window holds all information about your business partner and the values entered will be used to generate all document transactions

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

Greeting
--------
\ **Description**\ 
 \ *Greeting to print on correspondence*\ 
\ **Help**\ 
 \ *The Greeting identifies the greeting to print on correspondence.*\ 

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

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Credit Status
-------------
\ **Description**\ 
 \ *Business Partner Credit Status*\ 
\ **Help**\ 
 \ *Credit Management is inactive if Credit Status is No Credit Check, Credit Stop or if the Credit Limit is 0.
If active, the status is set automatically set to Credit Hold, if the Total Open Balance (including Vendor activities)  is higher then the Credit Limit. It is set to Credit Watch, if above 90% of the Credit Limit and Credit OK otherwise.*\ 

Open Balance
------------
\ **Description**\ 
 \ *Total Open Balance Amount in primary Accounting Currency*\ 
\ **Help**\ 
 \ *The Total Open Balance Amount is the calculated open item amount for Customer and Vendor activity.  If the Balance is below zero, we owe the Business Partner.  The amount is used for Credit Management.
Invoices and Payment Allocations determine the Open Balance (i.e. not Orders or Payments).*\ 

Tax ID
------
\ **Description**\ 
 \ *Tax Identification*\ 
\ **Help**\ 
 \ *The Tax ID field identifies the legal Identification number of this Entity.*\ 

SO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on sales*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on sales, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

PO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on purchases*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on purchases, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

Tax Group
---------

D-U-N-S
-------
\ **Description**\ 
 \ *Dun & Bradstreet Number*\ 
\ **Help**\ 
 \ *Used for EDI - For details see   www.dnb.com/dunsno/list.htm*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

NAICS/SIC
---------
\ **Description**\ 
 \ *Standard Industry Code or its successor NAIC - http://www.osha.gov/oshstats/sicser.html*\ 
\ **Help**\ 
 \ *The NAICS/SIC identifies either of these codes that may be applicable to this Business Partner.*\ 

Rating
------
\ **Description**\ 
 \ *Classification or Importance*\ 
\ **Help**\ 
 \ *The Rating is used to differentiate the importance*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this Business Partner if Multi-Language enabled*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting documents. It requires, that on Client level, Multi-Lingual documents are selected and that you have created/loaded the language.*\ 

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Prospect
--------
\ **Description**\ 
 \ *Indicates this is a Prospect*\ 
\ **Help**\ 
 \ *The Prospect checkbox indicates an entity that is an active prospect.*\ 

Link Organization
-----------------
\ **Description**\ 
 \ *Link Business Partner to an Organization*\ 
\ **Help**\ 
 \ *If the Business Partner is another Organization, select the Organization or set to empty to create a new Organization.  You link a Business Partner to an Organization to create explicit Documents for Inter-Org transaction.
If you create a new Organization, you may supply a Organization Type.  If you select a Role, the access to the new Organization is limited to that role, otherwise all (non manual) roles of the Client will have access to the new Organization.*\ 

Potential Life Time Value
-------------------------
\ **Description**\ 
 \ *Total Revenue expected*\ 
\ **Help**\ 
 \ *The Potential Life Time Value is the anticipated revenue in primary accounting currency to be generated by the Business Partner.*\ 

Actual Life Time Value
----------------------
\ **Description**\ 
 \ *Actual Life Time Revenue*\ 
\ **Help**\ 
 \ *The Actual Life Time Value is the recorded revenue in primary accounting currency generated by the Business Partner.*\ 

Acquisition Cost
----------------
\ **Description**\ 
 \ *The cost of gaining the prospect as a customer*\ 
\ **Help**\ 
 \ *The Acquisition Cost identifies the cost associated with making this prospect a customer.*\ 

Employees
---------
\ **Description**\ 
 \ *Number of employees*\ 
\ **Help**\ 
 \ *Indicates the number of employees for this Business Partner.  This field displays only for Prospects.*\ 

Share
-----
\ **Description**\ 
 \ *Share of Customer's business as a percentage*\ 
\ **Help**\ 
 \ *The Share indicates the percentage of this Business Partner's volume of the products supplied.*\ 

Sales Volume in 1.000
---------------------
\ **Description**\ 
 \ *Total Volume of Sales in Thousands of Currency*\ 
\ **Help**\ 
 \ *The Sales Volume indicates the total volume of sales for a Business Partner.*\ 

First Sale
----------
\ **Description**\ 
 \ *Date of First Sale*\ 
\ **Help**\ 
 \ *The First Sale Date identifies the date of the first sale to this Business Partner*\ 

Logo
----

Customer
--------
\ **Description**\ 
 \ *Define Customer Parameters*\ 
\ **Help**\ 
 \ *The Customer Tab defines a Business Partner who is a customer of this organization.  If the Customer check box is selected then the necessary fields will display.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Customer
--------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Customer*\ 
\ **Help**\ 
 \ *The Customer checkbox indicates if this Business Partner is a customer.  If it is select additional fields will display which further define this customer.*\ 

Document Copies
---------------
\ **Description**\ 
 \ *Number of copies to be printed*\ 
\ **Help**\ 
 \ *The Document Copies indicates the number of copies of each document that will be generated.*\ 

Invoice Rule
------------
\ **Description**\ 
 \ *Frequency and method of invoicing*\ 
\ **Help**\ 
 \ *The Invoice Rule defines how a Business Partner is invoiced and the frequency of invoicing.*\ 

Invoice Schedule
----------------
\ **Description**\ 
 \ *Schedule for generating Invoices*\ 
\ **Help**\ 
 \ *The Invoice Schedule identifies the frequency used when generating invoices.*\ 

Delivery Rule
-------------
\ **Description**\ 
 \ *Defines the timing of Delivery*\ 
\ **Help**\ 
 \ *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*\ 

Delivery Via
------------
\ **Description**\ 
 \ *How the order will be delivered*\ 
\ **Help**\ 
 \ *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Discount Schema
---------------
\ **Description**\ 
 \ *Schema to calculate the trade discount percentage*\ 
\ **Help**\ 
 \ *After calculation of the (standard) price, the trade discount percentage is calculated and applied resulting in the final price.*\ 

Flat Discount %
---------------
\ **Description**\ 
 \ *Flat discount percentage*\ 

Payment Rule
------------
\ **Description**\ 
 \ *How you pay the invoice*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of invoice payment.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Dunning
-------
\ **Description**\ 
 \ *Dunning Rules for overdue invoices*\ 
\ **Help**\ 
 \ *The Dunning indicates the rules and method of dunning for past due payments.*\ 

Order Reference
---------------
\ **Description**\ 
 \ *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*\ 
\ **Help**\ 
 \ *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*\ 

Discount Printed
----------------
\ **Description**\ 
 \ *Print Discount on Invoice and Order*\ 
\ **Help**\ 
 \ *The Discount Printed Checkbox indicates if the discount will be printed on the document.*\ 

Order Description
-----------------
\ **Description**\ 
 \ *Description to be used on orders*\ 
\ **Help**\ 
 \ *The Order Description identifies the standard description to use on orders for this Customer.*\ 

Invoice Print Format
--------------------
\ **Description**\ 
 \ *Print Format for printing Invoices*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Min Shelf Life %
----------------
\ **Description**\ 
 \ *Minimum Shelf Life in percent based on Product Instance Guarantee Date*\ 
\ **Help**\ 
 \ *Minimum Shelf Life of products with Guarantee Date instance. If > 0 you cannot select products with a shelf life ((Guarantee Date-Today) / Guarantee Days) less than the minimum shelf life, unless you select "Show All"*\ 

Credit Limit
------------
\ **Description**\ 
 \ *Total outstanding invoice amounts allowed*\ 
\ **Help**\ 
 \ *The Credit Limit indicates the total amount allowed "on account" in primary accounting currency.  If the Credit Limit is 0, no check is performed.  Credit Management is based on the Total Open Amount, which includes Vendor activities.*\ 

Credit Used
-----------
\ **Description**\ 
 \ *Current open balance*\ 
\ **Help**\ 
 \ *The Credit Used indicates the total amount of open or unpaid invoices in primary accounting currency for the Business Partner. Credit Management is based on the Total Open Amount, which includes Vendor activities.*\ 

Dunning Grace Date
------------------

AR Trial balance
----------------
\ **Description**\ 
 \ *Trial Balance for a period or date range*\ 
\ **Help**\ 
 \ *Select a Period (current period if empty) or enter a Account Date Range. If an account is selected, the balance is calculated based on the account type and the primary calendar of the client (i.e. for revenue/expense accounts from the beginning of the year). If no account is selected, the balance is the sum of all transactions before the selected account range or first day of the period selected. You can select an alternative Reporting Hierarchy.*\ 

Unapplied AR Payments
---------------------
\ **Description**\ 
 \ *Payment Detail Report*\ 
\ **Help**\ 
 \ *Type adjusted payments (receipts positive, payments negative) with allocated and available amounts*\ 

Open Invoices
-------------
\ **Description**\ 
 \ *Open Item (Invoice) List*\ 
\ **Help**\ 
 \ *Displays all unpaid invoices for a given Business Partner and date range. Please note that Invoices paid in Cash will appear in Open Items until the Cash Journal is processed.*\ 

Not Posted Invoice
------------------

Customer Accounting
-------------------
\ **Description**\ 
 \ *Define Customer Accounting*\ 
\ **Help**\ 
 \ *The Customer Accounting Tab defines the default accounts to use when this business partner is referenced on an accounts receivable transaction.*\ 

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

Customer Receivables
--------------------
\ **Description**\ 
 \ *Account for Customer Receivables*\ 
\ **Help**\ 
 \ *The Customer Receivables Accounts indicates the account to be used for recording transaction for customers receivables.*\ 

Receivable Services
-------------------
\ **Description**\ 
 \ *Customer Accounts Receivables Services Account*\ 
\ **Help**\ 
 \ *Account to post services related Accounts Receivables if you want to differentiate between Services and Product related revenue. This account is only used, if posting to service accounts is enabled in the accounting schema.*\ 

Customer Prepayment
-------------------
\ **Description**\ 
 \ *Account for customer prepayments*\ 
\ **Help**\ 
 \ *The Customer Prepayment account indicates the account to be used for recording prepayments from a customer.*\ 

Vendor
------
\ **Description**\ 
 \ *Define Vendor Parameters*\ 
\ **Help**\ 
 \ *The Vendor Tab defines a Business Partner that is a Vendor for this Organization.  If the Vendor check box is selected the necessary fields will display.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Vendor
------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Vendor*\ 
\ **Help**\ 
 \ *The Vendor checkbox indicates if this Business Partner is a Vendor.  If it is selected, additional fields will display which further identify this vendor.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Indicates if  the business partner is a sales representative or company agent*\ 
\ **Help**\ 
 \ *The Sales Rep checkbox indicates if this business partner is a sales representative. A sales representative may also be an employee, but does not need to be.*\ 

Payment Rule
------------
\ **Description**\ 
 \ *Purchase payment option*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of purchase payment.*\ 

PO Payment Term
---------------
\ **Description**\ 
 \ *Payment rules for a purchase order*\ 
\ **Help**\ 
 \ *The PO Payment Term indicates the payment term that will be used when this purchase order becomes an invoice.*\ 

Purchase Pricelist
------------------
\ **Description**\ 
 \ *Price List used by this Business Partner*\ 
\ **Help**\ 
 \ *Identifies the price list used by a Vendor for products purchased by this organization.*\ 

PO Discount Schema
------------------
\ **Description**\ 
 \ *Schema to calculate the purchase trade discount percentage*\ 

Is Manufacturer
---------------
\ **Description**\ 
 \ *Indicate role of this Business partner as Manufacturer*\ 

AP Trial balance
----------------
\ **Description**\ 
 \ *Trial Balance for a period or date range*\ 
\ **Help**\ 
 \ *Select a Period (current period if empty) or enter a Account Date Range. If an account is selected, the balance is calculated based on the account type and the primary calendar of the client (i.e. for revenue/expense accounts from the beginning of the year). If no account is selected, the balance is the sum of all transactions before the selected account range or first day of the period selected. You can select an alternative Reporting Hierarchy.*\ 

Unapplied AR Payments
---------------------
\ **Description**\ 
 \ *Payment Detail Report*\ 
\ **Help**\ 
 \ *Type adjusted payments (receipts positive, payments negative) with allocated and available amounts*\ 

Open Invoices
-------------
\ **Description**\ 
 \ *Open Item (Invoice) List*\ 
\ **Help**\ 
 \ *Displays all unpaid invoices for a given Business Partner and date range. Please note that Invoices paid in Cash will appear in Open Items until the Cash Journal is processed.*\ 

Not Posted Invoice
------------------

Vendor Accounting
-----------------
\ **Description**\ 
 \ *Define Vendor Accounting*\ 
\ **Help**\ 
 \ *The Vendor Accounting Tab defines the default accounts to use when this business partner is referenced in an accounts payable transaction.*\ 

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

Vendor Liability
----------------
\ **Description**\ 
 \ *Account for Vendor Liability*\ 
\ **Help**\ 
 \ *The Vendor Liability account indicates the account used for recording transactions for vendor liabilities*\ 

Vendor Service Liability
------------------------
\ **Description**\ 
 \ *Account for Vendor Service Liability*\ 
\ **Help**\ 
 \ *The Vendor Service Liability account indicates the account to use for recording service liabilities.  It is used if you need to distinguish between Liability for products and services. This account is only used, if posting to service accounts is enabled in the accounting schema.*\ 

Vendor Prepayment
-----------------
\ **Description**\ 
 \ *Account for Vendor Prepayments*\ 
\ **Help**\ 
 \ *The Vendor Prepayment Account indicates the account used to record prepayments from a vendor.*\ 

Employee
--------
\ **Description**\ 
 \ *Define Employee Parameters*\ 
\ **Help**\ 
 \ *The Employee Tab defines a Business Partner who is an Employee of this organization.  If the Employee is also a Sales Representative then the check box should be selected.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Indicates if  the business partner is a sales representative or company agent*\ 
\ **Help**\ 
 \ *The Sales Rep checkbox indicates if this business partner is a sales representative. A sales representative may also be an employee, but does not need to be.*\ 

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

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

ACH
---
\ **Description**\ 
 \ *Automatic Clearing House*\ 
\ **Help**\ 
 \ *The ACH checkbox indicates if this Bank Account accepts ACH transactions.*\ 

Account Usage
-------------
\ **Description**\ 
 \ *Business Partner Bank Account usage*\ 
\ **Help**\ 
 \ *Determines how the bank account is used.*\ 

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

Account Street
--------------
\ **Description**\ 
 \ *Street address of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Street Address of the Credit Card or Account holder.*\ 

Account City
------------
\ **Description**\ 
 \ *City or the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Account City indicates the City of the Credit Card or Account holder*\ 

Account Zip/Postal
------------------
\ **Description**\ 
 \ *Zip Code of the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Zip Code of the Credit Card or Account Holder.*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Account Country
---------------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *Account Country Name*\ 

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

Account EMail
-------------
\ **Description**\ 
 \ *Email Address*\ 
\ **Help**\ 
 \ *The EMail Address indicates the EMail address off the Credit Card or Account holder.*\ 

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

ISDN
----
\ **Description**\ 
 \ *ISDN or modem line*\ 
\ **Help**\ 
 \ *The ISDN identifies a ISDN or Modem line number.*\ 

Ship Address
------------
\ **Description**\ 
 \ *Business Partner Shipment Address*\ 
\ **Help**\ 
 \ *If the Ship Address is selected, the location is used to ship goods to a customer or receive goods from a vendor.*\ 

Invoice Address
---------------
\ **Description**\ 
 \ *Business Partner Invoice/Bill Address*\ 
\ **Help**\ 
 \ *If the Invoice Address is selected, the location is used to send invoices to a customer or receive invoices from a vendor.*\ 

Pay-From Address
----------------
\ **Description**\ 
 \ *Business Partner pays from that address and we'll send dunning letters there*\ 
\ **Help**\ 
 \ *If the Pay-From Address is selected, this location is the address the Business Partner pays from and where dunning letters will be sent to.*\ 

Remit-To Address
----------------
\ **Description**\ 
 \ *Business Partner payment address*\ 
\ **Help**\ 
 \ *If the Remit-To Address is selected, the location is used to send payments to the vendor.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

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

Is Project Manager
------------------
\ **Description**\ 
 \ *Is Project Manager*\ 
\ **Help**\ 
 \ *Is Project Manager indicates if the contact is assigned as project manager to a project*\ 

Is Project Member
-----------------
\ **Description**\ 
 \ *Is Project Member*\ 
\ **Help**\ 
 \ *Is Project Member indicates if the contact is assigned to a project and will receive notifications of any project changes*\ 

Login User
----------
\ **Help**\ 
 \ *Define if the user can login*\ 

Internal User
-------------
\ **Description**\ 
 \ *Is just for use internal*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Password
--------
\ **Description**\ 
 \ *Password of any length (case sensitive)*\ 
\ **Help**\ 
 \ *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*\ 

Webstore User
-------------
\ **Description**\ 
 \ *Is a user for Webstore*\ 
\ **Help**\ 
 \ *It is created from Webstore*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

Greeting
--------
\ **Description**\ 
 \ *Greeting to print on correspondence*\ 
\ **Help**\ 
 \ *The Greeting identifies the greeting to print on correspondence.*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Title
-----
\ **Description**\ 
 \ *Name this entity is referred to as*\ 
\ **Help**\ 
 \ *The Title indicates the name that an entity is referred to as.*\ 

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

Notification Type
-----------------
\ **Description**\ 
 \ *Type of Notifications*\ 
\ **Help**\ 
 \ *Emails or Notification sent out for Request Updates, etc.*\ 

Position
--------
\ **Description**\ 
 \ *Job Position*\ 

Full BP Access
--------------
\ **Description**\ 
 \ *The user/contact has full access to Business Partner information and resources*\ 
\ **Help**\ 
 \ *If selected, the user has full access to the Business Partner (BP) information (Business Documents like Orders, Invoices - Requests) or resources (Assets, Downloads). If you deselect it, the user has no access rights unless, you explicitly grant it in tab "BP Access"*\ 

EMail Verify
------------
\ **Description**\ 
 \ *Date Email was verified*\ 

Verification Info
-----------------
\ **Description**\ 
 \ *Verification information of EMail Address*\ 
\ **Help**\ 
 \ *The field contains additional information how the EMail Address has been verified*\ 

Last Contact
------------
\ **Description**\ 
 \ *Date this individual was last contacted*\ 
\ **Help**\ 
 \ *The Last Contact indicates the date that this Business Partner Contact was last contacted.*\ 

Last Result
-----------
\ **Description**\ 
 \ *Result of last contact*\ 
\ **Help**\ 
 \ *The Last Result identifies the result of the last contact made.*\ 

BP Access
---------
\ **Description**\ 
 \ *Access of the User/Contact to Business Partner information and resources*\ 
\ **Help**\ 
 \ *If on User level, "Full BP Access" is NOT selected, you need to give access explicitly here.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Access Type
-----------
\ **Description**\ 
 \ *Type of Access of the user/contact to Business Partner information and resources*\ 
\ **Help**\ 
 \ *If on User level, "Full BP Access" is NOT selected, give access explicitly*\ 

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

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

Price
-----
\ **Description**\ 
 \ *Business Partner specific prices*\ 
\ **Help**\ 
 \ *Prices and discounts specified here will override the selected price list price and discount schema discount.*\ 

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

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Price Override Type
-------------------
\ **Description**\ 
 \ *Type of price override, fixed price or discount off list*\ 

Break Value
-----------
\ **Description**\ 
 \ *Low Value of trade discount break level*\ 
\ **Help**\ 
 \ *Starting Quantity or Amount Value for break level*\ 

Discount %
----------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

List Price
----------
\ **Description**\ 
 \ *List Price*\ 
\ **Help**\ 
 \ *The List Price is the official List Price in the document currency.*\ 

Standard Price
--------------
\ **Description**\ 
 \ *Standard Price*\ 
\ **Help**\ 
 \ *The Standard Price indicates the standard or normal price for a product on this price list*\ 

Limit Price
-----------
\ **Description**\ 
 \ *Lowest price for a product*\ 
\ **Help**\ 
 \ *The Price Limit indicates the lowest price for a product stated in the Price List Currency.*\ 

Net Price
---------
\ **Description**\ 
 \ *Net Price including all discounts*\ 
\ **Help**\ 
 \ *If price is set as "Net Price" no further discounts will be applied.*\ 

Memo
----
\ **Description**\ 
 \ *Business Partner Memo and alerts*\ 
\ **Help**\ 
 \ *Notes on Business Partner*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Alert
-----
\ **Description**\ 
 \ *Display alert message when referenced record is accessed*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

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
