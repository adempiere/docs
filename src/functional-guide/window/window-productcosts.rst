
.. _functional-guide/window/window-productcosts:

=============
Product Costs
=============

Maintain Product Costs

Help
====
Maintain Product Cost Elements

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Select Product
--------------
\ **Description**\ 
 \ *Select the product*\ 

.. note::
    The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Product Type
------------
\ **Description**\ 
 \ *Type of product*\ 
\ **Help**\ 
 \ *The type of product also determines accounting consequences.*\ 

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

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Stocked
-------
\ **Description**\ 
 \ *Organization stocks this product*\ 
\ **Help**\ 
 \ *The Stocked check box indicates if this product is stocked by this Organization.*\ 

Company Agent
-------------
\ **Description**\ 
 \ *Purchase or Company Agent*\ 
\ **Help**\ 
 \ *Purchase agent for the document. Any Sales Rep must be a valid internal user.*\ 

Cost Dimensions
---------------
\ **Description**\ 
 \ *Maintain Cost Dimensions*\ 

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

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 

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

Costing Method
--------------
\ **Description**\ 
 \ *Indicates how Costs will be calculated*\ 
\ **Help**\ 
 \ *The Costing Method indicates how costs will be calculated (Standard, Average, Lifo, FiFo).  The default costing method is defined on accounting schema level and can be optionally overwritten in the product category.  The costing method cannot conflict with the Material Movement Policy (defined on Product Category).*\ 

Current Cost Price
------------------
\ **Description**\ 
 \ *The currently used cost price*\ 

Current Cost Price LL
---------------------
\ **Description**\ 
 \ *Current Price Lower Level Is the sum of the costs of the components of this product manufactured for this level.*\ 
\ **Help**\ 
 \ *Current Price Lower Level is used for get the total costs for lower level the a product manufactured.

The Current Price Lower Level always will be calculated.

You can see the Current Cost Price and Current Cost Price Lower Level with Cost  Bill of Material & Formula Detail Report.
 
The sum the Current Cost Price + Current Cost Price Lower Level is the total cost to a product manufactured.*\ 

Percent
-------
\ **Description**\ 
 \ *Percentage*\ 
\ **Help**\ 
 \ *The Percent indicates the percentage used.*\ 

Current Quantity
----------------
\ **Description**\ 
 \ *Current Quantity*\ 

Accumulated Qty
---------------
\ **Description**\ 
 \ *Total Quantity*\ 
\ **Help**\ 
 \ *Sum of the quantities*\ 

Accumulated Amt
---------------
\ **Description**\ 
 \ *Total Amount*\ 
\ **Help**\ 
 \ *Sum of all amounts*\ 

Accumulated Amt LL
------------------
\ **Description**\ 
 \ *Total Amount*\ 
\ **Help**\ 
 \ *Sum of all amounts*\ 

Future Cost Price
-----------------

Future Cost Price LL
--------------------

Cost Frozen
-----------
\ **Description**\ 
 \ *Indicated that the Standard Cost is frozen*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Cost Details
------------
\ **Description**\ 
 \ *View Product Cost Details*\ 

.. note::
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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

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

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Reversal
--------
\ **Description**\ 
 \ *This is a reversing transaction*\ 
\ **Help**\ 
 \ *The Reversal check box indicates if this is a reversal of a prior transaction.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Current Quantity
----------------
\ **Description**\ 
 \ *Current Quantity*\ 

Price
-----
\ **Description**\ 
 \ *Price*\ 
\ **Help**\ 
 \ *The Price indicates the Price for a product or service.*\ 

Amount
------
\ **Description**\ 
 \ *Amount*\ 
\ **Help**\ 
 \ *Amount*\ 

Amount LL
---------
\ **Description**\ 
 \ *Amount Lower Level Cost*\ 
\ **Help**\ 
 \ *Amount Lower Level Cost*\ 

Current Cost Price
------------------
\ **Description**\ 
 \ *The currently used cost price*\ 

Current Cost Price LL
---------------------
\ **Description**\ 
 \ *Current Price Lower Level Is the sum of the costs of the components of this product manufactured for this level.*\ 
\ **Help**\ 
 \ *Current Price Lower Level is used for get the total costs for lower level the a product manufactured.

The Current Price Lower Level always will be calculated.

You can see the Current Cost Price and Current Cost Price Lower Level with Cost  Bill of Material & Formula Detail Report.
 
The sum the Current Cost Price + Current Cost Price Lower Level is the total cost to a product manufactured.*\ 

Delta Quantity
--------------
\ **Description**\ 
 \ *Quantity Difference*\ 

Delta Amount
------------
\ **Description**\ 
 \ *Difference Amount*\ 

Accumulated Qty
---------------
\ **Description**\ 
 \ *Total Quantity*\ 
\ **Help**\ 
 \ *Sum of the quantities*\ 

Accumulated Amt
---------------
\ **Description**\ 
 \ *Total Amount*\ 
\ **Help**\ 
 \ *Sum of all amounts*\ 

Accumulated Amt LL
------------------
\ **Description**\ 
 \ *Total Amount*\ 
\ **Help**\ 
 \ *Sum of all amounts*\ 

Cost Value
----------
\ **Description**\ 
 \ *Value with Cost*\ 

Cost Value LL
-------------
\ **Description**\ 
 \ *Value with Cost Lower Level*\ 

Cost Adjustment
---------------
\ **Description**\ 
 \ *Product Cost Adjustment*\ 
\ **Help**\ 
 \ *product cost adjustments*\ 

