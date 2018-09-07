
.. _functional-guide/window/window-asset:

=====
Asset
=====

Asset used internally or by customers

Help
====
An asset is either created by purchasing or by delivering a product.  An asset can be used internally or be a customer asset.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Asset
-----
\ **Description**\ 
 \ *Asset used internally or by customers*\ 
\ **Help**\ 
 \ *An asset is either created by purchasing or by delivering a product.  An asset can be used internally or be a customer asset.*\ 

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

Inventory No
------------

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

Parent Asset
------------

Asset Group
-----------
\ **Description**\ 
 \ *Group of Assets*\ 
\ **Help**\ 
 \ *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*\ 

Version No
----------
\ **Description**\ 
 \ *Version Number*\ 

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

Serial No
---------
\ **Description**\ 
 \ *Product Serial Number*\ 
\ **Help**\ 
 \ *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*\ 

Manufactured Year
-----------------

Lot No
------
\ **Description**\ 
 \ *Lot number (alphanumeric)*\ 
\ **Help**\ 
 \ *The Lot Number indicates the specific lot that a product was part of.*\ 

In Service Date
---------------
\ **Description**\ 
 \ *Date when Asset was put into service*\ 
\ **Help**\ 
 \ *The date when the asset was put into service - usually used as start date for depreciation.*\ 

Guarantee Date
--------------
\ **Description**\ 
 \ *Date when guarantee expires*\ 
\ **Help**\ 
 \ *Date when the normal guarantee or availability expires*\ 

Create Date
-----------

Revaluation Date
----------------

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

In Possession
-------------
\ **Description**\ 
 \ *The asset is in the possession of the organization*\ 
\ **Help**\ 
 \ *Assets which are not in possession are e.g. at Customer site and may or may not be owned by the company.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

BPartner (Agent)
----------------
\ **Description**\ 
 \ *Business Partner (Agent or Sales Rep)*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Location comment
----------------
\ **Description**\ 
 \ *Additional comments or remarks concerning the location*\ 

Owned
-----
\ **Description**\ 
 \ *The asset is owned by the organization*\ 
\ **Help**\ 
 \ *The asset may not be in possession, but the asset is legally owned by the organization*\ 

Lessor
------
\ **Description**\ 
 \ *The Business Partner who rents or leases*\ 

Lease Termination
-----------------
\ **Description**\ 
 \ *Lease Termination Date*\ 
\ **Help**\ 
 \ *Last Date of Lease*\ 

Depreciate
----------
\ **Description**\ 
 \ *The asset will be depreciated*\ 
\ **Help**\ 
 \ *The asset is used internally and will be depreciated*\ 

Fully depreciated
-----------------
\ **Description**\ 
 \ *The asset is fully depreciated*\ 
\ **Help**\ 
 \ *The asset costs are fully amortized.*\ 

Life use
--------
\ **Description**\ 
 \ *Units of use until the asset is not usable anymore*\ 
\ **Help**\ 
 \ *Life use and the actual use may be used to calculate the depreciation*\ 

Use units
---------
\ **Description**\ 
 \ *Currently used units of the assets*\ 

Last Maintenance
----------------
\ **Description**\ 
 \ *Last Maintenance Date*\ 

Last Unit
---------
\ **Description**\ 
 \ *Last Maintenance Unit*\ 

Last Note
---------
\ **Description**\ 
 \ *Last Maintenance Note*\ 

Next Maintenence
----------------
\ **Description**\ 
 \ *Next Maintenence Date*\ 

Next Unit
---------
\ **Description**\ 
 \ *Next Maintenence Unit*\ 

Asset Status
------------

Activation Date
---------------

Asset Depreciation Date
-----------------------
\ **Description**\ 
 \ *Date of last depreciation*\ 
\ **Help**\ 
 \ *Date of the last deprecation, if the asset is used internally and depreciated.*\ 

Disposed
--------
\ **Description**\ 
 \ *The asset is disposed*\ 
\ **Help**\ 
 \ *The asset is no longer used and disposed*\ 

Asset Disposal Date
-------------------
\ **Description**\ 
 \ *Date when the asset is/was disposed*\ 

Product
-------

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

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

Fixed Asset Current Qty
-----------------------
\ **Description**\ 
 \ *Fixed Asset Current Quantity*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Asset Balances
--------------
\ **Description**\ 
 \ *Asset Balance Report and Adjustments*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Fixed Asset Cost
----------------
\ **Description**\ 
 \ *Cost of acquisition of the Fixed Asset*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Asset Salvage Value
