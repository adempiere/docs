
.. _functional-guide/window/resource:

========
Resource
========

Maintain Resources

Help
====
Maintain your Resources. The product for the resource is automatically created and synchronized. Update Name, Unit of Measure, etc. in the Resource and don't change it in the product.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Resource
--------
\ **Description**\ 
 \ *Maintain Resources*\ 

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

Resource Type
-------------

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Available
---------
\ **Description**\ 
 \ *Resource is available*\ 
\ **Help**\ 
 \ *Resource is available for assignments*\ 

Unavailability
--------------
\ **Description**\ 
 \ *Resource unavailability*\ 
\ **Help**\ 
 \ *Dates, when the resource is not available (e.g. vacation)*\ 

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

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Date From
---------
\ **Description**\ 
 \ *Starting date for a range*\ 
\ **Help**\ 
 \ *The Date From indicates the starting date of a range.*\ 

Date To
-------
\ **Description**\ 
 \ *End date of a date range*\ 
\ **Help**\ 
 \ *The Date To indicates the end date of a range (inclusive)*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Resource Product
----------------
\ **Description**\ 
 \ *Maintain Product information of Resource*\ 
\ **Help**\ 
 \ *The product for the resource is automatically created and synchronized. Update Name, Unit of Measure, etc. in the Resource and don't change it in the product.*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Document Note
-------------
\ **Description**\ 
 \ *Additional information for a Document*\ 
\ **Help**\ 
 \ *The Document Note is used for recording any additional information regarding this product.*\ 

UPC/EAN
-------
\ **Description**\ 
 \ *Bar Code (Universal Product Code or its superset European Article Number)*\ 
\ **Help**\ 
 \ *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*\ 

SKU
---
\ **Description**\ 
 \ *Stock Keeping Unit*\ 
\ **Help**\ 
 \ *The SKU indicates a user defined stock keeping unit.  It may be used for an additional bar code symbols or your own schema.*\ 

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

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Classification
--------------
\ **Description**\ 
 \ *Classification for grouping*\ 
\ **Help**\ 
 \ *The Classification can be used to optionally group products.*\ 

Tax Category
------------
\ **Description**\ 
 \ *Tax Category*\ 
\ **Help**\ 
 \ *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*\ 

Tax Type
--------
\ **Description**\ 
 \ *Tax Type*\ 

Revenue Recognition
-------------------
\ **Description**\ 
 \ *Method for recording revenue*\ 
\ **Help**\ 
 \ *The Revenue Recognition indicates how revenue will be recognized for this product*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Product Type
------------
\ **Description**\ 
 \ *Type of product*\ 
\ **Help**\ 
 \ *The type of product also determines accounting consequences.*\ 

Purchased
---------
\ **Description**\ 
 \ *Organization purchases this product*\ 
\ **Help**\ 
 \ *The Purchased check box indicates if this product is purchased by this organization.*\ 

Sold
----
\ **Description**\ 
 \ *Organization sells this product*\ 
\ **Help**\ 
 \ *The Sold check box indicates if this product is sold by this organization.*\ 

Discontinued
------------
\ **Description**\ 
 \ *This product is no longer available*\ 
\ **Help**\ 
 \ *The Discontinued check box indicates a product that has been discontinued.*\ 

Discontinued At
---------------
\ **Description**\ 
 \ *Discontinued At indicates Date when product was discontinued*\ 

Image URL
---------
\ **Description**\ 
 \ *URL of  image*\ 
\ **Help**\ 
 \ *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*\ 

Description URL
---------------
\ **Description**\ 
 \ *URL for the description*\ 

Price
-----
\ **Description**\ 
 \ *Resource Pricing*\ 
\ **Help**\ 
 \ *The Pricing Tab displays the List, Standard and Limit prices for each price list a resource is contained in.*\ 

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

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Accounting
----------
\ **Description**\ 
 \ *Define Accounting Parameters*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the defaults to use when generating accounting transactions for orders and invoices which contain this resource.  Not all accounts apply to resources.*\ 

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

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Assignment
----------
\ **Description**\ 
 \ *Resource Assignments*\ 
\ **Help**\ 
 \ *History of Assignments*\ 

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

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Assign From
-----------
\ **Description**\ 
 \ *Assign resource from*\ 
\ **Help**\ 
 \ *Assignment start*\ 

Assign To
---------
\ **Description**\ 
 \ *Assign resource until*\ 
\ **Help**\ 
 \ *Assignment end*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Confirmed
---------
\ **Description**\ 
 \ *Assignment is confirmed*\ 
\ **Help**\ 
 \ *Resource assignment is confirmed*\ 

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
