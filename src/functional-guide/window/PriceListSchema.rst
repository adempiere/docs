
.. _window-pricelistschema:

=================
Price List Schema
=================

Maintain Price List Schema

Help
====
Price List schema defines calculation rules for price lists

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Price List Schema
-----------------
\ **Description**\ 
 \ *Price List Schema*\ 
\ **Help**\ 
 \ *Price List schema defines calculation rules for price lists*\ 

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

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Discount Type
-------------
\ **Description**\ 
 \ *Type of trade discount calculation*\ 
\ **Help**\ 
 \ *Type of procedure used to calculate the trade discount percentage*\ 

Renumber
--------
\ **Description**\ 
 \ *Renumber Discount entries*\ 

Schema Line
-----------
\ **Description**\ 
 \ *Trade Discount Price List Lines*\ 
\ **Help**\ 
 \ *Pricelists are created based on Product Purchase and Category Discounts.
The parameters listed here allow to copy and calculate pricelists.
The calculation:
<UL>
<LI>Copy and convert price from referenced price list
<LI>result plus Surcharge Amount
<LI>result minus Discount
<LI>if resulting price is less than the original limit price plus min Margin, use this price (only if Margin is not zero)
<LI>if resulting price is more than the original limit price plus max Margin, use this price (only if Margin us not zero)
<LI>Round resulting price
</UL>
\ **The Formula**\  is
NewPrice = (Convert(BasePrice) + Surcharge) * (100-Discount) / 100;
if MinMargin <> 0 then NewPrice = Max (NewPrice, Convert(OrigLimitPrice) + MinMargin);
if MaxMargin <> 0 then NewPrice = Min (NewPrice, Convert(OrigLimitPrice) + MaxMargin);
 
\ **Example:**\  (assuming same currency)
Original Prices:  List=300, Standard=250, Limit=200;
New List Price: Base=List, Surcharge=0, Discount=0, Round*\ 

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

Price List Schema
-----------------
\ **Description**\ 
 \ *Schema to calculate price lists*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

Conversion Date
---------------
\ **Description**\ 
 \ *Date for selecting conversion rate*\ 
\ **Help**\ 
 \ *The Conversion Date identifies the date used for currency conversion. The conversion rate chosen must include this date in it's date range*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

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

Group1
------

Group2
------

List price Base
---------------
\ **Description**\ 
 \ *Price used as the basis for price list calculations*\ 
\ **Help**\ 
 \ *The List Price Base indicates the price to use as the basis for the calculation of a new price list.*\ 

List price min Margin
---------------------
\ **Description**\ 
 \ *Minimum margin for a product*\ 
\ **Help**\ 
 \ *The List Price Min Margin indicates the minimum margin for a product.  The margin is calculated by subtracting the original list price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

List price Surcharge Amount
---------------------------
\ **Description**\ 
 \ *List Price Surcharge Amount*\ 
\ **Help**\ 
 \ *The List Price Surcharge Amount indicates the amount to be added to the price prior to multiplication.*\ 

List price max Margin
---------------------
\ **Description**\ 
 \ *Maximum margin for a product*\ 
\ **Help**\ 
 \ *The List Price Max Margin indicates the maximum margin for a product.  The margin is calculated by subtracting the original list price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

List price Discount %
---------------------
\ **Description**\ 
 \ *Discount from list price as a percentage*\ 
\ **Help**\ 
 \ *The List Price Discount Percentage indicates the percentage discount which will be subtracted from the base price.  A negative amount indicates the percentage which will be added to the base price.*\ 

List price Rounding
-------------------
\ **Description**\ 
 \ *Rounding rule for final list price*\ 
\ **Help**\ 
 \ *The List Price Rounding indicates how the final list price will be rounded.*\ 

Fixed List Price
----------------
\ **Description**\ 
 \ *Fixes List Price (not calculated)*\ 

Standard price Base
-------------------
\ **Description**\ 
 \ *Base price for calculating new standard price*\ 
\ **Help**\ 
 \ *The Standard Price Base indicates the price to use as the basis for the calculation of a new price standard.*\ 

Standard price min Margin
-------------------------
\ **Description**\ 
 \ *Minimum margin allowed for a product*\ 
\ **Help**\ 
 \ *The Standard Price Min Margin indicates the minimum margin for a product.  The margin is calculated by subtracting the original Standard price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

Standard price Surcharge Amount
-------------------------------
\ **Description**\ 
 \ *Amount added to a price as a surcharge*\ 
\ **Help**\ 
 \ *The Standard Price Surcharge Amount indicates the amount to be added to the price prior to multiplication.*\ 

Standard max Margin
-------------------
\ **Description**\ 
 \ *Maximum margin allowed for a product*\ 
\ **Help**\ 
 \ *The Standard Price Max Margin indicates the maximum margin for a product.  The margin is calculated by subtracting the original Standard price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

Standard price Discount %
-------------------------
\ **Description**\ 
 \ *Discount percentage to subtract from base price*\ 
\ **Help**\ 
 \ *The Standard Price Discount Percentage indicates the percentage discount which will be subtracted from the base price.  A negative amount indicates the percentage which will be added to the base price.*\ 

Standard price Rounding
-----------------------
\ **Description**\ 
 \ *Rounding rule for calculated price*\ 
\ **Help**\ 
 \ *The Standard Price Rounding indicates how the final Standard price will be rounded.*\ 

Fixed Standard Price
--------------------
\ **Description**\ 
 \ *Fixed Standard Price (not calculated)*\ 

Limit price Base
----------------
\ **Description**\ 
 \ *Base price for calculation of the new price*\ 
\ **Help**\ 
 \ *Identifies the price to be used as the base for calculating a new price list.*\ 

Limit price min Margin
----------------------
\ **Description**\ 
 \ *Minimum difference to original limit price; ignored if zero*\ 
\ **Help**\ 
 \ *Indicates the minimum margin for a product.  The margin is calculated by subtracting the original limit price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

Limit price Surcharge Amount
----------------------------
\ **Description**\ 
 \ *Amount added to the converted/copied price before multiplying*\ 
\ **Help**\ 
 \ *Indicates the amount to be added to the Limit price prior to multiplication.*\ 

Limit price max Margin
----------------------
\ **Description**\ 
 \ *Maximum difference to original limit price; ignored if zero*\ 
\ **Help**\ 
 \ *Indicates the maximum margin for a product.  The margin is calculated by subtracting the original limit price from the newly calculated price.  If this field contains 0.00 then it is ignored.*\ 

Limit price Discount %
----------------------
\ **Description**\ 
 \ *Discount in percent to be subtracted from base, if negative it will be added to base price*\ 
\ **Help**\ 
 \ *Indicates the discount in percent to be subtracted from base, if negative it will be added to base price*\ 

Limit price Rounding
--------------------
\ **Description**\ 
 \ *Rounding of the final result*\ 
\ **Help**\ 
 \ *A drop down list box which indicates the rounding (if any) will apply to the final prices in this price list.*\ 

Fixed Limit Price
-----------------
\ **Description**\ 
 \ *Fixed Limit Price (not calculated)*\ 