-------------------

Accumulated Depreciation
------------------------

Accumulated Depreciation (fiscal)
---------------------------------

Remaining Amt
-------------

Remaining Amt (fiscal)
----------------------

SL Expense/Period
-----------------

SL Expense/Period (fiscal)
--------------------------

Life periods (min)
------------------

Life periods (max)
------------------

Usable Life - Years
-------------------
\ **Description**\ 
 \ *Years of the usable life of the asset*\ 

Use Life - Years (fiscal)
-------------------------

Usable Life - Months
--------------------
\ **Description**\ 
 \ *Months of the usable life of the asset*\ 

Use Life - Months (fiscal)
--------------------------

Depreciate
----------
\ **Description**\ 
 \ *The asset will be depreciated*\ 
\ **Help**\ 
 \ *The asset is used internally and will be depreciated*\ 

Current Period
--------------

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Update depreciation
-------------------

Accounting Setup
----------------
\ **Description**\ 
 \ *Enter accounting setup information*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Asset Salvage Value
-------------------

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Depreciation
------------

Depreciation (fiscal)
---------------------

Asset Acct
----------

Accumulated Depreciation Account
--------------------------------

Depreciation Account
--------------------

Disposal Revenue Acct
---------------------

Disposal Loss Acct
------------------

Cost Details
------------
\ **Description**\ 
 \ *Cost Detail*\ 

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

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Capital/Expense
---------------

Source Type
-----------

Journal Batch
-------------
\ **Description**\ 
 \ *General Ledger Journal Batch*\ 
\ **Help**\ 
 \ *The General Ledger Journal Batch identifies a group of journals to be processed as a group.*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

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

Asset value
-----------
\ **Description**\ 
 \ *Book Value of the asset*\ 

Fixed Asset Current Qty
-----------------------
\ **Description**\ 
 \ *Fixed Asset Current Quantity*\ 

Activation/Addition
-------------------
\ **Description**\ 
 \ *Activation/Addition*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Create Asset
------------

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Document Date
-------------
\ **Description**\ 
 \ *Date of the Document*\ 
\ **Help**\ 
 \ *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Capital/Expense
---------------

Source Type
-----------

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Invoice Line
------------
\ **Description**\ 
 \ *Invoice Detail Line*\ 
\ **Help**\ 
 \ *The Invoice Line uniquely identifies a single line of an Invoice.*\ 

Match Invoice
-------------
\ **Description**\ 
 \ *Match Shipment/Receipt to Invoice*\ 

Shipment/Receipt Line
---------------------
\ **Description**\ 
 \ *Line on Shipment or Receipt document*\ 
\ **Help**\ 
 \ *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Imported Fixed Asset
--------------------

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

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Source Amount
-------------

Asset value
-----------
\ **Description**\ 
 \ *Book Value of the asset*\ 

Entered Amount
--------------

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Fixed Asset Current Qty
-----------------------
\ **Description**\ 
 \ *Fixed Asset Current Quantity*\ 

Accumulated Depreciation
------------------------

Accumulated Depreciation (fiscal)
---------------------------------

Delta Use Life Years
--------------------

Delta Use Life Years (fiscal)
-----------------------------
\ **Description**\ 
 \ *Delta Use Life Years (fiscal)*\ 

Life periods (min)
------------------

Life periods (max)
------------------

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Document Status
---------------
\ **Description**\ 
 \ *The current status of the document*\ 
\ **Help**\ 
 \ *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*\ 

Asset Addition Process
----------------------

Disposal
--------

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Disposed Method
---------------

Disposed Date
-------------

Document Date
-------------
\ **Description**\ 
 \ *Date of the Document*\ 
\ **Help**\ 
 \ *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Asset Proceeds
--------------

Asset Trade
-----------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Asset Usage
-----------
\ **Description**\ 
 \ *Record Asset Usage*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

UseDate
-------

Use units
---------
\ **Description**\ 
 \ *Currently used units of the assets*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Delivery
--------
\ **Description**\ 
 \ *Delivery or availability*\ 
\ **Help**\ 
 \ *Record of delivery or availability*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Product Download
----------------
\ **Description**\ 
 \ *Product downloads*\ 
\ **Help**\ 
 \ *Define download for a product. If the product is an asset, the user can download the data.*\ 

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Version No
----------
\ **Description**\ 
 \ *Version Number*\ 

Lot No
------
\ **Description**\ 
 \ *Lot number (alphanumeric)*\ 
