
.. _functional-guide/window/window-importcurrencyrate:

====================
Import Currency Rate
====================

Import Currency Conversion Rates

Help
====
The rates are imported after validation of currencies and conversion rate type as well as rates. The multiply rate is used. If a reciprocal rate is to be created, the divide rate is used. 

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Currency Rate
--------------------
\ **Description**\ 
 \ *Import Currency Conversion Rate*\ 

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Conversion Rate
----------------------
\ **Description**\ 
 \ *Import Currency Conversion Rate*\ 

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Conversion Rate
---------------
\ **Description**\ 
 \ *Rate used for converting currencies*\ 
\ **Help**\ 
 \ *The Conversion Rate defines the rate (multiply or divide) to use when converting a source currency to an accounting currency.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

ISO Currency To Code
--------------------
\ **Description**\ 
 \ *Three letter ISO 4217 Code of the To Currency*\ 
\ **Help**\ 
 \ *For details - http://www.unece.org/trade/rec/rec09en.htm*\ 

Currency To
-----------
\ **Description**\ 
 \ *Target currency*\ 
\ **Help**\ 
 \ *The Currency To defines the target currency for this conversion rate.*\ 

Currency Type Key
-----------------
\ **Description**\ 
 \ *Key value for the Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The date type key for the conversion of foreign currency transactions*\ 

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

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

Create Reciprocal Rate
----------------------
\ **Description**\ 
 \ *Create Reciprocal Rate from current information*\ 
\ **Help**\ 
 \ *If selected, the imported USD->EUR rate is used to create/calculate the reciprocal rate EUR->USD.*\ 

Import Conversion Rate
----------------------
\ **Description**\ 
 \ *Import Currency Conversion Rate*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
