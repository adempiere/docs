
.. _functional-guide/window/assetgroup:

===========
Asset Group
===========

Group of Assets

Help
====
The group of assets determines default accounts.  If a asset group is selected in the product category, assets are created when delivering the asset.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Asset Group
-----------
\ **Description**\ 
 \ *Group of Assets*\ 
\ **Help**\ 
 \ *The group of assets determines default accounts.  If a asset group is selected in the product category, assets are created when delivering the asset.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

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

Owned
-----
\ **Description**\ 
 \ *The asset is owned by the organization*\ 
\ **Help**\ 
 \ *The asset may not be in possession, but the asset is legally owned by the organization*\ 

Depreciate
----------
\ **Description**\ 
 \ *The asset will be depreciated*\ 
\ **Help**\ 
 \ *The asset is used internally and will be depreciated*\ 

One Asset Per UOM
-----------------
\ **Description**\ 
 \ *Create one asset per UOM*\ 
\ **Help**\ 
 \ *If selected, one asset per UOM is created, otherwise one asset with the quantity received/shipped.  If you have multiple lines, one asset is created per line.*\ 

Is a Fixed Asset
----------------
\ **Description**\ 
 \ *Indicates whether this group will be a Fixed Asset*\ 

Group Account
-------------
\ **Description**\ 
 \ *Setup for Group Accounts*\ 

.. note::
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

Asset Group
-----------
\ **Description**\ 
 \ *Group of Assets*\ 
\ **Help**\ 
 \ *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*\ 

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

Depreciation
------------

Depreciation (fiscal)
---------------------

Usable Life - Years
-------------------
\ **Description**\ 
 \ *Years of the usable life of the asset*\ 

Use Life - Years (fiscal)
-------------------------

Usable Life - Months
--------------------
\ **Description**\ 
 \ *Months of the usable life of the asset*\ 

Use Life - Months (fiscal)
--------------------------

Asset Acct
----------

Accumulated Depreciation Account
--------------------------------

Depreciation Account
--------------------

Disposal Revenue Acct
---------------------

Disposal Loss Acct
------------------
