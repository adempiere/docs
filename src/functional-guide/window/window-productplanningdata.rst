
.. _functional-guide/window/window-productplanningdata:

=====================
Product Planning Data
=====================

Maintain Product Planning Data

Help
====
in the Window Product Planning Data you enter the product information which will serve as a base to execute the algorithms of Material Requirement Planning, along with MPS, open orders and inventories

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Product
-------

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

Version No
----------
\ **Description**\ 
 \ *Version Number*\ 

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

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

Weight
------
\ **Description**\ 
 \ *Weight of a product*\ 
\ **Help**\ 
 \ *The Weight indicates the weight  of the product in the Weight UOM of the Client*\ 

Volume
------
\ **Description**\ 
 \ *Volume of a product*\ 
\ **Help**\ 
 \ *The Volume indicates the volume of the product in the Volume UOM of the Client*\ 

Freight Category
----------------
\ **Description**\ 
 \ *Category of the Freight*\ 
\ **Help**\ 
 \ *Freight Categories are used to calculate the Freight for the Shipper selected*\ 

Drop Shipment
-------------
\ **Description**\ 
 \ *Drop Shipments are sent from the Vendor directly to the Customer*\ 
\ **Help**\ 
 \ *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*\ 

Stocked
-------
\ **Description**\ 
 \ *Organization stocks this product*\ 
\ **Help**\ 
 \ *The Stocked check box indicates if this product is stocked by this Organization.*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Shelf Width
-----------
\ **Description**\ 
 \ *Shelf width required*\ 
\ **Help**\ 
 \ *The Shelf Width indicates the width dimension required on a shelf for a product*\ 

Shelf Height
------------
\ **Description**\ 
 \ *Shelf height required*\ 
\ **Help**\ 
 \ *The Shelf Height indicates the height dimension required on a shelf for a product*\ 

Shelf Depth
-----------
\ **Description**\ 
 \ *Shelf depth required*\ 
\ **Help**\ 
 \ *The Shelf Depth indicates the depth dimension required on a shelf for a product*\ 

Units Per Pallet
----------------
\ **Description**\ 
 \ *Units Per Pallet*\ 
\ **Help**\ 
 \ *The Units per Pallet indicates the number of units of this product which fit on a pallet.*\ 

Bill of Materials
-----------------
\ **Description**\ 
 \ *Bill of Materials*\ 
\ **Help**\ 
 \ *The Bill of Materials check box indicates if this product consists of a bill of materials.*\ 

Verified
--------
\ **Description**\ 
 \ *The BOM configuration has been verified*\ 
\ **Help**\ 
 \ *The Verified check box indicates if the configuration of this product has been verified.  This is used for products that consist of a bill of materials*\ 

Verify BOM
----------
\ **Description**\ 
 \ *Verify BOM Structure and Update Low Level*\ 
\ **Help**\ 
 \ *The Verify BOM Structure checks the elements and steps which comprise a Bill of Materials.*\ 

Print detail records on invoice
-------------------------------
\ **Description**\ 
 \ *Print detail BOM elements on the invoice*\ 
\ **Help**\ 
 \ *The Print Details on Invoice indicates that the BOM element products will print on the Invoice as opposed to this product.*\ 

Print detail records on pick list
---------------------------------
\ **Description**\ 
 \ *Print detail BOM elements on the pick list*\ 
\ **Help**\ 
 \ *The Print Details on Pick List indicates that the BOM element products will print on the Pick List as opposed to this product.*\ 

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

Expense Type
------------
\ **Description**\ 
 \ *Expense report type*\ 

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

Subscription Type
-----------------
\ **Description**\ 
 \ *Type of subscription*\ 
\ **Help**\ 
 \ *Subscription type and renewal frequency*\ 

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

Guarantee Days
--------------
\ **Description**\ 
 \ *Number of days the product is guaranteed or available*\ 
\ **Help**\ 
 \ *If the value is 0, there is no limit to the availability or guarantee, otherwise the guarantee date is calculated by adding the days to the delivery date.*\ 

Min Guarantee Days
------------------
\ **Description**\ 
 \ *Minimum number of guarantee days*\ 
\ **Help**\ 
 \ *When selecting batch/products with a guarantee date, the minimum left guarantee days for automatic picking.  You can pick any batch/product manually.*\ 

Attribute Set
-------------
\ **Description**\ 
 \ *Product Attribute Set*\ 
\ **Help**\ 
 \ *Define Product Attribute Sets to add additional attributes and values to the product. You need to define a Attribute Set if you want to enable Serial and Lot Number tracking.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Featured in Web Store
---------------------
\ **Description**\ 
 \ *If selected, the product is displayed in the initial or any empty search*\ 
\ **Help**\ 
 \ *In the display of products in the Web Store, the product is displayed in the initial view or if no search criteria are entered. To be displayed, the product must be in the price list used.*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Data Planning
-------------

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

Resource
--------
\ **Description**\ 
 \ *Resource*\ 
\ **Help**\ 
 \ *A manufacturing resource is a place where a product will be made.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.