Cost Adjustment LL
------------------
\ **Description**\ 
 \ *Product Cost Adjustment Lower Level*\ 
\ **Help**\ 
 \ *product cost adjustments*\ 

Cost Adjustment Date
--------------------
\ **Description**\ 
 \ *Product Cost Adjustment*\ 
\ **Help**\ 
 \ *product cost adjustments*\ 

Cost Adjustment Date
--------------------
\ **Description**\ 
 \ *Date Product Cost Adjustment Lower Level*\ 
\ **Help**\ 
 \ *Date product cost adjustments Lower Level*\ 

Purchase Order Line
-------------------
\ **Description**\ 
 \ *Purchase Order Line*\ 
\ **Help**\ 
 \ *The Purchase Order Line is a unique identifier for a line in an order.*\ 

Invoice Line
------------
\ **Description**\ 
 \ *Invoice Detail Line*\ 
\ **Help**\ 
 \ *The Invoice Line uniquely identifies a single line of an Invoice.*\ 

Receipt Line
------------
\ **Description**\ 
 \ *Line on Receipt document*\ 

Move Line
---------
\ **Description**\ 
 \ *Inventory Move document Line*\ 
\ **Help**\ 
 \ *The Movement Line indicates the inventory movement document line (if applicable) for this transaction*\ 

Phys.Inventory Line
-------------------
\ **Description**\ 
 \ *Unique line in an Inventory document*\ 
\ **Help**\ 
 \ *The Physical Inventory Line indicates the inventory document line (if applicable) for this transaction*\ 

Project Issue
-------------
\ **Description**\ 
 \ *Project Issues (Material, Labor)*\ 
\ **Help**\ 
 \ *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*\ 

Production Line
---------------
\ **Description**\ 
 \ *Document Line representing a production*\ 
\ **Help**\ 
 \ *The Production Line indicates the production document line (if applicable) for this transaction*\ 

Landed Cost Allocation
----------------------
\ **Description**\ 
 \ *Allocation for Land Costs*\ 

Manufacturing Cost Collector
----------------------------

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Cost Queue
----------
\ **Description**\ 
 \ *Cost Queue for Lifo/Fifo*\ 
\ **Help**\ 
 \ *Note thet the cost queue may not be the same as the physical movement cost queue due to differences in costing level and warehouse priority.*\ 

.. note::
    The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Current Cost Price
------------------
\ **Description**\ 
 \ *The currently used cost price*\ 

Current Quantity
----------------
\ **Description**\ 
 \ *Current Quantity*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Costing (old)
-------------
\ **Description**\ 
 \ *Old Product Costing Info*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Current Cost Price
------------------
\ **Description**\ 
 \ *The currently used cost price*\ 

Average Cost
------------
\ **Description**\ 
 \ *Weighted average costs*\ 
\ **Help**\ 
 \ *Weighted average (actual) costs*\ 

Average Cost Amount Sum
-----------------------
\ **Description**\ 
 \ *Cumulative average cost amounts (internal)*\ 
\ **Help**\ 
 \ *Current cumulative costs for calculating the average costs*\ 

Average Cost Quantity Sum
-------------------------
\ **Description**\ 
 \ *Cumulative average cost quantities (internal)*\ 
\ **Help**\ 
 \ *Current cumulative quantity for calculating the average costs*\ 

Standard Cost
-------------
\ **Description**\ 
 \ *Standard Costs*\ 
\ **Help**\ 
 \ *Standard (plan) costs.*\ 

Future Cost Price
-----------------

Std PO Cost Amount Sum
----------------------
\ **Description**\ 
 \ *Standard Cost Purchase Order Amount Sum (internal)*\ 
\ **Help**\ 
 \ *Current cumulative amount for calculating the standard cost difference based on (planned) purchase order price*\ 

Std PO Cost Quantity Sum
------------------------
\ **Description**\ 
 \ *Standard Cost Purchase Order Quantity Sum (internal)*\ 
\ **Help**\ 
 \ *Current cumulative quantity for calculating the standard cost difference based on (planned) purchase order price*\ 

Std Cost Amount Sum
-------------------
\ **Description**\ 
 \ *Standard Cost Invoice Amount Sum (internal)*\ 
\ **Help**\ 
 \ *Current cumulative amount for calculating the standard cost difference based on (actual) invoice price*\ 

Std Cost Quantity Sum
---------------------
\ **Description**\ 
 \ *Standard Cost Invoice Quantity Sum (internal)*\ 
\ **Help**\ 
 \ *Current cumulative quantity for calculating the standard cost difference based on (actual) invoice price*\ 

Last PO Price
-------------
\ **Description**\ 
 \ *Price of the last purchase order for the product*\ 
\ **Help**\ 
 \ *The Last PO Price indicates the last price paid (per the purchase order) for this product.*\ 

Last Invoice Price
------------------
\ **Description**\ 
 \ *Price of the last invoice for the product*\ 
\ **Help**\ 
 \ *The Last Invoice Price indicates the last price paid (per the invoice) for this product.*\ 

Total Invoice Amount
--------------------
\ **Description**\ 
 \ *Cumulative total lifetime invoice amount*\ 
\ **Help**\ 
 \ *The cumulative total lifetime invoice amount is used to calculate the total average price*\ 

Total Invoice Quantity
----------------------
\ **Description**\ 
 \ *Cumulative total lifetime invoice quantity*\ 
\ **Help**\ 
 \ *The cumulative total lifetime invoice quantity is used to calculate the total average price*\ 
