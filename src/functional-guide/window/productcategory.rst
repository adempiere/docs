
.. _functional-guide/window/productcategory:

================
Product Category
================

Maintain Product Categories

Help
====
The Product Category allows you to define different groups of products.  These groups can be used in generating Price Lists, defining margins and for easily assigning different accounting parameters for products.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Product Category
----------------
\ **Description**\ 
 \ *Define Product Category*\ 
\ **Help**\ 
 \ *The Product Category defines unique groupings of products.  Product categories can be used in building price lists.*\ 

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

Parent Product Category
-----------------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Material Policy
---------------
\ **Description**\ 
 \ *Material Movement Policy*\ 
\ **Help**\ 
 \ *The Material Movement Policy determines how the stock is flowing (FiFo or LiFo) if a specific Product Instance was not selected.  The policy can not contradict the costing method (e.g. FiFo movement policy and LiFo costing method).*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Planned Margin %
----------------
\ **Description**\ 
 \ *Project's planned margin as a percentage*\ 
\ **Help**\ 
 \ *The Planned Margin Percentage indicates the anticipated margin percentage for this project or project line*\ 

Asset Group
-----------
\ **Description**\ 
 \ *Group of Assets*\ 
\ **Help**\ 
 \ *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*\ 

Print Color
-----------
\ **Description**\ 
 \ *Color used for printing and display*\ 
\ **Help**\ 
 \ *Colors used for printing and display*\ 

Accounting
----------
\ **Description**\ 
 \ *Accounting Parameters*\ 
\ **Help**\ 
 \ *The Accounting Tab defines default accounting parameters.  Any product that uses a product category can inherit its default accounting parameters.  If the Costing method is not defined, the default costing method of the accounting schema is used.*\ 

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

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

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

Costing Method
--------------
\ **Description**\ 
 \ *Indicates how Costs will be calculated*\ 
\ **Help**\ 
 \ *The Costing Method indicates how costs will be calculated (Standard, Average, Lifo, FiFo).  The default costing method is defined on accounting schema level and can be optionally overwritten in the product category.  The costing method cannot conflict with the Material Movement Policy (defined on Product Category).*\ 

Costing Level
-------------
\ **Description**\ 
 \ *The lowest level to accumulate Costing Information*\ 
\ **Help**\ 
 \ *If you want to maintain different costs per organization (warehouse) or per Batch/Lot, you need to make sure that you define the costs for each of the organizations or batch/lot. The Costing Level is defined per Accounting Schema and can be overwritten by Product Category and Accounting Schema.*\ 

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

Product Revenue
---------------
\ **Description**\ 
 \ *Account for Product Revenue (Sales Account)*\ 
\ **Help**\ 
 \ *The Product Revenue Account indicates the account used for recording sales revenue for this product.*\ 

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

Copy Accounts
-------------
\ **Description**\ 
 \ *Copy and overwrite Accounts to Products of this category*\ 
\ **Help**\ 
 \ *If you copy and overwrite the current default values, you may have to repeat previous updates (e.g. set the revenue account, ...). If no Accounting Schema is selected all Accounting Schemas will be updated / inserted for products of this category.*\ 

Assigned Products
-----------------
\ **Description**\ 
 \ *Products assigned to Product Category*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

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

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Discontinued
------------
\ **Description**\ 
 \ *This product is no longer available*\ 
\ **Help**\ 
 \ *The Discontinued check box indicates a product that has been discontinued.*\ 

Product Type
------------
\ **Description**\ 
 \ *Type of product*\ 
\ **Help**\ 
 \ *The type of product also determines accounting consequences.*\ 

Expense Type
------------
\ **Description**\ 
 \ *Expense report type*\ 

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Featured in Web Store
---------------------
\ **Description**\ 
 \ *If selected, the product is displayed in the initial or any empty search*\ 
\ **Help**\ 
 \ *In the display of products in the Web Store, the product is displayed in the initial view or if no search criteria are entered. To be displayed, the product must be in the price list used.*\ 
