
.. _functional-guide/window/window-pricelist:

==========
Price List
==========

Maintain Product Price Lists

Help
====
The Price List Window allows you to generate product price lists for your Business Partners.  Price lists determine currency and tax treatment.  Price list versions allow to maintain parallel lists for different date ranges.  The most current pricelist version is used based on the document date.

All pricelists have three prices: List, Standard and Limit

First step is to create a base price list.  You can manually add products and enter the prices or create them automatically.  The base price list is often the purchase price list with list price ('official' retail price), the standard price (your purchase price).  The limit price can be used to check your final purchase costs after discounts, rebates, etc.
*  
Pricelists can be calculated and copied.  To speed up the calculation, the parameters are stored an used when creating a new price list version.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Price List
----------
\ **Description**\ 
 \ *Define Price Lists*\ 
\ **Help**\ 
 \ *Price lists determine currency of the document as well as tax treatment.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

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

Net Price
---------
\ **Description**\ 
 \ *Net Price including all discounts*\ 
\ **Help**\ 
 \ *If price is set as "Net Price" no further discounts will be applied.*\ 

Version
-------
\ **Description**\ 
 \ *Maintain price list versions*\ 
\ **Help**\ 
 \ *Price lists are automatically created based on Product Purchasing Information and the Vendor Category Discount.
The other alternative is to copy them from existing pricelists and the re-calculate them.
You can also re-calculate the pricelist by referencing no pricelist or referencing the same pricelist.  If no base price list is selected, the Procuct Purchase records are used as reference.*\ 

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

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

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

Price List Schema
-----------------
\ **Description**\ 
 \ *Schema to calculate price lists*\ 

Base Price List
---------------
\ **Description**\ 
 \ *Source for Price list calculations*\ 
\ **Help**\ 
 \ *The Base Price List identifies the Base Pricelist used for calculating prices (the source)*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Create Price List
-----------------
\ **Description**\ 
 \ *Create Prices based on parameters of this version*\ 
\ **Help**\ 
 \ *Create Prices for this pricelist version in the sequence of the Discount Schema Price List.
Lines with a higher sequence overwrite existing prices.  The sequence should be from generic to specific.*\ 

Create Product Entries in Pricelist
-----------------------------------

Product Price
-------------
\ **Description**\ 
 \ *Maintain Product Prices*\ 
\ **Help**\ 
 \ *The Price List Tab displays the prices for a product based on the selected price list.*\ 

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

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 

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

Product Price Break
-------------------

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

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 

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

Break Value
-----------
\ **Description**\ 
 \ *Low Value of trade discount break level*\ 
\ **Help**\ 
 \ *Starting Quantity or Amount Value for break level*\ 

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
