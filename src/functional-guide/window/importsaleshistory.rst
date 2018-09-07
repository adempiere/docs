
.. _functional-guide/window/importsaleshistory:

====================
Import Sales History
====================

This process allows to import the sales statistics by using a predefined import format,  inside the application.

Help
====
The parameters are the default values to import the records.


The maintained information inside the sales statistic are: the business partner data, product, sales quantities, prices, costs and reference values.


The sales historical information is used to realize the forecast calculus and to get sales statistics reports.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Sales Histroy
--------------------
\ **Description**\ 
 \ *This process allows to import the sales statistics by using a predefined import format,  inside the application.*\ 
\ **Help**\ 
 \ *The parameters are the default values to import the records.


The maintained information inside the sales statistic are: the business partner data, product, sales quantities, prices, costs and reference values.


The sales historical information is used to realize the forecast calculus and to get sales statistics reports.*\ 

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

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

Sales History
-------------
\ **Description**\ 
 \ *Sales History for statistics and forecast*\ 

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

Org Key
-------
\ **Description**\ 
 \ *Key of the Organization*\ 

Business Partner Key
--------------------
\ **Description**\ 
 \ *Key of the Business Partner*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Group Key
---------
\ **Description**\ 
 \ *Business Partner Group Key*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Sales Representative
--------------------

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

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

Category Name
-------------
\ **Description**\ 
 \ *Name of the Category*\ 

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

Date Invoiced
-------------
\ **Description**\ 
 \ *Date printed on Invoice*\ 
\ **Help**\ 
 \ *The Date Invoice indicates the date printed on the invoice.*\ 

Warehouse Key
-------------
\ **Description**\ 
 \ *Key of the Warehouse*\ 
\ **Help**\ 
 \ *Key to identify the Warehouse*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Total Invoice Quantity
----------------------
\ **Description**\ 
 \ *Cumulative total lifetime invoice quantity*\ 
\ **Help**\ 
 \ *The cumulative total lifetime invoice quantity is used to calculate the total average price*\ 

Cost Value
----------
\ **Description**\ 
 \ *Value with Cost*\ 

Total Invoice Cost
------------------
\ **Description**\ 
 \ *Total lifetime invoice costs*\ 

Price Invoiced
--------------
\ **Description**\ 
 \ *The priced invoiced to the customer (in the currency of the customer's AR price list) - 0 for default price*\ 
\ **Help**\ 
 \ *The invoiced price is derived from the Invoice Price entered and can be overwritten.  If the price is 0, the default price on the customer's invoice is used.*\ 

Total Invoice Amount
--------------------
\ **Description**\ 
 \ *Cumulative total lifetime invoice amount*\ 
\ **Help**\ 
 \ *The cumulative total lifetime invoice amount is used to calculate the total average price*\ 

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Activity Value
--------------

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Campaign Value
--------------

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Project
-------
\ **Description**\ 
 \ *Name of the Project*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Project Phase
-------------
\ **Description**\ 
 \ *Name of the Project Phase*\ 

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Project Task
------------
\ **Description**\ 
 \ *Actual Project Task in a Phase*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Import Sales History
--------------------
\ **Description**\ 
 \ *Imports Sales History from a file into the application*\ 
\ **Help**\ 
 \ *Import Sales History will bring a file of sales history, in a predefined format into the application. The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
