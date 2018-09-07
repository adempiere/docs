
.. _functional-guide/window/window-importproductasi:

==================
Import Product ASI
==================

Import Product ASI

Help
====
The "Import Products ASI" Window is an interim table which is used when importing Attribute Instance for a product from  external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

If a set of attributes, attribute or attribute search is not found, it is created, then an   attributes use is created based on the attribute's name, which are grouped by the attribute set's name

Window Type
-----------
\ **Maintain**\ 


Tabs
====

ASI Product
-----------
\ **Description**\ 
 \ *Import Products ASI*\ 
\ **Help**\ 
 \ *If a set of attributes, attribute or attribute search is not found, it is created, then an   attributes use is created based on the attribute's name, which are grouped by the attribute set's name*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

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

Attribute Set Name
------------------
\ **Description**\ 
 \ *Name of the Attribute Set*\ 
\ **Help**\ 
 \ *Identifier of the Attribute Set*\ 

Attribute Set
-------------
\ **Description**\ 
 \ *Product Attribute Set*\ 
\ **Help**\ 
 \ *Define Product Attribute Sets to add additional attributes and values to the product. You need to define a Attribute Set if you want to enable Serial and Lot Number tracking.*\ 

Lot
---
\ **Description**\ 
 \ *The product instances have a Lot Number*\ 
\ **Help**\ 
 \ *For individual products, you can define Lot Numbers*\ 

Mandatory Lot
-------------
\ **Description**\ 
 \ *The entry of Lot info is mandatory when creating a Product Instance*\ 

Serial No
---------
\ **Description**\ 
 \ *The product instances have Serial Numbers*\ 
\ **Help**\ 
 \ *For individual products, you can define Serial Numbers*\ 

Mandatory Serial No
-------------------
\ **Description**\ 
 \ *The entry of a Serial No is mandatory when creating a Product Instance*\ 

Guarantee Date
--------------
\ **Description**\ 
 \ *Product has Guarantee or Expiry Date*\ 
\ **Help**\ 
 \ *For individual products, you can define a guarantee or expiry date*\ 

Mandatory Guarantee Date
------------------------
\ **Description**\ 
 \ *The entry of a Guarantee Date is mandatory when creating a Product Instance*\ 

Guarantee Days
--------------
\ **Description**\ 
 \ *Number of days the product is guaranteed or available*\ 
\ **Help**\ 
 \ *If the value is 0, there is no limit to the availability or guarantee, otherwise the guarantee date is calculated by adding the days to the delivery date.*\ 

Mandatory Type
--------------
\ **Description**\ 
 \ *The specification of a Product Attribute Instance is mandatory*\ 

Attribute Name
--------------
\ **Description**\ 
 \ *Name of the Attribute*\ 
\ **Help**\ 
 \ *Identifier of the attribute*\ 

Attribute
---------
\ **Description**\ 
 \ *Product Attribute*\ 
\ **Help**\ 
 \ *Product Attribute like Color, Size*\ 

Attribute Value Type
--------------------
\ **Description**\ 
 \ *Type of Attribute Value*\ 
\ **Help**\ 
 \ *The Attribute Value type determines the data/validation type*\ 

Mandatory
---------
\ **Description**\ 
 \ *Data entry is required in this column*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Instance Attribute
------------------
\ **Description**\ 
 \ *The product attribute is specific to the instance (like Serial No, Lot or Guarantee Date)*\ 
\ **Help**\ 
 \ *If selected, the individual instance of the product has this attribute - like the individual Serial or Lot Numbers or  Guarantee Date of a product instance.  If not selected, all instances of the product share the attribute (e.g. color=green).*\ 

Element Name
------------
\ **Description**\ 
 \ *Name of the Element*\ 

Attribute Value
---------------
\ **Description**\ 
 \ *Value of the Attribute*\ 
\ **Help**\ 
 \ *Adempiere converts the (string) field values to the attribute data type.  Booleans (Yes-No) may have the values "true" and "false", the date format is YYYY-MM-DD*\ 

Attribute Value
---------------
\ **Description**\ 
 \ *Product Attribute Value*\ 
\ **Help**\ 
 \ *Individual value of a product attribute (e.g. green, large, ..)*\ 

Attribute Search Name
---------------------
\ **Description**\ 
 \ *Name of the Attribute Search*\ 
\ **Help**\ 
 \ *Identifier of the Attribute Search*\ 

Attribute Search
----------------
\ **Description**\ 
 \ *Common Search Attribute*\ 
\ **Help**\ 
 \ *Attributes are specific to a Product Attribute Set (e.g. Size for T-Shirts: S,M,L). If you have multiple attributes and want to search under a common attribute, you define a search attribute. Example: have one Size search attribute combining the values of all different sizes (Size for Dress Shirt  XL,L,M,S,XS). The Attribute Search allows you to have all values available for selection.  This eases the maintenance of the individual product attribute.*\ 

Import Product ASI
------------------
\ **Description**\ 
 \ *Imports Product Attribute Set Instance  from a file into the application*\ 
\ **Help**\ 
 \ *The parameters are the default values to import the records.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
