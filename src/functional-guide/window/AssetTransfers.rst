
.. _window-assettransfers:

===============
Asset Transfers
===============

Process transfers of assets

Help
====
The Asset Transfer window allows you to transfer assets

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Transaction**\ 


Tabs
====

Step1 Select Asset
------------------
\ **Description**\ 
 \ *Select the asset to be transfered*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.
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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Parent Asset
------------

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Version No
----------
\ **Description**\ 
 \ *Version Number*\ 

Lot No
------
\ **Description**\ 
 \ *Lot number (alphanumeric)*\ 
\ **Help**\ 
 \ *The Lot Number indicates the specific lot that a product was part of.*\ 

Serial No
---------
\ **Description**\ 
 \ *Product Serial Number*\ 
\ **Help**\ 
 \ *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*\ 

A_QTY_Original
--------------

Fixed Asset Current Qty
-----------------------
\ **Description**\ 
 \ *Fixed Asset Current Quantity*\ 

Create Date
-----------

Revaluation Date
----------------

In Service Date
---------------
\ **Description**\ 
 \ *Date when Asset was put into service*\ 
\ **Help**\ 
 \ *The date when the asset was put into service - usually used as start date for depreciation.*\ 

Guarantee Date
--------------
\ **Description**\ 
 \ *Date when guarantee expires*\ 
\ **Help**\ 
 \ *Date when the normal guarantee or availability expires*\ 

Asset Group
-----------
\ **Description**\ 
 \ *Group of Assets*\ 
\ **Help**\ 
 \ *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*\ 

Owned
-----
\ **Description**\ 
 \ *The asset is owned by the organization*\ 
\ **Help**\ 
 \ *The asset may not be in possession, but the asset is legally owned by the organization*\ 

In Possession
-------------
\ **Description**\ 
 \ *The asset is in the possession of the organization*\ 
\ **Help**\ 
 \ *Assets which are not in possession are e.g. at Customer site and may or may not be owned by the company.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship from) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Location comment
----------------
\ **Description**\ 
 \ *Additional comments or remarks concerning the location*\ 

Depreciate
----------
\ **Description**\ 
 \ *The asset will be depreciated*\ 
\ **Help**\ 
 \ *The asset is used internally and will be depreciated*\ 

Fully depreciated
-----------------
\ **Description**\ 
 \ *The asset is fully depreciated*\ 
\ **Help**\ 
 \ *The asset costs are fully amortized.*\ 

Usable Life - Years
-------------------
\ **Description**\ 
 \ *Years of the usable life of the asset*\ 

Usable Life - Months
--------------------
\ **Description**\ 
 \ *Months of the usable life of the asset*\ 

Life use
--------
\ **Description**\ 
 \ *Units of use until the asset is not usable anymore*\ 
\ **Help**\ 
 \ *Life use and the actual use may be used to calculate the depreciation*\ 

Use units
---------
\ **Description**\ 
 \ *Currently used units of the assets*\ 

Asset Depreciation Date
-----------------------
\ **Description**\ 
 \ *Date of last depreciation*\ 
\ **Help**\ 
 \ *Date of the last deprecation, if the asset is used internally and depreciated.*\ 

Disposed
--------
\ **Description**\ 
 \ *The asset is disposed*\ 
\ **Help**\ 
 \ *The asset is no longer used and disposed*\ 

Asset Disposal Date
-------------------
\ **Description**\ 
 \ *Date when the asset is/was disposed*\ 

Process Now
-----------

Step2 Select Accounting Setup
-----------------------------
\ **Description**\ 
 \ *Enter accounting setup information*\ 

.. note::
    The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

A_Period_Start
--------------

A_Period_End
------------

Depreciation
------------

A_Depreciation_Manual_Amount
----------------------------

A_Depreciation_Manual_Period
----------------------------

A_Depreciation_Table_Header_ID
------------------------------

Variable Percent
----------------

A_Asset_Spread_ID
-----------------

Depreciation Method
-------------------

Convention Type
---------------

Asset Salvage Value
-------------------

Split Percent
-------------

Asset Acct
----------

Accumulated Depreciation Account
--------------------------------

Depreciation Account
--------------------

Disposal Revenue
----------------

Loss on Disposal
----------------

A_Reval_Cal_Method
------------------

Revaluation Cost Offset for Current Year
----------------------------------------

Revaluation Cost Offset for Prior Year
--------------------------------------

Revaluation Accumulated Depreciation Offset for Current Year
------------------------------------------------------------

Revaluation Accumulated Depreciation Offset for Prior Year
----------------------------------------------------------

Revaluation Expense Offs
------------------------

Step3 Process Transfers
-----------------------
\ **Description**\ 
 \ *Process asset transfers*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

A_Period_Start
--------------

A_Period_End
------------

Split Percent
-------------

Period
------
\ **Description**\ 
 \ *Period of the Calendar*\ 
\ **Help**\ 
 \ *The Period indicates an exclusive range of dates for a calendar.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

A_Asset_Acct_Str
----------------

New Asset Cost Acct
-------------------

Old Asset Cost Acct
-------------------

New Accum Depreciation Acct
---------------------------

A_Depreciation_Acct_Str
-----------------------

New Depreciation Exp Acct
-------------------------

Disposal Revenue Str
--------------------

New Disposal Revenue
--------------------

Disposal Loss Str
-----------------

New Disposal Loss
-----------------

A_Transfer_Balance
------------------

Is Transferred Balance
----------------------
\ **Description**\ 
 \ *Indicates whether the balance for a Fixed Asset is transferred to the new Fixed Asset or not*\ 

Process Now
-----------
