
.. _functional-guide/window/vendordetails:

==============
Vendor Details
==============

Maintain Vendor Details

Help
====
The Vendor Details Window allows you to display and maintain all products for a selected Vendor.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Vendor
------
\ **Description**\ 
 \ *Vendor*\ 
\ **Help**\ 
 \ *The Vendor Tab displays the Vendors.  A Vendor is selected and all products for that Vendor will be displayed.*\ 

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

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

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Open Balance
------------
\ **Description**\ 
 \ *Total Open Balance Amount in primary Accounting Currency*\ 
\ **Help**\ 
 \ *The Total Open Balance Amount is the calculated open item amount for Customer and Vendor activity.  If the Balance is below zero, we owe the Business Partner.  The amount is used for Credit Management.
Invoices and Payment Allocations determine the Open Balance (i.e. not Orders or Payments).*\ 

Product Details
---------------
\ **Description**\ 
 \ *Product Details*\ 
\ **Help**\ 
 \ *The Product Details Tab allows you to display and maintain all products for a selected Vendor.*\ 

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
