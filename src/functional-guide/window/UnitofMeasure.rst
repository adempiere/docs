
.. _window-unitofmeasure:

===============
Unit of Measure
===============

Maintain Unit of Measure 

Help
====
The Unit of Measure Window is used to define non monetary units of measure.  It also defines if conversion between units of measure are allowed and how they are to be performed. The system provides some automatic conversions between units of measures (e.g. minute, hour, day, working day, etc.) if they are not explicitly defined here.
Conversions need to be direct (i.e. if you have only a conversion between A-B and B-C, the system cannot convert A-C, you need to define it explicitly).

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Unit of Measure
---------------
\ **Description**\ 
 \ *Define units of measure*\ 
\ **Help**\ 
 \ *The Unit of Measure Tab defines a non monetary Unit of Measure.*\ 

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

UOM Code
--------
\ **Description**\ 
 \ *UOM EDI X12 Code*\ 
\ **Help**\ 
 \ *The Unit of Measure Code indicates the EDI X12 Code Data Element 355 (Unit or Basis for Measurement)*\ 

Symbol
------
\ **Description**\ 
 \ *Symbol for a Unit of Measure*\ 
\ **Help**\ 
 \ *The Symbol identifies the Symbol to be displayed and printed for a Unit of Measure*\ 

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

UOM Type
--------

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
\ **Description**\ 
 \ *Unit of Measure Translation*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

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

Symbol
------
\ **Description**\ 
 \ *Symbol for a Unit of Measure*\ 
\ **Help**\ 
 \ *The Symbol identifies the Symbol to be displayed and printed for a Unit of Measure*\ 

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

Conversion
----------
\ **Description**\ 
 \ *Define standard Unit of Measure Conversion*\ 
\ **Help**\ 
 \ *The Conversion Tab defines the rates for converting a Unit of Measure. The system provides some automatic conversions between units of measures (e.g. minute, hour, day, working day, etc.) if they are not explicitly defined here.
Conversions need to be direct (i.e. if you have only a conversion between A-B and B-C, the system cannot convert A-C, you need to define it explicitly).*\ 

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

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

UoM To
------
\ **Description**\ 
 \ *Target or destination Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM To indicates the destination UOM for a UOM Conversion pair.*\ 

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
