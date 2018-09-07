
.. _functional-guide/window/window-importaccount:

==============
Import Account
==============

Import Natural Account Values

Help
====
The Import Natural Account Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Account
--------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Account
--------------
\ **Description**\ 
 \ *Import Account Value*\ 

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Account Element
---------------
\ **Description**\ 
 \ *Account Element*\ 
\ **Help**\ 
 \ *Account Elements can be natural accounts or user defined values.*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

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

Element Name
------------
\ **Description**\ 
 \ *Name of the Element*\ 

Element
-------
\ **Description**\ 
 \ *Accounting Element*\ 
\ **Help**\ 
 \ *The Account Element uniquely identifies an Account Type.  These are commonly known as a Chart of Accounts.*\ 

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

Account Type
------------
\ **Description**\ 
 \ *Indicates the type of account*\ 
\ **Help**\ 
 \ *Valid account types are A - Asset, E - Expense, L - Liability, O- Owner's Equity, R -Revenue and M- Memo.  The account type is used to determine what taxes, if any are applicable, validating payables and receivables for business partners.  Note:  Memo account amounts are ignored when checking for balancing*\ 

Account Sign
------------
\ **Description**\ 
 \ *Indicates the Natural Sign of the Account as a Debit or Credit*\ 
\ **Help**\ 
 \ *Indicates if the expected balance for this account should be a Debit or a Credit. If set to Natural, the account sign for an asset or expense account is Debit Sign (i.e. negative if a credit balance).*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Parent Key
----------
\ **Description**\ 
 \ *Key if the Parent*\ 

Parent Account
--------------
\ **Description**\ 
 \ *The parent (summary) account*\ 

Post Actual
-----------
\ **Description**\ 
 \ *Actual Values can be posted*\ 
\ **Help**\ 
 \ *The Post Actual indicates if actual values can be posted to this element value.*\ 

Post Budget
-----------
\ **Description**\ 
 \ *Budget values can be posted*\ 
\ **Help**\ 
 \ *The Post Budget indicates if budget values can be posted to this element value.*\ 

Post Statistical
----------------
\ **Description**\ 
 \ *Post statistical quantities to this account?*\ 

Post Encumbrance
----------------
\ **Description**\ 
 \ *Post commitments to this account*\ 

Document Controlled
-------------------
\ **Description**\ 
 \ *Control account - If an account is controlled by a document, you cannot post manually to it*\ 

Default Account
---------------
\ **Description**\ 
 \ *Name of the Default Account Column*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Charge Name
-----------
\ **Description**\ 
 \ *Name of the Charge*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Tax Category Name
-----------------
\ **Description**\ 
 \ *Name of tax category*\ 

Tax Category
------------
\ **Description**\ 
 \ *Tax Category*\ 
\ **Help**\ 
 \ *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*\ 

Import Accounts
---------------
\ **Description**\ 
 \ *Import Natural Accounts*\ 
\ **Help**\ 
 \ *Import accounts and their hierarchies and optional update the default accounts.  
Updating the Default Accounts changes the natural account segment of the used account, e.g. account 01-240 becomes 01-300).  If you create a new combination, the old account (e.g. 01-240) will remain, otherwise replaced.
If you select this, make sure that you not multiple default accounts using one natural account and HAVE A BACKUP !!
The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