\ **Help**\ 
 \ *The Lot Number indicates the specific lot that a product was part of.*\ 

Serial No
---------
\ **Description**\ 
 \ *Product Serial Number*\ 
\ **Help**\ 
 \ *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*\ 

Shipment/Receipt Line
---------------------
\ **Description**\ 
 \ *Line on Shipment or Receipt document*\ 
\ **Help**\ 
 \ *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

Message ID
----------
\ **Description**\ 
 \ *EMail Message ID*\ 
\ **Help**\ 
 \ *SMTP Message ID for tracking purposes*\ 

Delivery Confirmation
---------------------
\ **Description**\ 
 \ *EMail Delivery confirmation*\ 

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Referrer
--------
\ **Description**\ 
 \ *Referring web address*\ 

Remote Addr
-----------
\ **Description**\ 
 \ *Remote Address*\ 
\ **Help**\ 
 \ *The Remote Address indicates an alternative or external address.*\ 

Remote Host
-----------
\ **Description**\ 
 \ *Remote host Info*\ 

Asset History
-------------
\ **Description**\ 
 \ *Detail asset transaction history*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Details
-------

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

ChangeType
----------

Created
-------
\ **Description**\ 
 \ *Date this record was created*\ 
\ **Help**\ 
 \ *The Created field indicates the date that this record was created.*\ 

Updated By
----------
\ **Description**\ 
 \ *User who updated this records*\ 
\ **Help**\ 
 \ *The Updated By field indicates the user who updated this record.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

A_Period_Start
--------------

A_Period_End
------------

DepreciationType
----------------

A_Depreciation_Manual_Amount
----------------------------

A_Depreciation_Manual_Period
----------------------------

Variable Percent
----------------

A_Depreciation_Table_Header_ID
------------------------------

Calculation Type
----------------

Spread Type
-----------

ConventionType
--------------

Asset Salvage Value
-------------------

Split Percent
-------------

Owned
-----
\ **Description**\ 
 \ *The asset is owned by the organization*\ 
\ **Help**\ 
 \ *The asset may not be in possession, but the asset is legally owned by the organization*\ 

In Possession
-------------
\ **Description**\ 
 \ *The asset is in the possession of the organization*\ 
\ **Help**\ 
 \ *Assets which are not in possession are e.g. at Customer site and may or may not be owned by the company.*\ 

Depreciate
----------
\ **Description**\ 
 \ *The asset will be depreciated*\ 
\ **Help**\ 
 \ *The asset is used internally and will be depreciated*\ 

Fully depreciated
-----------------
\ **Description**\ 
 \ *The asset is fully depreciated*\ 
\ **Help**\ 
 \ *The asset costs are fully amortized.*\ 

Disposed
--------
\ **Description**\ 
 \ *The asset is disposed*\ 
\ **Help**\ 
 \ *The asset is no longer used and disposed*\ 

A_Reval_Cal_Method
------------------

ChangeAmt
---------

Asset value
-----------
\ **Description**\ 
 \ *Book Value of the asset*\ 

AssetBookValueAmt
-----------------

AssetAccumDepreciationAmt
-------------------------

Market value Amount
-------------------
\ **Description**\ 
 \ *Market value of the asset*\ 
\ **Help**\ 
 \ *For reporting, the market value of the asset*\ 

A_QTY_Original
--------------

Fixed Asset Current Qty
-----------------------
\ **Description**\ 
 \ *Fixed Asset Current Quantity*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Create Date
-----------

In Service Date
---------------
\ **Description**\ 
 \ *Date when Asset was put into service*\ 
\ **Help**\ 
 \ *The date when the asset was put into service - usually used as start date for depreciation.*\ 

Asset Depreciation Date
-----------------------
\ **Description**\ 
 \ *Date of last depreciation*\ 
\ **Help**\ 
 \ *Date of the last deprecation, if the asset is used internally and depreciated.*\ 

Revaluation Date
----------------

Asset Disposal Date
-------------------
\ **Description**\ 
 \ *Date when the asset is/was disposed*\ 

Usable Life - Years
-------------------
\ **Description**\ 
 \ *Years of the usable life of the asset*\ 

Usable Life - Months
--------------------
\ **Description**\ 
 \ *Months of the usable life of the asset*\ 

Life use
--------
\ **Description**\ 
 \ *Units of use until the asset is not usable anymore*\ 
\ **Help**\ 
 \ *Life use and the actual use may be used to calculate the depreciation*\ 

