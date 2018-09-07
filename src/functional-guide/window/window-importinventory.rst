
.. _functional-guide/window/window-importinventory:

================
Import Inventory
================

Import Inventory Transactions

Help
====
Validate and Import Inventory Transactions

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Inventory
---------
\ **Description**\ 
 \ *Import Inventory*\ 
\ **Help**\ 
 \ *Validate and Import Inventory Transactions. The Locator is primarily determined by the Locator Key, then the Warehouse and X,Y,Z fields.
A Physical Inventory is created per Warehouse and Movement Date.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Inventory
----------------
\ **Description**\ 
 \ *Import Inventory Transactions*\ 

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Phys.Inventory
--------------
\ **Description**\ 
 \ *Parameters for a Physical Inventory*\ 
\ **Help**\ 
 \ *The Physical Inventory indicates a unique parameters for a physical inventory.*\ 

Phys.Inventory Line
-------------------
\ **Description**\ 
 \ *Unique line in an Inventory document*\ 
\ **Help**\ 
 \ *The Physical Inventory Line indicates the inventory document line (if applicable) for this transaction*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

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

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

Warehouse Key
-------------
\ **Description**\ 
 \ *Key of the Warehouse*\ 
\ **Help**\ 
 \ *Key to identify the Warehouse*\ 

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

Locator Key
-----------
\ **Description**\ 
 \ *Key of the Warehouse Locator*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

UPC/EAN
-------
\ **Description**\ 
 \ *Bar Code (Universal Product Code or its superset European Article Number)*\ 
\ **Help**\ 
 \ *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Quantity book
-------------
\ **Description**\ 
 \ *Book Quantity*\ 
\ **Help**\ 
 \ *The Quantity Book indicates the line count stored in the system for a product in inventory*\ 

Quantity count
--------------
\ **Description**\ 
 \ *Counted Quantity*\ 
\ **Help**\ 
 \ *The Quantity Count indicates the actual inventory count taken for a product in inventory*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

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

Import Inventory
----------------
\ **Description**\ 
 \ *Import Physical Inventory*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.*\ 
