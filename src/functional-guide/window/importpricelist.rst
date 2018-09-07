
.. _functional-guide/window/importpricelist:

=================
Import Price List
=================

Import Price Lists

Help
====
The Import Price List Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Import Price List
-----------------
\ **Description**\ 
 \ *Import Price Lists*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Price List
-----------------

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

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

ISO Currency Code
-----------------
\ **Description**\ 
 \ *Three letter ISO 4217 Code of the Currency*\ 
\ **Help**\ 
 \ *For details - http://www.unece.org/trade/rec/rec09en.htm*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Price Precision
---------------
\ **Description**\ 
 \ *Precision (number of decimals) for the Price*\ 
\ **Help**\ 
 \ *The prices of the price list are rounded to the precision entered.  This allows to have prices with below currency precision, e.g. $0.005. Enter the number of decimals or -1 for no rounding.*\ 

Sales Price list
----------------
\ **Description**\ 
 \ *This is a Sales Price List*\ 
\ **Help**\ 
 \ *The Sales Price List check box indicates if this price list is used for sales transactions.*\ 

Price includes Tax
------------------
\ **Description**\ 
 \ *Tax is included in the price*\ 
\ **Help**\ 
 \ *The Tax Included checkbox indicates if the prices include tax.  This is also known as the gross price.*\ 

Enforce price limit
-------------------
\ **Description**\ 
 \ *Do not allow prices below the limit price*\ 
\ **Help**\ 
 \ *The Enforce Price Limit check box indicates that prices cannot be below the limit price in Orders and Invoices.  This can be overwritten, if the role allows this.*\ 

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Product Key
-----------
\ **Description**\ 
 \ *Key of the Product*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Business Partner Key
--------------------
\ **Description**\ 
 \ *The Key of the Business Partner*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Break Value
-----------
\ **Description**\ 
 \ *Low Value of trade discount break level*\ 
\ **Help**\ 
 \ *Starting Quantity or Amount Value for break level*\ 

UOM Code
--------
\ **Description**\ 
 \ *UOM EDI X12 Code*\ 
\ **Help**\ 
 \ *The Unit of Measure Code indicates the EDI X12 Code Data Element 355 (Unit or Basis for Measurement)*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Import Price Lists
------------------
\ **Description**\ 
 \ *Imports price lists from a file into the application*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