Warehouse place where you locate and control the products*\ 

Planner
-------
\ **Description**\ 
 \ *Company Agent for Planning*\ 
\ **Help**\ 
 \ *The Master Planner indicates the company agent in charge of the MPS management. Any Master Planner must be a valid internal user.*\ 

BOM & Formula
-------------
\ **Help**\ 
 \ *The name BOM/Formula that you introduce in this window will be considered the default BOM to produce the product in this Organization-Plant-Warehouse. If you do not fill this field the default BOM & Formula for the entity will be the BOM/Formula which has the same name as the product.*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.

The Workflow you introduce in this window will be considered the default Workflow to produce the product in this Organization-Plant-Warehouse. If you do not fill this field the defaul Workflow for the entity will be the Workflow with the same name as the product.*\ 

Network Distribution
--------------------
\ **Description**\ 
 \ *Identifies a distribution network, distribution networks are used to establish the source and target of the materials in the supply chain*\ 
\ **Help**\ 
 \ *DRP uses the distribution networks to generate the distribution plan.

A distribution network defines the supply path by a relationship between the source and target warehouse and a percentage of the supply quantity.*\ 

Is MPS
------
\ **Description**\ 
 \ *Indicates if this product is part of the master production schedule*\ 
\ **Help**\ 
 \ *The independent demand products such as end products or spare parts, should be part of the MPS.


This flag is used to segregate the products to be used in reports and inquiries of the MPS and allows to calculate the MPS by the execution of a selective MRP process.*\ 

Create Plan
-----------
\ **Description**\ 
 \ *Indicates whether planned orders will be generated by MRP*\ 
\ **Help**\ 
 \ *Indicates whether planned orders will be generated by MRP, if this flag is not just MRP generate a 'Create' action notice*\ 

Is MRP Required
---------------
\ **Description**\ 
 \ *Is MRP Required*\ 
\ **Help**\ 
 \ *If the MRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e BOM, Orders, Inventory, MPS, etc. and therefore  you need to executed again MRP to adjust the Planned Orders to the new conditions and to get the updated action messages.*\ 

Is DRP Required
---------------
\ **Description**\ 
 \ *Is DRP Required*\ 
\ **Help**\ 
 \ *If the DRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e Network Distribution, Orders, Inventory, MPS, etc. and therefore  you need to executed again DRP to adjust the Planned Orders to the new conditions and to get the updated action messages.*\ 

Promised Delivery Time
----------------------
\ **Description**\ 
 \ *Promised days between order and delivery*\ 
\ **Help**\ 
 \ *The Promised Delivery Time indicates the number of days between the order date and the date that delivery was promised.

You must enter the average number of days to receive the product in the warehouse since you approve the requisition or manufacturing order until you receive the material in the warehouse . If the product is bought you must register the calendar days required since you make the PO until you receive the material in the warehouse. If the product is manufactured in your plant you must register the number of working days since you release the MO until you receive the material in the warehouse.*\ 

Time Fence
----------
\ **Description**\ 
 \ *The Time Fence is the number of days since you execute the MRP process inside of which  the system must not change the planned orders.*\ 
\ **Help**\ 
 \ *The system will generate  action messages warning if some order needs to be modified or created into the time fence.

The Limit time is used for the master plan products, the number of days is the equal or bigger than the product’s delivery time.

It is recommended to establish a limit time, so you don’t have a nervous manufacturing system or a systems that reacts to any change or plan modification.*\ 

Transfer Time
-------------
\ **Description**\ 
 \ *Transfer Time*\ 
\ **Help**\ 
 \ *Indicates the number of days the product needs to be moved from one warehouse to another.*\ 

Order Policy
------------
\ **Description**\ 
 \ *Order Policy*\ 
\ **Help**\ 
 \ *If the DRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e Network Distribution, Orders, Inventory, MPS, etc. and therefore  you need to executed again DRP to adjust the Planned Orders to the new conditions and to get the updated action messages.


Lot-For-Lot  (LFL): Creates planned orders to satisfy the demand, an order is created to satisfy each net requirement. so MRP process must generate one planned order for each demand not satisfied.

Period Order Quantity (POQ): Creates planned orders to satisfy the demand, the requirements are accumulated in a defined period and a planned order is created for the period quantity accumulation. The number of days are entered in the field Order Period.

Use  Fixed Order Quantity when you always need to ask for  the same Quantity of product, this Quantity is entered in the field Order Qty.
* 
If the order policy is not FOQ and you enter a quantity in the Order Qty field, this quantity is the Economic Order Quantity.*\ 

Order Period
------------
\ **Description**\ 
 \ *Order Period*\ 
\ **Help**\ 
 \ *Number of calendar days used to accumulate  the net requirements to integrate the quantity of a planned order under the policy of POQ.*\ 

Order Qty
---------
\ **Description**\ 
 \ *Order Qty*\ 
\ **Help**\ 
 \ *Define the fixed quantity to be ordered when the order policy used is FOQ*\ 