Use units
---------
\ **Description**\ 
 \ *Currently used units of the assets*\ 

Parent Asset
------------

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Lot No
------
\ **Description**\ 
 \ *Lot number (alphanumeric)*\ 
\ **Help**\ 
 \ *The Lot Number indicates the specific lot that a product was part of.*\ 

Serial No
---------
\ **Description**\ 
 \ *Product Serial Number*\ 
\ **Help**\ 
 \ *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*\ 

Version No
----------
\ **Description**\ 
 \ *Version Number*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Asset Acct
----------

Depreciation Account
--------------------

Accumulated Depreciation Account
--------------------------------

Disposal Revenue
----------------

Disposal Revenue Acct
---------------------

Disposal Loss Acct
------------------

Loss on Disposal
----------------

Revaluation Cost Offset for Current Year
----------------------------------------

Reval Cost Offset Acct
----------------------

Revaluation Cost Offset for Prior Year
--------------------------------------

Reval Cost Offset Prior Acct
----------------------------

A_Reval_Accumdep_Offset_Cur
---------------------------

Revaluation Accumulated Depreciation Offset for Current Year
------------------------------------------------------------

A_Reval_Accumdep_Offset_Prior
-----------------------------

Revaluation Accumulated Depreciation Offset for Prior Year
----------------------------------------------------------

Reval Depexp Offset Acct
------------------------

Revaluation Expense Offs
------------------------

A_Asset_Change_ID
-----------------

Issue Project
-------------
\ **Description**\ 
 \ *Automatic Issue Reporting*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

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

System Status
-------------
\ **Description**\ 
 \ *Status of the system - Support priority depends on system status*\ 
\ **Help**\ 
 \ *System status helps to prioritize support resources*\ 

Statistics
----------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics as well as general anonymous statistics*\ 

Profile
-------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics*\ 

Finance Information
-------------------
\ **Description**\ 
 \ *Finace Information for the Asset*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Asset Finance Method
--------------------

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Contract Date
-------------

Asset Expired Date
------------------

Asset Monthly Payment
---------------------

Asset Due On
------------

Purchase Option
---------------

Purchase Price
--------------

Purchase Option Credit
----------------------

Purchase Option Credit %
------------------------

Text Message
------------
\ **Description**\ 
 \ *Text Message*\ 

License Information
-------------------
\ **Description**\ 
 \ *License Information for Asset*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Description
-----------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Issuing Agency
--------------

Asset License No
----------------

Asset License Fee
-----------------

Asset Renewal Date
------------------

Insurance Information
---------------------
\ **Description**\ 
 \ *Insurance Information for asset*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Insurance Company
-----------------

Asset Policy No
---------------

Asset Renewal Date
------------------

Asset Insurance Premium
-----------------------

Asset Replace Cost
------------------

Asset Insurance Value
---------------------

Description
-----------

Tax Information
---------------
\ **Description**\ 
 \ *Tax information for asset*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Asset Tax Entity
----------------

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Asset New Used
--------------

Asset Finance Method
--------------------

Asset Investment CR
-------------------

Text Message
------------
\ **Description**\ 
 \ *Text Message*\ 

Other Information
-----------------
\ **Description**\ 
 \ *Other information associated with asset*\ 

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

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

A_User1
-------

A_User10
--------

A_User2
-------

A_User11
--------

A_User3
-------

A_User12
--------

A_User4
-------

A_User13
--------

A_User5
-------

A_User14
--------

A_User6
-------

A_User15
--------

A_User7
-------

A_User8
-------

A_User9
-------

Description
-----------

Expense
-------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Read Only indicates that this field may only be Read.  It may not be updated.

Fields
======

Entry Type
----------

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Expense
-------

Expense (fiscal)
----------------

Account (debit)
---------------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Account (credit)
----------------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Asset Period
------------

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Fixed Asset Cost
----------------
\ **Description**\ 
 \ *Cost of acquisition of the Fixed Asset*\ 

Delta Asset Cost
----------------

Accumulated Depreciation
------------------------

Accumulated Depreciation (delta)
--------------------------------

Accumulated Depreciation (fiscal)
---------------------------------

Accumulated Depreciation - fiscal (delta)
-----------------------------------------

Remaining Amt
-------------

Remaining Amt (fiscal)
----------------------

Usable Life - Months
--------------------
\ **Description**\ 
 \ *Months of the usable life of the asset*\ 

Use Life - Months (fiscal)
--------------------------

Asset Addition
--------------

Asset Disposed
--------------
