
.. _functional-guide/window/window-accountingschema:

=================
Accounting Schema
=================

Maintain Accounting Schema - For changes to become effective you must re-login

Help
====
The Accounting Schema Window defines an accounting method and the elements that will comprise an account structure. Create and activate elements for detailed accounting for Business Partners, Products, Locations, etc.
Review and change the GL and Default accounts. The actual accounts used in transactions depend on the executing organization; Most of the information is derived from the context.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Accounting Schema
-----------------
\ **Description**\ 
 \ *Define your Account Schema Structure*\ 
\ **Help**\ 
 \ *The Accounting Schema Tab defines the controls used for accounting.  You can define multiple accounting schema per client (for parallel accounting).  
Postings are generated for an accounting schema, if the schema is valid and you have defined GL and Default accounts and after completion of the Add / Copy Accounts process.*\ 

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

GAAP
----
\ **Description**\ 
 \ *Generally Accepted Accounting Principles*\ 
\ **Help**\ 
 \ *The GAAP identifies the account principles that this accounting schema will adhere to.*\ 

Commitment Type
---------------
\ **Description**\ 
 \ *Create Commitment and/or Reservations for Budget Control*\ 
\ **Help**\ 
 \ *The Posting Type Commitments is created when posting Purchase Orders; The Posting Type Reservation is created when posting Requisitions.  This is used for budgetary control.*\ 

Accrual
-------
\ **Description**\ 
 \ *Indicates if Accrual or Cash Based accounting will be used*\ 
\ **Help**\ 
 \ *The Accrual checkbox indicates if this accounting schema will use accrual based account or cash based accounting.  The Accrual method recognizes revenue when the product or service is delivered.  Cash based method recognizes income when then payment is received.*\ 

Costing Method
--------------
\ **Description**\ 
 \ *Indicates how Costs will be calculated*\ 
\ **Help**\ 
 \ *The Costing Method indicates how costs will be calculated (Standard, Average, Lifo, FiFo).  The default costing method is defined on accounting schema level and can be optionally overwritten in the product category.  The costing method cannot conflict with the Material Movement Policy (defined on Product Category).*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Costing Level
-------------
\ **Description**\ 
 \ *The lowest level to accumulate Costing Information*\ 
\ **Help**\ 
 \ *If you want to maintain different costs per organization (warehouse) or per Batch/Lot, you need to make sure that you define the costs for each of the organizations or batch/lot. The Costing Level is defined per Accounting Schema and can be overwritten by Product Category and Accounting Schema.*\ 

Adjust COGS
-----------
\ **Description**\ 
 \ *Adjust Cost of Good Sold*\ 
\ **Help**\ 
 \ *For Invoice costing methods, you can adjust the cost of goods sold. At the time of shipment, you may not have received the invoice for the receipt or cost adjustments like freight, customs, etc.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Automatic Period Control
------------------------
\ **Description**\ 
 \ *If selected, the periods are automatically opened and closed*\ 
\ **Help**\ 
 \ *In the Automatic Period Control, periods are opened and closed based on the current date.  If the Manual alternative is activated, you have to open and close periods explicitly.*\ 

Period
------
\ **Description**\ 
 \ *Period of the Calendar*\ 
\ **Help**\ 
 \ *The Period indicates an exclusive range of dates for a calendar.*\ 

History Days
------------
\ **Description**\ 
 \ *Number of days to be able to post in the past (based on system date)*\ 
\ **Help**\ 
 \ *If Automatic Period Control is enabled, the current period is calculated based on the system date and you can always post to all days in the current period.  History Days enable to post to previous periods.  E.g. today is May 15th and History Days is set to 30, you can post back to April 15th*\ 

Future Days
-----------
\ **Description**\ 
 \ *Number of days to be able to post to a future date (based on system date)*\ 
\ **Help**\ 
 \ *If Automatic Period Control is enabled, the current period is calculated based on the system date and you can always post to all days in the current period.  Future Days enable to post to future periods. E.g. today is Apr 15th and Future Days is set to 30, you can post up to May 15th*\ 

Element Separator
-----------------
\ **Description**\ 
 \ *Element Separator*\ 
