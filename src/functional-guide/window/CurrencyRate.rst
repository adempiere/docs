
.. _window-currencyrate:

=============
Currency Rate
=============

Maintain Currency Conversion Rates

Help
====
The Conversion Rates window is used to define the conversion rates that will be used when converting document amounts from one currency to another. Note that only the multiply rate is used; The divide rate is for visualization only.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Conversion Rate
---------------
\ **Description**\ 
 \ *Define Currency Conversion Rates*\ 
\ **Help**\ 
 \ *The Conversion Rates tab is used to define conversion rates to be used when converting document amounts from one currency to another.  Conversion rates can be defined for multiple rate types.  They can also be effective for a defined range of dates. Note that only the multiply rate is used; The divide rate is for visualization only.*\ 

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

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Currency To
-----------
\ **Description**\ 
 \ *Target currency*\ 
\ **Help**\ 
 \ *The Currency To defines the target currency for this conversion rate.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

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