Order Pack Qty
--------------
\ **Description**\ 
 \ *Package order size in UOM (e.g. order set of 5 units)*\ 
\ **Help**\ 
 \ *The Order Pack Quantity indicates the number of units in each pack of this product.*\ 

Minimum Order Qty
-----------------
\ **Description**\ 
 \ *Minimum order quantity in UOM*\ 
\ **Help**\ 
 \ *The Minimum Order Quantity indicates the smallest quantity of this product which can be ordered.*\ 

Maximum Order Qty
-----------------
\ **Description**\ 
 \ *Maximum order quantity in UOM*\ 
\ **Help**\ 
 \ *The Maximum Order Quantity indicates the biggest quantity of this product which can be ordered.*\ 

Safety Stock Qty
----------------
\ **Description**\ 
 \ *Safety stock is a term used to describe a level of stock that is maintained below the cycle stock to buffer against stock-outs*\ 
\ **Help**\ 
 \ *Safety stock is defined as extra units of inventory carried as protection against possible stockouts. It is held when an organization cannot accurately predict demand and/or lead time for the product.

Rereference:
http://en.wikipedia.org/wiki/Safety_stock*\ 

Yield %
-------
\ **Description**\ 
 \ *The Yield is the percentage of a lot that is expected to be of acceptable wuality may fall below 100 percent*\ 
\ **Help**\ 
 \ *ADempiere Calculate the total yield for a product from the yield for each activity when the process Workflow Cost Roll-Up is executed.

The expected yield for an Activity can be expressed as:

Yield = Acceptable Units at Activity End x 100

The Total manufacturing yield for a product is determined by multiplying the yied percentage for each activity.

Manufacturing Yield = Yield % for Activity 10 x Yied % for Activity 20 , etc

Take care when setting yield to anything but 100% particularly when yied is used for multiples activities*\ 

Replenish
---------

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

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

Purchasing
----------

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Quality Rating
--------------
\ **Description**\ 
 \ *Method for rating vendors*\ 
\ **Help**\ 
 \ *The Quality Rating indicates how a vendor is rated (higher number = higher quality)*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Current vendor
--------------
\ **Description**\ 
 \ *Use this Vendor for pricing and stock replenishment*\ 
\ **Help**\ 
 \ *The Current Vendor indicates if prices are used and Product is reordered from this vendor*\ 

UPC/EAN
-------
\ **Description**\ 
 \ *Bar Code (Universal Product Code or its superset European Article Number)*\ 
\ **Help**\ 
 \ *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*\ 

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

Price effective
---------------
\ **Description**\ 
 \ *Effective Date of Price*\ 
\ **Help**\ 
 \ *The Price Effective indicates the date this price is for. This allows you to enter future prices for products which will become effective when appropriate.*\ 

PO Price
--------
\ **Description**\ 
 \ *Price based on a purchase order*\ 
\ **Help**\ 
 \ *The PO Price indicates the price for a product per the purchase order.*\ 

Royalty Amount
--------------
\ **Description**\ 
 \ *(Included) Amount for copyright, etc.*\ 

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

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Minimum Order Qty
-----------------
\ **Description**\ 
 \ *Minimum order quantity in UOM*\ 
\ **Help**\ 
 \ *The Minimum Order Quantity indicates the smallest quantity of this product which can be ordered.*\ 

Order Pack Qty
--------------
\ **Description**\ 
 \ *Package order size in UOM (e.g. order set of 5 units)*\ 
\ **Help**\ 
 \ *The Order Pack Quantity indicates the number of units in each pack of this product.*\ 

Promised Delivery Time
----------------------
\ **Description**\ 
 \ *Promised days between order and delivery*\ 
\ **Help**\ 
 \ *The Promised Delivery Time indicates the number of days between the order date and the date that delivery was promised.*\ 

Actual Delivery Time
--------------------
\ **Description**\ 
 \ *Actual days between order and delivery*\ 
\ **Help**\ 
 \ *The Actual Delivery Time indicates the number of days elapsed between placing an order and the delivery of the order*\ 

Cost per Order
--------------
\ **Description**\ 
 \ *Fixed Cost Per Order*\ 
\ **Help**\ 
 \ *The Cost Per Order indicates the fixed charge levied when an order for this product is placed.*\ 

Partner Product Key
-------------------
\ **Description**\ 
 \ *Product Key of the Business Partner*\ 
\ **Help**\ 
 \ *The Business Partner Product Key identifies the number used by the Business Partner for this product. It can be printed on orders and invoices when you include the Product Key in the print format.*\ 

Partner Category
----------------
\ **Description**\ 
 \ *Product Category of the Business Partner*\ 
\ **Help**\ 
 \ *The Business Partner Category identifies the category used by the Business Partner for this product.*\ 

Manufacturer
------------
\ **Description**\ 
 \ *Manufacturer of the Product*\ 
\ **Help**\ 
 \ *The manufacturer of the Product (used if different from the Business Partner / Vendor)*\ 

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

Transaction
-----------

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

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

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

Manufacturing Cost Collector
----------------------------