\ **Help**\ 
 \ *The Element Separator defines the delimiter printed between elements of the structure*\ 

Use Account Alias
-----------------
\ **Description**\ 
 \ *Ability to select (partial) account combinations by an Alias*\ 
\ **Help**\ 
 \ *The Alias checkbox indicates that account combination can be selected using a user defined alias or short key.*\ 

Post Trade Discount
-------------------
\ **Description**\ 
 \ *Generate postings for trade discounts*\ 
\ **Help**\ 
 \ *If the invoice is based on an item with a list price, the amount based on the list price and the discount is posted instead of the net amount.
Example: Quantity 10 - List Price: 20 - Actual Price: 17
If selected for a sales invoice 200 is posted to Product Revenue and 30 to Discount Granted - rather than 170 to Product Revenue.
The same applies to vendor invoices.*\ 

Post Services Separately
------------------------
\ **Description**\ 
 \ *Differentiate between Services and Product Receivable/Payables*\ 
\ **Help**\ 
 \ *If selected, you will post service related revenue to a different receivables account and service related cost to a different payables account.*\ 

Tax Correction
--------------
\ **Description**\ 
 \ *Type of Tax Correction*\ 
\ **Help**\ 
 \ *Determines if/when tax is corrected. Discount could be agreed or granted underpayments; Write-off may be partial or complete write-off.*\ 

Explicit Cost Adjustment
------------------------
\ **Description**\ 
 \ *Post the cost adjustment explicitly*\ 
\ **Help**\ 
 \ *If selected, landed costs are posted to the account in the line and then this posting is reversed by the postings to the cost adjustment accounts.  If not selected, it is directly posted to the cost adjustment accounts.*\ 

Only Organization
-----------------
\ **Description**\ 
 \ *Create posting entries only for this organization*\ 
\ **Help**\ 
 \ *When you have multiple accounting schema, you may want to restrict the generation of postings entries for the additional accounting schema (i.e. not for the primary).  Example: You have a US and a FR organization. The primary accounting schema is in USD, the second in EUR.  If for the EUR accounting schema, you select the FR organizations, you would not create accounting entries for the transactions of the US organization in EUR.*\ 

Allow Negative Posting
----------------------
\ **Description**\ 
 \ *Allow to post negative accounting values*\ 

Create GL/Default
-----------------
\ **Description**\ 
 \ *Copy matching account element values from existing Accounting Schema*\ 
\ **Help**\ 
 \ *Create the GL and Default accounts for this accounting schema and copy matching account element values.*\ 

Post if Clearing Equal
----------------------
\ **Description**\ 
 \ *This flag controls if Adempiere must post when clearing (transit) and final accounts are the same*\ 

Account Schema Element
----------------------
\ **Description**\ 
 \ *Define the elements of your Account Key*\ 
\ **Help**\ 
 \ *The Account Schema Element Tab defines the elements that comprise the account key. A name is defined which will display in documents.  Also the order of the elements and if they are balanced and mandatory are indicated.*\ 

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

Type
----
\ **Description**\ 
 \ *Element Type (account or user defined)*\ 
\ **Help**\ 
 \ *The Element Type indicates if this element is the Account element or is a User Defined element.*\ 

Element
-------
\ **Description**\ 
 \ *Accounting Element*\ 
\ **Help**\ 
 \ *The Account Element uniquely identifies an Account Type.  These are commonly known as a Chart of Accounts.*\ 

Balanced
--------

Mandatory
---------
\ **Description**\ 
 \ *Data entry is required in this column*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Account Element
---------------
\ **Description**\ 
 \ *Account Element*\ 
\ **Help**\ 
 \ *Account Elements can be natural accounts or user defined values.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

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

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

General Ledger
--------------
\ **Description**\ 
 \ *Accounts for GL*\ 
\ **Help**\ 
 \ *The General Ledger Tab defines error and balance handling to use as well as  the necessary accounts for posting to General Ledger.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Use Suspense Balancing
----------------------

Suspense Balancing Acct
-----------------------

Use Suspense Error
------------------

Suspense Error Acct
-------------------

Use Currency Balancing
----------------------

