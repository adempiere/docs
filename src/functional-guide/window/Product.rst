
.. _window-product:

=======
Product
=======

Maintain Products

Help
====
The Product Window defines all products used by an organization.  These products include those sold to customers, used in the manufacture of products sold to customers and products purchased by an organization.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Product
-------
\ **Description**\ 
 \ *Define Product*\ 
\ **Help**\ 
 \ *The Product Tab defines each product and identifies it for use in price lists and orders. The Location is the default location when receiving the stored product.*\ 

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

Product Group
-------------
\ **Description**\ 
 \ *Group of a Product*\ 
\ **Help**\ 
 \ *Identifies the Group which this product belongs to.*\ 

Product Class
-------------
\ **Description**\ 
 \ *Class of a Product*\ 
\ **Help**\ 
 \ *Identifies the Class which this product belongs to*\ 

Product Classification
----------------------
\ **Description**\ 
 \ *Classification of a Product*\ 
\ **Help**\ 
 \ *Identifies the classification which this product belongs to.*\ 

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

Group1
------

Group2
------

Revenue Recognition
-------------------
\ **Description**\ 
 \ *Method for recording revenue*\ 
\ **Help**\ 
 \ *The Revenue Recognition indicates how revenue will be recognized for this product*\ 

Classification
--------------
\ **Description**\ 
 \ *Classification for grouping*\ 
\ **Help**\ 
 \ *The Classification can be used to optionally group products.*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Company Agent
-------------
\ **Description**\ 
 \ *Purchase or Company Agent*\ 
\ **Help**\ 
 \ *Purchase agent for the document. Any Sales Rep must be a valid internal user.*\ 

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

Part Type
---------

Discontinued
------------
\ **Description**\ 
 \ *This product is no longer available*\ 
\ **Help**\ 
 \ *The Discontinued check box indicates a product that has been discontinued.*\ 

Manufactured
------------
\ **Description**\ 
 \ *This product is manufactured*\ 

Kanban controlled
-----------------
\ **Description**\ 
 \ *This part is Kanban controlled*\ 

Phantom
-------
\ **Description**\ 
 \ *Phantom Component*\ 
\ **Help**\ 
 \ *Phantom Component are not stored and produced with the product. This is an option to avild maintaining an Engineering and Manufacturing Bill of Materials.*\ 

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

Exclude Auto Delivery
---------------------
\ **Description**\ 
 \ *Exclude from automatic Delivery*\ 
\ **Help**\ 
 \ *The product is excluded from generating Shipments.  This allows manual creation of shipments for high demand items. If selected, you need to create the shipment manually.
But, the item is always included, when the delivery rule of the Order is Force (e.g. for POS). 
This allows finer granularity of the Delivery Rule Manual.*\ 

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
 \ *Product Attribute Values*\ 
\ **Help**\ 
 \ *The values of the actual Product Attributes. Product Instance attributes are defined in the actual transactions.*\ 

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

Copy from product
-----------------
\ **Description**\ 
 \ *Copy prices etc from other product*\ 

BOM
---
\ **Description**\ 
 \ *Bill of Material product lines*\ 
\ **Help**\ 
 \ *The Bill of Materials tab defines those products that are generated from other products.  A Bill of Material (BOM) is one or more Products or BOMs.

Available Quantity:
- Stored BOMs have to be created via "Production"
- The available quantity of a non-stored BOMs is dynamically calculated
- The attribute "Stored" is defined in the "Product" tab

Price:
- BOMs must be listed in Pricelists
- If the price is 0.00, the price is dynamically calculated

Printing:
- Usually, only the BOM information is printed
- For invoices, delivery slips and pick lists, you have the option to print the details
- In the details, the quantity is listed - and the price, if this is dynamically calculated*\ 

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

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Change Notice
-------------
\ **Description**\ 
 \ *Bill of Materials (Engineering) Change Notice (Version)*\ 

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Revision
--------

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

BOM Type
--------
\ **Description**\ 
 \ *Type of BOM*\ 
\ **Help**\ 
 \ *The type of Bills of Materials determines the state*\ 

BOM Use
-------
\ **Description**\ 
 \ *The use of the Bill of Material*\ 
\ **Help**\ 
 \ *By default the Master BOM is used, if the alternatives are not defined*\ 

