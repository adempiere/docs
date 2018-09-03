
.. _window-productbom:

===========
Product BOM
===========

Maintain Product Bill of Materials

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Product
-------
\ **Description**\ 
 \ *Maintain Product Information*\ 

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

Alternative Groups
------------------
\ **Description**\ 
 \ *Product BOM Alternative Group*\ 
\ **Help**\ 
 \ *Alternative groups allow you to group Bill of Material components, which are exclusive (i.e. only one is valid). Examples different engine sizes.*\ 

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

Operation
---------
\ **Description**\ 
 \ *Product Manufacturing Operation*\ 
\ **Help**\ 
 \ *The Operations to create the product.  Note that the actual used operation and sequence is determined by the BOM Product.*\ 

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

Setup Time
----------
\ **Description**\ 
 \ *Setup time before starting Production*\ 
\ **Help**\ 
 \ *Once per operation*\ 

Teardown Time
-------------
\ **Description**\ 
 \ *Time at the end of the operation*\ 
\ **Help**\ 
 \ *Once per operation*\ 

Runtime per Unit
----------------
\ **Description**\ 
 \ *Time to produce one unit*\ 

Operation Resource
------------------
\ **Description**\ 
 \ *Product Operation Resources*\ 
\ **Help**\ 
 \ *Resources for the Operation. You can have multiple resources (e.g. tool, labor) per operation.*\ 

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

Product Operation
-----------------
\ **Description**\ 
 \ *Product Manufacturing Operation*\ 
\ **Help**\ 
 \ *The Operations to create the product.  Note that the actual used operation and sequence is determined by the BOM Product.*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Position
--------
\ **Description**\ 
 \ *Job Position*\ 

Setup Time
----------
\ **Description**\ 
 \ *Setup time before starting Production*\ 
\ **Help**\ 
 \ *Once per operation*\ 

Teardown Time
-------------
\ **Description**\ 
 \ *Time at the end of the operation*\ 
\ **Help**\ 
 \ *Once per operation*\ 

Runtime per Unit
----------------
\ **Description**\ 
 \ *Time to produce one unit*\ 

BOM
---
\ **Description**\ 
 \ *Bill of Materials*\ 

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

Change Notice
-------------
\ **Description**\ 
 \ *Bill of Materials (Engineering) Change Notice (Version)*\ 

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

Process Now
-----------

BOM Component
-------------
\ **Description**\ 
 \ *Bill of Material Component (Product)*\ 
\ **Help**\ 
 \ *The Bill of Material Compoment determines what products, services and outside processing is included in producing the Product. It references the operation and determines it's sequence.*\ 

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

BOM
---
\ **Description**\ 
 \ *Bill of Material*\ 
\ **Help**\ 
 \ *The composition of the Product*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

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

Component Type
--------------
\ **Description**\ 
 \ *BOM Product Type*\ 

Alternative Group
-----------------
\ **Description**\ 
 \ *Product BOM Alternative Group*\ 
\ **Help**\ 
 \ *Alternative groups allow you to group Bill of Material components, which are exclusive (i.e. only one is valid). Examples different engine sizes.*\ 

Phantom
-------
\ **Description**\ 
 \ *Phantom Component*\ 
\ **Help**\ 
 \ *Phantom Component are not stored and produced with the product. This is an option to avild maintaining an Engineering and Manufacturing Bill of Materials.*\ 

BOM Product
-----------
\ **Description**\ 
 \ *Bill of Material Component Product*\ 
\ **Help**\ 
 \ *The BOM Product identifies an element that is part of this Bill of Materials.*\ 

Change Notice
-------------
\ **Description**\ 
 \ *Bill of Materials (Engineering) Change Notice (Version)*\ 

BOM Quantity
------------
\ **Description**\ 
 \ *Bill of Materials Quantity*\ 
\ **Help**\ 
 \ *The BOM Quantity indicates the quantity of the product in its Unit of Measure (multiplication)*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Product Operation
-----------------
\ **Description**\ 
 \ *Product Manufacturing Operation*\ 
\ **Help**\ 
 \ *The Operations to create the product.  Note that the actual used operation and sequence is determined by the BOM Product.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Lead Time Offset
----------------
\ **Description**\ 
 \ *Optional Lead Time offset before starting production*\ 
\ **Help**\ 
 \ *Optional Lead Time offset before starting production*\ 
