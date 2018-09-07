
.. _functional-guide/window/window-importbudget:

=============
Import Budget
=============

Import Budget

Help
====
The Import Budget Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Budget
-------------

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

I_Budget_ID
-----------

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

Journal Batch
-------------
\ **Description**\ 
 \ *General Ledger Journal Batch*\ 
\ **Help**\ 
 \ *The General Ledger Journal Batch identifies a group of journals to be processed as a group.*\ 

Batch Document No
-----------------
\ **Description**\ 
 \ *Document Number of the Batch*\ 

Journal
-------
\ **Description**\ 
 \ *General Ledger Journal*\ 
\ **Help**\ 
 \ *The General Ledger Journal identifies a group of journal lines which represent a logical business transaction*\ 

Journal Line
------------
\ **Description**\ 
 \ *General Ledger Journal Line*\ 
\ **Help**\ 
 \ *The General Ledger Journal Line identifies a single transaction in a journal.*\ 

Journal Line Description
------------------------

Org Key
-------
\ **Description**\ 
 \ *Key of the Organization*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Account Schema Name
-------------------
\ **Description**\ 
 \ *Name of the Accounting Schema*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Budget Code
-----------

Budget
------
\ **Description**\ 
 \ *General Ledger Budget*\ 
\ **Help**\ 
 \ *The General Ledger Budget identifies a user defined budget.  These can be used in reporting as a comparison against your actual amounts.*\ 

Combination
-----------
\ **Description**\ 
 \ *Valid Account Combination*\ 
\ **Help**\ 
 \ *The Combination identifies a valid combination of element which represent a GL account.*\ 

Account Key
-----------
\ **Description**\ 
 \ *Key of Account Element*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Sub Account Value
-----------------
\ **Description**\ 
 \ *Sub account Value*\ 
\ **Help**\ 
 \ *The Element Value (e.g. Account) may have optional sub accounts Value for further detail. The sub account is dependent on the value of the account, so a further specification. If the sub-accounts are more or less the same, consider using another accounting dimension.*\ 

Sub Account
-----------
\ **Description**\ 
 \ *Sub account for Element Value*\ 
\ **Help**\ 
 \ *The Element Value (e.g. Account) may have optional sub accounts for further detail. The sub account is dependent on the value of the account, so a further specification. If the sub-accounts are more or less the same, consider using another accounting dimension.*\ 

Activity Value
--------------

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

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

Project Key
-----------
\ **Description**\ 
 \ *Key of the Project*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Trx Org Key
-----------
\ **Description**\ 
 \ *Key of the Transaction Organization*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Campaign Value
--------------

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

User List Value 1
-----------------
\ **Description**\ 
 \ *User value defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List Value 2
-----------------
\ **Description**\ 
 \ *User value defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List Value 3
-----------------
\ **Description**\ 
 \ *User value defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List Value 4
-----------------
\ **Description**\ 
 \ *User value defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User Element Value 1
--------------------
\ **Description**\ 
 \ *User Element Value 1 defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

User Element 1
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

User Element Value 2
--------------------
\ **Description**\ 
 \ *User Element Value 2 defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

User Element 2
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Sales Region Value
------------------

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Location From
-------------
\ **Description**\ 
 \ *Location that inventory was moved from*\ 
\ **Help**\ 
 \ *The Location From indicates the location that a product was moved from.*\ 

Location To
-----------
\ **Description**\ 
 \ *Location that inventory was moved to*\ 
\ **Help**\ 
 \ *The Location To indicates the location that a product was moved to.*\ 

Asset Value
-----------

Fixed Asset
-----------
\ **Description**\ 
 \ *Fixed Asset used internally or by customers*\ 
\ **Help**\ 
 \ *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*\ 

Month_0_Amt
-----------

Month_1_Amt
-----------

Month_2_Amt
-----------

Month_3_Amt
-----------

Month_4_Amt
-----------

Month_5_Amt
-----------

Month_6_Amt
-----------

Month_7_Amt
-----------

Month_8_Amt
-----------

Month_9_Amt
-----------

Month_10_Amt
------------

Month_11_Amt
------------

Month_0_Qty
-----------

Month_1_Qty
-----------

Month_2_Qty
-----------

Month_3_Qty
-----------

Month_4_Qty
-----------

Month_5_Qty
-----------

Month_6_Qty
-----------

Month_7_Qty
-----------

Month_8_Qty
-----------

Month_9_Qty
-----------

Month_10_Qty
------------

Month_11_Qty
------------

Import Budget
-------------
\ **Description**\ 
 \ *Import Budget*\ 
\ **Help**\ 
 \ *This process allows importing the budget for accounting*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