BOM & Formula
-------------
\ **Description**\ 
 \ *BOM & Formula*\ 

Copy BOM Lines From
-------------------
\ **Description**\ 
 \ *Copy BOM Lines from an exising BOM*\ 
\ **Help**\ 
 \ *Copy BOM Lines from an exising BOM. The BOM being copied to, must not have any existing BOM Lines.*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Components
----------
\ **Description**\ 
 \ *Components*\ 
\ **Help**\ 
 \ *Components of Bill fo Material*\ 

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Component Type
--------------
\ **Description**\ 
 \ *Component Type for a Bill of Material or Formula*\ 
\ **Help**\ 
 \ *The Component Type can be:

1.- By Product: Define a By Product as Component into BOM
2.- Component: Define a normal Component into BOM
3.- Option: Define an Option for Product Configure BOM
4.- Phantom: Define a Phantom as Component into BOM
5.- Packing: Define a Packing as Component into BOM
6.- Planning : Define Planning as Component into BOM
7.- Tools: Define Tools as Component into BOM
8.- Variant: Define Variant  for Product Configure BOM*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Change Notice
-------------
\ **Description**\ 
 \ *Bill of Materials (Engineering) Change Notice (Version)*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range

The Valid From and Valid To dates indicate the valid time period to use the BOM in a Manufacturing Order.*\ 

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 

Is Qty Percentage
-----------------
\ **Description**\ 
 \ *Indicate that this component is based in % Quantity*\ 
\ **Help**\ 
 \ *Indicate that this component is based in % Quantity*\ 

Is Critical Component
---------------------
\ **Description**\ 
 \ *Indicate that a Manufacturing Order can not begin without have this component*\ 
\ **Help**\ 
 \ *Indicate that a Manufacturing Order can not begin without have this component*\ 

Quantity in %
-------------
\ **Description**\ 
 \ *Indicate the Quantity % use in this Formula*\ 
\ **Help**\ 
 \ *Exist two way the add a compenent to a BOM or Formula:

1.- Adding a Component based in quantity to use in this BOM
2.- Adding a Component based in % to use the Order Quantity of Manufacturing Order in this Formula.*\ 

Quantity
--------
\ **Description**\ 
 \ *Indicate the Quantity  use in this BOM*\ 
\ **Help**\ 
 \ *Exist two way the add a compenent to a BOM or Formula:

1.- Adding a Component based in quantity to use in this BOM
2.- Adding a Component based in % to use the Order Quantity of Manufacturing Order in this Formula.*\ 

Scrap %
-------
\ **Description**\ 
 \ *Indicate the Scrap %  for calculate the Scrap Quantity*\ 
\ **Help**\ 
 \ *Scrap is useful to determinate a rigth Standard Cost and management a good supply.*\ 

Quantity Assay
--------------
\ **Description**\ 
 \ *Indicated the Quantity Assay to use into Quality Order*\ 
\ **Help**\ 
 \ *Indicated the Quantity Assay to use into Quality Order*\ 

Issue Method
------------
\ **Description**\ 
 \ *There are two methods for issue the components to Manufacturing Order*\ 
\ **Help**\ 
 \ *Method Issue: The component are delivered one for one and is necessary indicate the delivered quantity for each component.

Method BackFlush: The component are delivered based in BOM, The  delivered quantity for each component is based in BOM or Formula and Manufacturing Order Quantity.

Use the field Backflush Group for grouping the component in a Backflush Method.*\ 

Backflush Group
---------------
\ **Description**\ 
 \ *The Grouping Components to the Backflush*\ 
\ **Help**\ 
 \ *When the components are deliver is possible to indicated The Backflush Group this way you only can deliver the components that are for this Backflush Group.*\ 

Lead Time Offset
----------------
\ **Description**\ 
 \ *Optional Lead Time offset before starting production*\ 
\ **Help**\ 
 \ *Optional Lead Time offset before starting production*\ 

Feature
-------
\ **Description**\ 
 \ *Indicated the Feature for Product Configure*\ 
\ **Help**\ 
 \ *Indicated the Feature for Product Configure*\ 

Forecast
--------
\ **Description**\ 
 \ *Indicated the % of participation this component into a of the BOM Planning*\ 
