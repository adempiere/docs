
.. _functional-guide/window/window-forecastdefinition:

===================
Forecast Definition
===================

This window allows to define the valid combinations, used to select the historic sales records. The combinations order is determined by the sequence, where the lower sequence has priority over the higher sequence.

Help
====
The information to define combinations are defined by business partner data (business partner, business partner group, sales region and campaign), Product data (product, category, classification, class and group), factor data for calculus (Alpha Factor, Gamma, Multiplier, Scale).


The suitable use of the forecast definition, allows to generate calculus with different factors for each main group of data defined for a business partner or product.


In this way is possible to get a forecast for each product category, different from another.


To set the sequence of the combinations is possible to use the tab of sequences, with which is possible to define the order of each combination.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Forecast Definition
-------------------
\ **Description**\ 
 \ *This window allows to define the valid combinations, used to select the historic sales records. The combinations order is determined by the sequence, where the lower sequence has priority over the higher sequence.*\ 
\ **Help**\ 
 \ *The information to define combinations are defined by business partner data (business partner, business partner group, sales region and campaign), Product data (product, category, classification, class and group), factor data for calculus (Alpha Factor, Gamma, Multiplier, Scale).*\ 

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

Forecast Definition
-------------------

Forecast Definition Line
------------------------
\ **Description**\ 
 \ *Set different criterias to calculate  the sales forecast.*\ 
\ **Help**\ 
 \ *The suitable use of the forecast definition, allows to generate calculus with different factors for each main group of data defined for a business partner or product.


In this way is possible to get a forecast for each product category, different from another.


To set the sequence of the combinations is possible to use the tab of sequences, with which is possible to define the order of each combination.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Forecast Definition
-------------------

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

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

Product Classification
----------------------
\ **Description**\ 
 \ *Classification of a Product*\ 
\ **Help**\ 
 \ *Identifies the classification which this product belongs to.*\ 

Product Class
-------------
\ **Description**\ 
 \ *Class of a Product*\ 
\ **Help**\ 
 \ *Identifies the Class which this product belongs to*\ 

Product Group
-------------
\ **Description**\ 
 \ *Group of a Product*\ 
\ **Help**\ 
 \ *Identifies the Group which this product belongs to.*\ 

Factor Alpha
------------
\ **Description**\ 
 \ *Identifies an Factor Alpha*\ 
\ **Help**\ 
 \ *The Factor Alpha is smoothing constant used in this exponential smoothing model.*\ 

Factor Gamma
------------
\ **Description**\ 
 \ *Identifies a Factor Gamma*\ 
\ **Help**\ 
 \ *Factor Gamma is the second smoothing constant (gamma) used in this exponential smoothing model This is used to smooth the trend.*\ 

Factor Beta
-----------
\ **Description**\ 
 \ *Identifies a Factor Beta*\ 
\ **Help**\ 
 \ *Factor Beta is the second smoothing constant (beta) used in this Triple exponential smoothing model.

betaTolerance the required precision/accuracy - or tolerance of error - required in the estimate of the beta smoothing constant*\ 

User Factor
-----------
\ **Description**\ 
 \ *Identifies a User Factor*\ 
\ **Help**\ 
 \ *The User Factor used in some forecast rules.*\ 

Factor Multiplier
-----------------
\ **Description**\ 
 \ *Identifies a Factor Multiplier*\ 
\ **Help**\ 
 \ *Factor Multiplier defines the increase or decrease in percentage for the forecast quantity, A negative percentage indicates that the amount is reduced.*\ 

Factor Scale
------------
\ **Description**\ 
 \ *Identifies a Factor Scale*\ 
\ **Help**\ 
 \ *Factor Scale defines the scale in percentage applied for the forecast quantity, this value cannot be negative.*\ 

Sequence
--------

.. note::
    null