Currency Balancing Acct
-----------------------
\ **Description**\ 
 \ *Account used when a currency is out of balance*\ 
\ **Help**\ 
 \ *The Currency Balancing Account indicates the account to used when a currency is out of balance (generally due to rounding)*\ 

Retained Earning Acct
---------------------

Income Summary Acct
-------------------
\ **Description**\ 
 \ *Income Summary Account*\ 

Intercompany Due To Acct
------------------------
\ **Description**\ 
 \ *Intercompany Due To / Payable Account*\ 
\ **Help**\ 
 \ *The Intercompany Due To Account indicates the account that represents money owed to other organizations.*\ 

Intercompany Due From Acct
--------------------------
\ **Description**\ 
 \ *Intercompany Due From / Receivables Account*\ 
\ **Help**\ 
 \ *The Intercompany Due From account indicates the account that represents money owed to this organization from other organizations.*\ 

PPV Offset
----------
\ **Description**\ 
 \ *Purchase Price Variance Offset Account*\ 
\ **Help**\ 
 \ *Offset account for standard costing purchase price variances. The counter account is Product PPV.*\ 

Commitment Offset
-----------------
\ **Description**\ 
 \ *Budgetary Commitment Offset Account*\ 
\ **Help**\ 
 \ *The Commitment Offset Account is used for posting Commitments and Reservations.  It is usually an off-balance sheet and gain-and-loss account.*\ 

Commitment Offset Sales
-----------------------
\ **Description**\ 
 \ *Budgetary Commitment Offset Account for Sales*\ 
\ **Help**\ 
 \ *The Commitment Offset Account is used for posting Commitments Sales and Reservations.  It is usually an off-balance sheet and gain-and-loss account.*\ 

Defaults
--------
\ **Description**\ 
 \ *Default Accounts*\ 
\ **Help**\ 
 \ *The Defaults Tab displays the Default accounts for an Accounting Schema.  These values will display when a new document is opened.  The user can override these defaults within the document.*\ 

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

Withholding
-----------
\ **Description**\ 
 \ *Account for Withholdings*\ 
\ **Help**\ 
 \ *The Withholding Account indicates the account used to record withholdings.*\ 

Employee Prepayment
-------------------
\ **Description**\ 
 \ *Account for Employee Expense Prepayments*\ 
\ **Help**\ 
 \ *The Employee Prepayment Account identifies the account to use for recording expense advances made to this employee.*\ 

Employee Expense
----------------
\ **Description**\ 
 \ *Account for Employee Expenses*\ 
\ **Help**\ 
 \ *The Employee Expense Account identifies the account to use for recording expenses for this employee.*\ 

Product Asset
-------------
\ **Description**\ 
 \ *Account for Product Asset (Inventory)*\ 
\ **Help**\ 
 \ *The Product Asset Account indicates the account used for valuing this a product in inventory.*\ 

Product Expense
---------------
\ **Description**\ 
 \ *Account for Product Expense*\ 
\ **Help**\ 
 \ *The Product Expense Account indicates the account used to record expenses associated with this product.*\ 

Cost Adjustment
---------------
\ **Description**\ 
 \ *Product Cost Adjustment Account*\ 
\ **Help**\ 
 \ *Account used for posting product cost adjustments (e.g. landed costs)*\ 

Inventory Clearing
------------------
\ **Description**\ 
 \ *Product Inventory Clearing Account*\ 
\ **Help**\ 
 \ *Account used for posting matched product (item) expenses (e.g. AP Invoice, Invoice Match).  You would use a different account then Product Expense, if you want to differentiate service related costs from item related costs. The balance on the clearing account should be zero and accounts for the timing difference between invoice receipt and matching.*\ 

Product Revenue
---------------
\ **Description**\ 
 \ *Account for Product Revenue (Sales Account)*\ 
\ **Help**\ 
 \ *The Product Revenue Account indicates the account used for recording sales revenue for this product.*\ 

Product COGS
------------
\ **Description**\ 
 \ *Account for Cost of Goods Sold*\ 
\ **Help**\ 
 \ *The Product COGS Account indicates the account used when recording costs associated with this product.*\ 

Purchase Price Variance
-----------------------
\ **Description**\ 
 \ *Difference between Standard Cost and Purchase Price (PPV)*\ 