\ **Help**\ 
 \ *The BOM of Planning Type are useful to Planning the Product family.

For example is possible create a BOM Planning for an Automobile

10% Automobile Red
35% Automobile Blue
45% Automobile Black
19% Automobile Green
1%  Automobile Orange

When Material Plan is calculated MRP generate a Manufacturing Order meet to demand to each  of the Automobile*\ 

BOM & Formula
-------------
\ **Description**\ 
 \ *BOM & Formula*\ 

Part Type
---------

Standard Cost
-------------
\ **Description**\ 
 \ *Standard Costs*\ 
\ **Help**\ 
 \ *Standard (plan) costs.*\ 

Std Cost Amount Sum
-------------------
\ **Description**\ 
 \ *Standard Cost Invoice Amount Sum (internal)*\ 
\ **Help**\ 
 \ *Current cumulative amount for calculating the standard cost difference based on (actual) invoice price*\ 

Bill of Materials
-----------------
\ **Description**\ 
 \ *Bill of Material product lines*\ 
\ **Help**\ 
 \ *The Bill of Materials tab defines those products that are generated from other products.  A Bill of Material (BOM) is one or more Products or BOMs.

Available Quantity:
- Stored BOMs have to be created via "Production"
- The available quantity of a non-stored BOMs is dynamically calculated
- The attribute "Stored" is defined in the "Product" tab

Price:
- BOMs must be listed in Pricelists
- If the price is 0.00, the price is dynamically calculated

Printing:
- Usually, only the BOM information is printed
- For invoices, delivery slips and pick lists, you have the option to print the details
- In the details, the quantity is listed - and the price, if this is dynamically calculated*\ 

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

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

BOM Type
--------
\ **Description**\ 
 \ *Type of BOM*\ 
\ **Help**\ 
 \ *The type of Bills of Materials determines the state*\ 

BOM Product
-----------
\ **Description**\ 
 \ *Bill of Material Component Product*\ 
\ **Help**\ 
 \ *The BOM Product identifies an element that is part of this Bill of Materials.*\ 

BOM Quantity
------------
\ **Description**\ 
 \ *Bill of Materials Quantity*\ 
\ **Help**\ 
 \ *The BOM Quantity indicates the quantity of the product in its Unit of Measure (multiplication)*\ 

Substitute
----------
\ **Description**\ 
 \ *Define Substitute*\ 
\ **Help**\ 
 \ *The Substitute Tab defines products which may be used as a replacement for the selected product.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
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

Substitute
----------
\ **Description**\ 
 \ *Entity which can be used in place of this entity*\ 
\ **Help**\ 
 \ *The Substitute identifies the entity to be used as a substitute for this entity.*\ 

Related
-------
\ **Description**\ 
 \ *Related Product*\ 
\ **Help**\ 
 \ *Related Product - e.g. for promotions*\ 

.. note::
    The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
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

Related Product Type
--------------------

Related Product
---------------
\ **Description**\ 
 \ *Related Product*\ 

Replenish
---------
\ **Description**\ 
 \ *Define Product Replenishment*\ 
\ **Help**\ 
 \ *The Replenishment Tab defines the type of replenishment quantities.  This is used for automated ordering.  If you select a custom replenishment type, you need to create a class implementing org.compiere.util.ReplenishInterface and set that on warehouse level.*\ 

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

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

Qty Batch Size
--------------

Planning Data
-------------
\ **Description**\ 
 \ *Maintain Product Planning Data*\ 
\ **Help**\ 
 \ *in the Window Product Planning Data you enter the product information which will serve as a base to execute the algorithms of Material Requirement Planning, along with MPS, open orders and inventories*\ 

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
\ **Description**\ 
 \ *BOM & Formula*\ 
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

Purchasing
----------
\ **Description**\ 
 \ *Purchasing*\ 
\ **Help**\ 
 \ *The Purchasing Tab define the pricing and rules ( pack quantity, UPC, minimum order quantity) for each product.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Business Partner specific Information of a Product*\ 
\ **Help**\ 
 \ *Note that some information is for reference only!  The*\ 

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

Quality Rating
--------------
\ **Description**\ 
 \ *Method for rating vendors*\ 
\ **Help**\ 
 \ *The Quality Rating indicates how a vendor is rated (higher number = higher quality)*\ 

