
.. _functional-guide/window/window-attributeset:

=============
Attribute Set
=============

Maintain Product Attribute Set

Help
====
Define Product Attribute Sets to add additional attributes and values to the product. You need to define a Attribute Set if you want to enable Serial and Lot Number tracking.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Attribute Set
-------------
\ **Description**\ 
 \ *Maintain Product Attribute Set*\ 
\ **Help**\ 
 \ *Define Product Attribute Sets to add additional attributes and values to the product. You need to define an Attribute Set if you want to enable Serial and Lot Number and Guarantee Date tracking.  Note that the Guarantee Days here determine the Shelf Life of a product instance after manufacturing (the Guarantee Days on the product determines a Customer Service date after selling)
If the Attribute Set is mandatory, a product instance needs to be selected/created before shipping.*\ 

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

Instance Attribute
------------------
\ **Description**\ 
 \ *The product attribute is specific to the instance (like Serial No, Lot or Guarantee Date)*\ 
\ **Help**\ 
 \ *If selected, the individual instance of the product has this attribute - like the individual Serial or Lot Numbers or  Guarantee Date of a product instance.  If not selected, all instances of the product share the attribute (e.g. color=green).*\ 

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

Lot Control
-----------
\ **Description**\ 
 \ *Product Lot Control*\ 
\ **Help**\ 
 \ *Definition to create Lot numbers for Products*\ 

Lot Char Start Overwrite
------------------------
\ **Description**\ 
 \ *Lot/Batch Start Indicator overwrite - default «*\ 
\ **Help**\ 
 \ *If not defined, the default character « is used*\ 

Lot Char End Overwrite
----------------------
\ **Description**\ 
 \ *Lot/Batch End Indicator overwrite - default »*\ 
\ **Help**\ 
 \ *If not defined, the default character » is used*\ 

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

Serial No Control
-----------------
\ **Description**\ 
 \ *Product Serial Number Control*\ 
\ **Help**\ 
 \ *Definition to create Serial numbers for Products*\ 

SerNo Char Start Overwrite
--------------------------
\ **Description**\ 
 \ *Serial Number Start Indicator overwrite - default #*\ 
\ **Help**\ 
 \ *If not defined, the default character # is used*\ 

SerNo Char End Overwrite
------------------------
\ **Description**\ 
 \ *Serial Number End Indicator overwrite - default empty*\ 
\ **Help**\ 
 \ *If not defined, no character is used*\ 

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

Attribute Use
-------------
\ **Description**\ 
 \ *Attributes Used for the Product Attribute Set*\ 
\ **Help**\ 
 \ *Attributes and Attribute Values used for the product*\ 

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

Attribute Set
-------------
\ **Description**\ 
 \ *Product Attribute Set*\ 
\ **Help**\ 
 \ *Define Product Attribute Sets to add additional attributes and values to the product. You need to define a Attribute Set if you want to enable Serial and Lot Number tracking.*\ 

Attribute
---------
\ **Description**\ 
 \ *Product Attribute*\ 
\ **Help**\ 
 \ *Product Attribute like Color, Size*\ 

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

Exclude
-------
\ **Description**\ 
 \ *Exclude the ability to enter Attribute Sets*\ 
\ **Help**\ 
 \ *Create a record, if you want to exclude the ability to enter Product Attribute Set information. 
Note that the information is cached. To have effect you may have to re-login or reset cache.*\ 

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

Attribute Set
-------------
\ **Description**\ 
 \ *Product Attribute Set*\ 
\ **Help**\ 
 \ *Define Product Attribute Sets to add additional attributes and values to the product. You need to define a Attribute Set if you want to enable Serial and Lot Number tracking.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 
