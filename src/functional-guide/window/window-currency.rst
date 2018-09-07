
.. _functional-guide/window/window-currency:

========
Currency
========

Maintain Currencies

Help
====
The Currency Window defines any currency which will be used in documents or reporting. You would define used currencies on System level and add currencies on Client level only for statistical currencies (e.g. for instable currencies) 

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Currency
--------
\ **Description**\ 
 \ *Define Currency*\ 
\ **Help**\ 
 \ *The Currency Tab defines any currency you will transact with or report in.*\ 

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

ISO Currency Code
-----------------
\ **Description**\ 
 \ *Three letter ISO 4217 Code of the Currency*\ 
\ **Help**\ 
 \ *For details - http://www.unece.org/trade/rec/rec09en.htm*\ 

Symbol
------
\ **Description**\ 
 \ *Symbol of the currency (opt used for printing only)*\ 
\ **Help**\ 
 \ *The Currency Symbol defines the symbol that will print when this currency is used.*\ 

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

Standard Precision
------------------
\ **Description**\ 
 \ *Rule for rounding  calculated amounts*\ 
\ **Help**\ 
 \ *The Standard Precision defines the number of decimal places that amounts will be rounded to for accounting transactions and documents.*\ 

Costing Precision
-----------------
\ **Description**\ 
 \ *Rounding used costing calculations*\ 
\ **Help**\ 
 \ *The Costing Precision defines the number of decimal places that amounts will be rounded to when performing costing calculations.*\ 

Translation
-----------

.. note::
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

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

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

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Symbol
------
\ **Description**\ 
 \ *Symbol of the currency (opt used for printing only)*\ 
\ **Help**\ 
 \ *The Currency Symbol defines the symbol that will print when this currency is used.*\ 

Accounting
----------
\ **Description**\ 
 \ *Currency Accounting*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the accounting parameters used for transactions including a currency. Please nore that if not defined, the default accounts of the Accounting Schema are used!*\ 

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

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

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

Realized Gain Acct
------------------
\ **Description**\ 
 \ *Realized Gain Account*\ 
\ **Help**\ 
 \ *The Realized Gain Account indicates the account to be used when recording gains achieved from currency revaluation that have been realized.*\ 

Realized Loss Acct
------------------
\ **Description**\ 
 \ *Realized Loss Account*\ 
\ **Help**\ 
 \ *The Realized Loss Account indicates the account to be used when recording losses incurred from currency revaluation that have yet to be realized.*\ 

Unrealized Gain Acct
--------------------
\ **Description**\ 
 \ *Unrealized Gain Account for currency revaluation*\ 
\ **Help**\ 
 \ *The Unrealized Gain Account indicates the account to be used when recording gains achieved from currency revaluation that have yet to be realized.*\ 

Unrealized Loss Acct
--------------------
\ **Description**\ 
 \ *Unrealized Loss Account for currency revaluation*\ 
\ **Help**\ 
 \ *The Unrealized Loss Account indicates the account to be used when recording losses incurred from currency revaluation that have yet to be realized.*\ 

Conversion Rates
----------------
\ **Description**\ 
 \ *Define currency conversion rates*\ 
\ **Help**\ 
 \ *The Conversion Rate Tab defines the rates to use when converting a source currency to an accounting or reporting currency. Note that only the multiply rate is used; The divide rate is for visualization only.*\ 

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