Min Shelf Life %
----------------
\ **Description**\ 
 \ *Minimum Shelf Life in percent based on Product Instance Guarantee Date*\ 
\ **Help**\ 
 \ *Minimum Shelf Life of products with Guarantee Date instance. If > 0 you cannot select products with a shelf life ((Guarantee Date-Today) / Guarantee Days) less than the minimum shelf life, unless you select "Show All"*\ 

Min Shelf Life Days
-------------------
\ **Description**\ 
 \ *Minimum Shelf Life in days based on Product Instance Guarantee Date*\ 
\ **Help**\ 
 \ *Minimum Shelf Life of products with Guarantee Date instance. If > 0 you cannot select products with a shelf life less than the minimum shelf life, unless you select "Show All"*\ 

Is Manufacturer
---------------
\ **Description**\ 
 \ *Indicate role of this Business partner as Manufacturer*\ 

Price
-----
\ **Description**\ 
 \ *Product Pricing*\ 
\ **Help**\ 
 \ *The Pricing Tab displays the List, Standard and Limit prices for each price list a product is contained in.*\ 

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

Download
--------
\ **Description**\ 
 \ *Maintain Product Downloads*\ 
\ **Help**\ 
 \ *Define downloads for a product.  If the product is an asset, the user can download the data.*\ 

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

Download URL
------------
\ **Description**\ 
 \ *URL of the Download files*\ 
\ **Help**\ 
 \ *Semicolon separated list of URLs to be downloaded or distributed*\ 

Accounting
----------
\ **Description**\ 
 \ *Define Accounting Parameters*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the defaults to use when generating accounting transactions for orders and invoices which contain this product.*\ 

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

Transactions
------------
\ **Description**\ 
 \ *Transactions for stored Products*\ 
\ **Help**\ 
 \ *The Transaction Tab displays the transactions that have been processed for this product.*\ 

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

Receipt Line
------------
\ **Description**\ 
 \ *Line on Receipt document*\ 

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

Translation
-----------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

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

Document Note
-------------
\ **Description**\ 
 \ *Additional information for a Document*\ 
\ **Help**\ 
 \ *The Document Note is used for recording any additional information regarding this product.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Located at
----------
\ **Description**\ 
 \ *Where are my units located?*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Date last inventory count
-------------------------
\ **Description**\ 
 \ *Date of Last Inventory Count*\ 
\ **Help**\ 
 \ *The Date Last Inventory Count indicates the last time an Inventory count was done.*\ 

On Hand Quantity
----------------
\ **Description**\ 
 \ *On Hand Quantity*\ 
\ **Help**\ 
 \ *The On Hand Quantity indicates the quantity of a product that is on hand in a warehouse.*\ 

PO Quantity
-----------
\ **Description**\ 
 \ *Ordered Quantity*\ 
\ **Help**\ 
 \ *The Ordered Quantity indicates the quantity of a product that was ordered.*\ 

On Order Quantity
-----------------
\ **Description**\ 
 \ *Quantity Ordered on Purchase Orders*\ 
\ **Help**\ 
 \ *The Ordered Quantity indicates the quantity of a product that is currently ordered.*\ 

UOM Conversion
--------------

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

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

UoM To
------
\ **Description**\ 
 \ *Target or destination Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM To indicates the destination UOM for a UOM Conversion pair.*\ 

Multiply Rate
-------------
\ **Description**\ 
 \ *Rate to multiple the source by to calculate the target.*\ 
\ **Help**\ 
 \ *To convert Source number to Target number, the Source is multiplied by the multiply rate.  If the Multiply Rate is entered, then the Divide Rate will be automatically calculated.*\ 

Divide Rate
-----------
\ **Description**\ 
 \ *To convert Source number to Target number, the Source is divided*\ 
\ **Help**\ 
 \ *To convert Source number to Target number, the Source is divided by the divide rate.  If you enter a Divide Rate, the Multiply Rate will be automatically calculated.*\ 

Costs
-----

.. note::
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

Future Cost Price
-----------------

Future Cost Price LL
--------------------

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

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Cost Frozen
-----------
\ **Description**\ 
 \ *Indicated that the Standard Cost is frozen*\ 

Memo
----

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

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

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