\ **Help**\ 
 \ *The Purchase Price Variance is used in Standard Costing. It reflects the difference between the Standard Cost and the Purchase Order Price.*\ 

Invoice Price Variance
----------------------
\ **Description**\ 
 \ *Difference between Costs and Invoice Price (IPV)*\ 
\ **Help**\ 
 \ *The Invoice Price Variance is used reflects the difference between the current Costs and the Invoice Price.*\ 

Average Cost Variance
---------------------
\ **Description**\ 
 \ *Average Cost Variance*\ 
\ **Help**\ 
 \ *The Average Cost Variance is used in weighted average costing to reflect differences when posting costs for negative inventory.*\ 

Trade Discount Received
-----------------------
\ **Description**\ 
 \ *Trade Discount Receivable Account*\ 
\ **Help**\ 
 \ *The Trade Discount Receivables Account indicates the account for received trade discounts in vendor invoices*\ 

Trade Discount Granted
----------------------
\ **Description**\ 
 \ *Trade Discount Granted Account*\ 
\ **Help**\ 
 \ *The Trade Discount Granted Account indicates the account for granted trade discount in sales invoices*\ 

(Not Used)
----------
\ **Description**\ 
 \ *Warehouse Inventory Asset Account - Currently not used*\ 
\ **Help**\ 
 \ *The Warehouse Inventory Asset Account identifies the account used for recording the value of your inventory. This is the counter account for inventory revaluation differences. The Product Asset account maintains the product asset value.*\ 

Inventory Adjustment
--------------------
\ **Description**\ 
 \ *Account for Inventory value adjustments for Actual Costing*\ 
\ **Help**\ 
 \ *In actual costing systems, this account is used to post Inventory value adjustments. You could set it to the standard Inventory Asset account.*\ 

Warehouse Differences
---------------------
\ **Description**\ 
 \ *Warehouse Differences Account*\ 
\ **Help**\ 
 \ *The Warehouse Differences Account indicates the account used recording differences identified during inventory counts.*\ 

Inventory Revaluation
---------------------
\ **Description**\ 
 \ *Account for Inventory Revaluation*\ 
\ **Help**\ 
 \ *The Inventory Revaluation Account identifies the account used to records changes in inventory value due to currency revaluation.*\ 

Project Asset
-------------
\ **Description**\ 
 \ *Project Asset Account*\ 
\ **Help**\ 
 \ *The Project Asset account is the account used as the final asset account in capital projects*\ 

Work In Progress
----------------
\ **Description**\ 
 \ *Account for Work in Progress*\ 
\ **Help**\ 
 \ *The Work in Process account is the account used in capital projects until the project is completed*\ 

Work In Process
---------------
\ **Description**\ 
 \ *The Work in Process account is the account used Manufacturing Order*\ 

Floor Stock
-----------
\ **Description**\ 
 \ *The Floor Stock account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Floor Stock is used for accounting the component with Issue method  is set Floor stock  into Bill of Material & Formula Window.

The components with Issue Method  defined as Floor stock is acounting next way:

Debit Floor Stock Account
Credit Work in Process Account*\ 

Method Change Variance
----------------------
\ **Description**\ 
 \ *The Method Change Variance account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Method Change Variance is used in Standard Costing. It reflects the difference between the Standard BOM , Standard Manufacturing Workflow and Manufacturing BOM Manufacturing Workflow.

If you change the method the manufacturing defined in BOM or Workflow Manufacturig then this variance is generate.*\ 

Usage Variance
--------------
\ **Description**\ 
 \ *The Usage Variance account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Usage Variance is used in Standard Costing. It reflects the difference between the  Quantities of Standard BOM  or Time Standard Manufacturing Workflow and Quantities of Manufacturing BOM or Time Manufacturing Workflow of Manufacturing Order.

If you change the Quantities or Time  defined in BOM or Workflow Manufacturig then this variance is generate.*\ 

Rate Variance
-------------
\ **Description**\ 
 \ *The Rate Variance account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Rate Variance is used in Standard Costing. It reflects the difference between the Standard Cost Rates and  The Cost Rates of Manufacturing Order.

