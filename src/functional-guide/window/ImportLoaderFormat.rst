
.. _window-importloaderformat:

====================
Import Loader Format
====================

Maintain Import Loader Formats

Help
====
The Import Loader Format Window is used for defining the file layout for product information which will be imported.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Format
-------------

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Classname
---------
\ **Description**\ 
 \ *Java Classname*\ 
\ **Help**\ 
 \ *The Classname identifies the Java classname used by this report or process.*\ 

Format
------
\ **Description**\ 
 \ *Format of the data*\ 
\ **Help**\ 
 \ *The Format is a drop down list box for selecting the format type (text, tab delimited, XML, etc) of the file to be imported*\ 

Separator Character
-------------------

Copy Lines
----------
\ **Description**\ 
 \ *Copy Lines from other Import Format*\ 

Format Field
------------
\ **Description**\ 
 \ *Maintain Format Fields*\ 
\ **Help**\ 
 \ *Define the individual field based on the table definition.  Please note that you have to make sure that a Constant has the correct  SQL data type (i.e. if it is a 'string', you need to enclose it like 'this').
Product mapping (for details see documentation):
<pre>
H_Item => Value
H_ItemDesc => Name / Description
H_ItemDefn => Help
H_ItemType => ProductCategory
H_PartnrID => Value of Business Partner
H_Commodity1 => Vendor Product No
H_Commodity2 => SKU
H_ItemClass => Classification (A,B,C..)
V_OperAmt_T_Cur => Currency
V_OperAmt_T => Price 
</pre>*\ 

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

Import Format
-------------

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Data Type
---------
\ **Description**\ 
 \ *Type of data*\ 

Data Format
-----------
\ **Description**\ 
 \ *Format String in Java Notation, e.g. ddMMyy*\ 
\ **Help**\ 
 \ *The Date Format indicates how dates are defined on the record to be imported.  It must be in Java Notation*\ 

Start No
--------
\ **Description**\ 
 \ *Starting number/position*\ 
\ **Help**\ 
 \ *The Start Number indicates the starting position in the line or field number in the line*\ 

End No
------

Decimal Point
-------------
\ **Description**\ 
 \ *Decimal Point in the data file - if any*\ 

Divide by 100
-------------
\ **Description**\ 
 \ *Divide number by 100 to get correct amount*\ 

Constant Value
--------------
\ **Description**\ 
 \ *Constant value*\ 

Default Value
-------------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *Default value to be used if import field is empty.*\ 

Callout
-------
\ **Description**\ 
 \ *Fully qualified class names and method - separated by semicolons*\ 
\ **Help**\ 
 \ *A Callout allow you to create Java extensions to perform certain tasks always after a value changed. Callouts should not be used for validation but consequences of a user selecting a certain value.
The callout is a Java class implementing org.compiere.model.Callout and a method name to call.  Example: "org.compiere.model.CalloutRequest.copyText" instantiates the class "CalloutRequest" and calls the method "copyText". You can have multiple callouts by separating them via a semicolon*\ 

Script
------
\ **Description**\ 
 \ *Dynamic Java Language Script to calculate result*\ 
\ **Help**\ 
 \ *Use Java language constructs to define the result of the calculation*\ 
