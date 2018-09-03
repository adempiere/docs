
.. _window-warehouselocators:

====================
Warehouse & Locators
====================

Maintain Warehouses and Locators

Help
====
The Warehouse and Locators Window defines each Warehouse, any Locators for that Warehouse and the Accounting parameters to be used for inventory in that Warehouse.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Warehouse
---------
\ **Description**\ 
 \ *Warehouse*\ 
\ **Help**\ 
 \ *The Warehouse Tab defines each Warehouse that is used to store products.  If a Source warehouse is selected, all product replenishment is from that warehouse.  If you use custom replenishment algorithms, you need to define the class used per warehouse.*\ 

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

In Transit
----------
\ **Description**\ 
 \ *Movement is in transit*\ 
\ **Help**\ 
 \ *Material Movement is in transit - shipped, but not received.
The transaction is completed, if confirmed.*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Element Separator
-----------------
\ **Description**\ 
 \ *Element Separator*\ 
\ **Help**\ 
 \ *The Element Separator defines the delimiter printed between elements of the structure*\ 

Source Warehouse
----------------
\ **Description**\ 
 \ *Optional Warehouse to replenish from*\ 
\ **Help**\ 
 \ *If defined, the warehouse selected is used to replenish the product(s)*\ 

Replenishment Class
-------------------
\ **Description**\ 
 \ *Custom class to calculate Quantity to Order*\ 
\ **Help**\ 
 \ *If you select a custom replenishment type, you need to create a class implementing org.compiere.util.ReplenishInterface and set that on warehouse level.*\ 

Locator
-------
\ **Description**\ 
 \ *Locator*\ 
\ **Help**\ 
 \ *The Locator Tab defines any Locators for that Warehouse.*\ 

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Relative Priority
-----------------
\ **Description**\ 
 \ *Where inventory should be picked from first*\ 
\ **Help**\ 
 \ *The Relative Priority indicates the location to pick from first if an product is stored in more than one location.  (100 = highest priority, 0 = lowest).  For outgoing shipments, the location is picked with the highest priority where the entire quantity can be shipped from.  If there is no location, the location with the highest priority is used.
The Priority is ignored for products with Guarantee Date (always the oldest first) or if a specific instance is selected.
Incoming receipts are stored at the location with the highest priority, if not explicitly selected.*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Aisle (X)
---------
\ **Description**\ 
 \ *X dimension, e.g., Aisle*\ 
\ **Help**\ 
 \ *The X dimension indicates the Aisle a product is located in.*\ 

Bin (Y)
-------
\ **Description**\ 
 \ *Y dimension, e.g., Bin*\ 
\ **Help**\ 
 \ *The Y dimension indicates the Bin a product is located in*\ 

Level (Z)
---------
\ **Description**\ 
 \ *Z dimension, e.g., Level*\ 
\ **Help**\ 
 \ *The Z dimension indicates the Level a product is located in.*\ 

Storage
-------
\ **Description**\ 
 \ *Detail Storage Information*\ 

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

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

On Hand Quantity
----------------
\ **Description**\ 
 \ *On Hand Quantity*\ 
\ **Help**\ 
 \ *The On Hand Quantity indicates the quantity of a product that is on hand in a warehouse.*\ 

Date last inventory count
-------------------------
\ **Description**\ 
 \ *Date of Last Inventory Count*\ 
\ **Help**\ 
 \ *The Date Last Inventory Count indicates the last time an Inventory count was done.*\ 

Reserved Quantity
-----------------
\ **Description**\ 
 \ *Reserved Quantity*\ 
\ **Help**\ 
 \ *The Reserved Quantity indicates the quantity of a product that is currently reserved.*\ 

Ordered Quantity
----------------
\ **Description**\ 
 \ *Ordered Quantity*\ 
\ **Help**\ 
 \ *The Ordered Quantity indicates the quantity of a product that was ordered.*\ 

Replenish
---------
\ **Description**\ 
 \ *Define Product Replenishment*\ 
\ **Help**\ 
 \ *The Replenishment Tab defines the type of replenishment quantities.  This is used for automated ordering.  If you select a custom replenishment type, you need to create a class implementing org.compiere.util.ReplenishInterface and set that on warehouse level.*\ 

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

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

Replenish Type
--------------
\ **Description**\ 
 \ *Method for re-ordering a product*\ 
\ **Help**\ 
 \ *The Replenish Type indicates if this product will be manually re-ordered, ordered when the quantity is below the minimum quantity or ordered when it is below the maximum quantity. If you select a custom replenishment type, you need to create a class implementing org.compiere.util.ReplenishInterface and set that on warehouse level.*\ 

Minimum Level
-------------
\ **Description**\ 
 \ *Minimum Inventory level for this product*\ 
\ **Help**\ 
 \ *Indicates the minimum quantity of this product to be stocked in inventory.*\ 

Maximum Level
-------------
\ **Description**\ 
 \ *Maximum Inventory level for this product*\ 
\ **Help**\ 
 \ *Indicates the maximum quantity of this product to be stocked in inventory.*\ 

Source Warehouse
----------------
\ **Description**\ 
 \ *Optional Warehouse to replenish from*\ 
\ **Help**\ 
 \ *If defined, the warehouse selected is used to replenish the product(s)*\ 

Accounting
----------
\ **Description**\ 
 \ *Accounting*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the Accounting parameters to be used for inventory in that Warehouse.*\ 

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

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

Product Transactions
--------------------
\ **Description**\ 
 \ *Transactions for stored Products*\ 

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

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Movement Quantity
-----------------
\ **Description**\ 
 \ *Quantity of a product moved.*\ 
\ **Help**\ 
 \ *The Movement Quantity indicates the quantity of a product that has been moved.*\ 

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

Movement Type
-------------
\ **Description**\ 
 \ *Method of moving the inventory*\ 
\ **Help**\ 
 \ *The Movement Type indicates the type of movement (in, out, to production, etc)*\ 

Shipment/Receipt Line
---------------------
\ **Description**\ 
 \ *Line on Shipment or Receipt document*\ 
\ **Help**\ 
 \ *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*\ 

Phys.Inventory Line
-------------------
\ **Description**\ 
 \ *Unique line in an Inventory document*\ 
\ **Help**\ 
 \ *The Physical Inventory Line indicates the inventory document line (if applicable) for this transaction*\ 

Move Line
---------
\ **Description**\ 
 \ *Inventory Move document Line*\ 
\ **Help**\ 
 \ *The Movement Line indicates the inventory movement document line (if applicable) for this transaction*\ 

Production Line
---------------
\ **Description**\ 
 \ *Document Line representing a production*\ 
\ **Help**\ 
 \ *The Production Line indicates the production document line (if applicable) for this transaction*\ 

Project Issue
-------------
\ **Description**\ 
 \ *Project Issues (Material, Labor)*\ 
\ **Help**\ 
 \ *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*\ 