If you change the Standard Rates then this variance is generate.*\ 

Mix Variance
------------
\ **Description**\ 
 \ *The Mix Variance account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Mix Variance is used when a co-product  received in Inventory  is different the quantity  expected*\ 

Labor
-----
\ **Description**\ 
 \ *The Labor account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Labor is used for accounting the productive Labor*\ 

Burden
------
\ **Description**\ 
 \ *The Burden account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Burden is used for accounting the Burden*\ 

Cost Of Production
------------------
\ **Description**\ 
 \ *The Cost Of Production account is the account used Manufacturing Order*\ 
\ **Help**\ 
 \ *The Cost Of Production is used for accounting Non productive Labor*\ 

Outside Processing
------------------
\ **Description**\ 
 \ *The Outside Processing Account is the account used in Manufacturing Order*\ 
\ **Help**\ 
 \ *The Outside Processing Account is used for accounting the Outside Processing*\ 

Overhead
--------
\ **Description**\ 
 \ *The Overhead account is the account used  in Manufacturing Order*\ 

Scrap
-----
\ **Description**\ 
 \ *The Scrap account is the account used  in Manufacturing Order*\ 

Bank Asset
----------
\ **Description**\ 
 \ *Bank Asset Account*\ 
\ **Help**\ 
 \ *The Bank Asset Account identifies the account to be used for booking changes to the balance in this bank account*\ 

Bank In Transit
---------------
\ **Description**\ 
 \ *Bank In Transit Account*\ 
\ **Help**\ 
 \ *The Bank in Transit Account identifies the account to be used for funds which are in transit.*\ 

Bank Unidentified Receipts
--------------------------
\ **Description**\ 
 \ *Bank Unidentified Receipts Account*\ 
\ **Help**\ 
 \ *The Bank Unidentified Receipts Account identifies the account to be used when recording receipts that can not be reconciled at the present time.*\ 

Unallocated Cash
----------------
\ **Description**\ 
 \ *Unallocated Cash Clearing Account*\ 
\ **Help**\ 
 \ *Receipts not allocated to Invoices*\ 

Payment Selection
-----------------
\ **Description**\ 
 \ *AP Payment Selection Clearing Account*\ 

Bank Expense
------------
\ **Description**\ 
 \ *Bank Expense Account*\ 
\ **Help**\ 
 \ *The Bank Expense Account identifies the account to be used for recording charges or fees incurred from this Bank.*\ 

Bank Interest Expense
---------------------
\ **Description**\ 
 \ *Bank Interest Expense Account*\ 
\ **Help**\ 
 \ *The Bank Interest Expense Account identifies the account to be used for recording interest expenses.*\ 

Bank Interest Revenue
---------------------
\ **Description**\ 
 \ *Bank Interest Revenue Account*\ 
\ **Help**\ 
 \ *The Bank Interest Revenue Account identifies the account to be used for recording interest revenue from this Bank.*\ 

Bank Revaluation Gain
---------------------
\ **Description**\ 
 \ *Bank Revaluation Gain Account*\ 
\ **Help**\ 
 \ *The Bank Revaluation Gain Account identifies the account to be used for recording gains that are recognized when converting currencies.*\ 

Bank Revaluation Loss
---------------------
\ **Description**\ 
 \ *Bank Revaluation Loss Account*\ 
\ **Help**\ 
 \ *The Bank Revaluation Loss Account identifies the account to be used for recording losses that are recognized when converting currencies.*\ 

Bank Settlement Loss
--------------------
\ **Description**\ 
 \ *Bank Settlement Loss Account*\ 
\ **Help**\ 
 \ *The Bank Settlement loss account identifies the account to be used when recording a currency loss when the settlement and receipt currency are not the same.*\ 

Bank Settlement Gain
--------------------
\ **Description**\ 
 \ *Bank Settlement Gain Account*\ 
\ **Help**\ 
 \ *The Bank Settlement Gain account identifies the account to be used when recording a currency gain when the settlement and receipt currency are not the same.*\ 

Tax Due
-------
\ **Description**\ 
 \ *Account for Tax you have to pay*\ 
