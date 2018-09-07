
.. _functional-guide/window/window-businesspartnergroup:

======================
Business Partner Group
======================

Maintain Business Partner Groups

Help
====
The Business Partner Group window allows you to define the accounting parameters at a group level.  If you define the accounting parameters for a group any Business Partner entered using this group will have these accounting parameters automatically populated.  You can then make any modifications necessary at the Business Partner level.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Groups for Reporting Accounting Defaults*\ 
\ **Help**\ 
 \ *The Business Partner Group Tab allow for the association of business partners for reporting and accounting defaults.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Print Color
-----------
\ **Description**\ 
 \ *Color used for printing and display*\ 
\ **Help**\ 
 \ *Colors used for printing and display*\ 

Priority Base
-------------
\ **Description**\ 
 \ *Base of Priority*\ 
\ **Help**\ 
 \ *When deriving the Priority from Importance, the Base is "added" to the User Importance.*\ 

Confidential Info
-----------------
\ **Description**\ 
 \ *Can enter confidential information*\ 
\ **Help**\ 
 \ *When entering/updating Requests over the web, the user can mark his info as confidential*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Purchase Pricelist
------------------
\ **Description**\ 
 \ *Price List used by this Business Partner*\ 
\ **Help**\ 
 \ *Identifies the price list used by a Vendor for products purchased by this organization.*\ 

Discount Schema
---------------
\ **Description**\ 
 \ *Schema to calculate the trade discount percentage*\ 
\ **Help**\ 
 \ *After calculation of the (standard) price, the trade discount percentage is calculated and applied resulting in the final price.*\ 

PO Discount Schema
------------------
\ **Description**\ 
 \ *Schema to calculate the purchase trade discount percentage*\ 

Credit Watch %
--------------
\ **Description**\ 
 \ *Credit Watch - Percent of Credit Limit when OK switches to Watch*\ 
\ **Help**\ 
 \ *If Adempiere maintains credit status, the status "Credit OK" is moved to "Credit Watch" if the credit available reaches the percent entered.  If not defined, 90% is used.*\ 

Price Match Tolerance
---------------------
\ **Description**\ 
 \ *PO-Invoice Match Price Tolerance in percent of the purchase price*\ 
\ **Help**\ 
 \ *Tolerance in Percent of matching the purchase order price to the invoice price.  The difference is posted as Invoice Price Tolerance for Standard Costing.  If defined, the PO-Invoice match must be explicitly approved, if the matching difference is greater then the tolerance.
Example: if the purchase price is $100 and the tolerance is 1 (percent), the invoice price must be between $99 and 101 to be automatically approved.*\ 

Dunning
-------
\ **Description**\ 
 \ *Dunning Rules for overdue invoices*\ 
\ **Help**\ 
 \ *The Dunning indicates the rules and method of dunning for past due payments.*\ 

Accounting
----------
\ **Description**\ 
 \ *Define Accounting*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the default accounts for any business partner that references this group.  These default values can be modified for each business partner if required.*\ 

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

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

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

Payment Discount Expense
------------------------
\ **Description**\ 
 \ *Payment Discount Expense Account*\ 
\ **Help**\ 
 \ *Indicates the account to be charged for payment discount expenses.*\ 

Write-off
---------
\ **Description**\ 
 \ *Account for Receivables write-off*\ 
\ **Help**\ 
 \ *The Write Off Account identifies the account to book write off transactions to.*\ 

Not-invoiced Receivables
------------------------
\ **Description**\ 
 \ *Account for not invoiced Receivables*\ 
\ **Help**\ 
 \ *The Not Invoiced Receivables account indicates the account used for recording receivables that have not yet been invoiced.*\ 

Not-invoiced Revenue
--------------------
\ **Description**\ 
 \ *Account for not invoiced Revenue*\ 
\ **Help**\ 
 \ *The Not Invoiced Revenue account indicates the account used for recording revenue that has not yet been invoiced.*\ 

Unearned Revenue
----------------
\ **Description**\ 
 \ *Account for unearned revenue*\ 
\ **Help**\ 
 \ *The Unearned Revenue indicates the account used for recording invoices sent for products or services not yet delivered.  It is used in revenue recognition*\ 

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

Payment Discount Revenue
------------------------
\ **Description**\ 
 \ *Payment Discount Revenue Account*\ 
\ **Help**\ 
 \ *Indicates the account to be charged for payment discount revenues.*\ 

Not-invoiced Receipts
---------------------
\ **Description**\ 
 \ *Account for not-invoiced Material Receipts*\ 
\ **Help**\ 
 \ *The Not Invoiced Receipts account indicates the account used for recording receipts for materials that have not yet been invoiced.*\ 

Copy Accounts
-------------
\ **Description**\ 
 \ *Copy and overwrite Accounts to Business Partners of this group*\ 
\ **Help**\ 
 \ *If you copy and overwrite the current default values, you may have to repeat previous updates (e.g. set the receivebles account, ...)*\ 

Assigned Partners
-----------------
\ **Description**\ 
 \ *Business Partners in Group*\ 

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

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Language
--------
\ **Description**\ 
 \ *Language for this Business Partner if Multi-Language enabled*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting documents. It requires, that on Client level, Multi-Lingual documents are selected and that you have created/loaded the language.*\ 

Prospect
--------
\ **Description**\ 
 \ *Indicates this is a Prospect*\ 
\ **Help**\ 
 \ *The Prospect checkbox indicates an entity that is an active prospect.*\ 

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
