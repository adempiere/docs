
.. _functional-guide/window/window-attribute:

=========
Attribute
=========

Product Attribute

Help
====
Product Attribute like Color, Size, etc.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Attribute
---------
\ **Description**\ 
 \ *Product Attribute*\ 
\ **Help**\ 
 \ *Product Attribute like Color, Size, etc.  If it is an Instance Attribute, all products have the same value.*\ 

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

Attribute Search
----------------
\ **Description**\ 
 \ *Common Search Attribute*\ 
\ **Help**\ 
 \ *Attributes are specific to a Product Attribute Set (e.g. Size for T-Shirts: S,M,L). If you have multiple attributes and want to search under a common attribute, you define a search attribute. Example: have one Size search attribute combining the values of all different sizes (Size for Dress Shirt  XL,L,M,S,XS). The Attribute Search allows you to have all values available for selection.  This eases the maintenance of the individual product attribute.*\ 

Instance Attribute
------------------
\ **Description**\ 
 \ *The product attribute is specific to the instance (like Serial No, Lot or Guarantee Date)*\ 
\ **Help**\ 
 \ *If selected, the individual instance of the product has this attribute - like the individual Serial or Lot Numbers or  Guarantee Date of a product instance.  If not selected, all instances of the product share the attribute (e.g. color=green).*\ 

Attribute Value
---------------
\ **Description**\ 
 \ *Product Attribute Value*\ 
\ **Help**\ 
 \ *Individual value of a product attribute (e.g. green, large, ..)*\ 

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

Attribute
---------
\ **Description**\ 
 \ *Product Attribute*\ 
\ **Help**\ 
 \ *Product Attribute like Color, Size*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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