\ **Help**\ 
 \ *The Tax Due Account indicates the account used to record taxes that you are liable to pay.*\ 

Tax Liability
-------------
\ **Description**\ 
 \ *Account for Tax declaration liability*\ 
\ **Help**\ 
 \ *The Tax Liability Account indicates the account used to record your tax liability declaration.*\ 

Tax Credit
----------
\ **Description**\ 
 \ *Account for Tax you can reclaim*\ 
\ **Help**\ 
 \ *The Tax Credit Account indicates the account used to record taxes that can be reclaimed*\ 

Tax Receivables
---------------
\ **Description**\ 
 \ *Account for Tax credit after tax declaration*\ 
\ **Help**\ 
 \ *The Tax Receivables Account indicates the account used to record the tax credit amount after your tax declaration.*\ 

Tax Expense
-----------
\ **Description**\ 
 \ *Account for paid tax you cannot reclaim*\ 
\ **Help**\ 
 \ *The Tax Expense Account indicates the account used to record the taxes that have been paid that cannot be reclaimed.*\ 

Charge Expense
--------------
\ **Description**\ 
 \ *Charge Expense Account*\ 
\ **Help**\ 
 \ *The Charge Expense Account identifies the account to use when recording charges paid to vendors.*\ 

Charge Revenue
--------------
\ **Description**\ 
 \ *Charge Revenue Account*\ 
\ **Help**\ 
 \ *The Charge Revenue Account identifies the account to use when recording charges paid by customers.*\ 

Unrealized Gain Acct
--------------------
\ **Description**\ 
 \ *Unrealized Gain Account for currency revaluation*\ 
\ **Help**\ 
 \ *The Unrealized Gain Account indicates the account to be used when recording gains achieved from currency revaluation that have yet to be realized.*\ 

Unrealized Loss Acct
--------------------
\ **Description**\ 
 \ *Unrealized Loss Account for currency revaluation*\ 
\ **Help**\ 
 \ *The Unrealized Loss Account indicates the account to be used when recording losses incurred from currency revaluation that have yet to be realized.*\ 

Realized Gain Acct
------------------
\ **Description**\ 
 \ *Realized Gain Account*\ 
\ **Help**\ 
 \ *The Realized Gain Account indicates the account to be used when recording gains achieved from currency revaluation that have been realized.*\ 

Realized Loss Acct
------------------
\ **Description**\ 
 \ *Realized Loss Account*\ 
\ **Help**\ 
 \ *The Realized Loss Account indicates the account to be used when recording losses incurred from currency revaluation that have yet to be realized.*\ 

Cash Book Asset
---------------
\ **Description**\ 
 \ *Cash Book Asset Account*\ 
\ **Help**\ 
 \ *The Cash Book Asset Account identifies the account to be used for recording payments into and disbursements from this cash book.*\ 

Cash Book Differences
---------------------
\ **Description**\ 
 \ *Cash Book Differences Account*\ 
\ **Help**\ 
 \ *The Cash Book Differences Account identifies the account to be used for recording any differences that affect this cash book*\ 

Cash Transfer
-------------
\ **Description**\ 
 \ *Cash Transfer Clearing Account*\ 
\ **Help**\ 
 \ *Account for Invoices paid by cash*\ 

Cash Book Expense
-----------------
\ **Description**\ 
 \ *Cash Book Expense Account*\ 
\ **Help**\ 
 \ *The Cash Book Expense Account identifies the account to be used for general, non itemized expenses.*\ 

Cash Book Receipt
-----------------
\ **Description**\ 
 \ *Cash Book Receipts Account*\ 
\ **Help**\ 
 \ *The Cash Book Receipt Account identifies the account to be used for general, non itemized cash book receipts.*\ 

Add or Copy Accounts
--------------------
\ **Description**\ 
 \ *Add missing Accounts - or Copy&Overwrite Accounts (DANGEROUS!!)*\ 
\ **Help**\ 
 \ *Either add missing accounts - or copy and overwrite all default accounts.  If you copy and overwrite the current default values, you may have to repeat previous updates (e.g. set the bank account asset accounts, ...).  If no Accounting Schema is selected all Accounting Schemas will be updated / inserted.*\ 
