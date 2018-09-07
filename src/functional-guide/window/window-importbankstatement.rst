
.. _functional-guide/window/window-importbankstatement:

=====================
Import Bank Statement
=====================

Import Bank Statements

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Bank Statement
--------------
\ **Description**\ 
 \ *Import Bank Statement*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Bank Statement
---------------------
\ **Description**\ 
 \ *Import of the Bank Statement*\ 

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Bank Statement
--------------
\ **Description**\ 
 \ *Bank Statement of account*\ 
\ **Help**\ 
 \ *The Bank Statement identifies a unique Bank Statement for a defined time period.  The statement defines all transactions that occurred*\ 

Bank statement line
-------------------
\ **Description**\ 
 \ *Line on a statement from this Bank*\ 
\ **Help**\ 
 \ *The Bank Statement Line identifies a unique transaction (Payment, Withdrawal, Charge) for the defined time period at this Bank.*\ 

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

Routing No
----------
\ **Description**\ 
 \ *Bank Routing Number*\ 
\ **Help**\ 
 \ *The Bank Routing Number (ABA Number) identifies a legal Bank.  It is used in routing checks and electronic transactions.*\ 

Bank Account No
---------------
\ **Description**\ 
 \ *Bank Account Number*\ 

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

Statement date
--------------
\ **Description**\ 
 \ *Date of the statement*\ 
\ **Help**\ 
 \ *The Statement Date field defines the date of the statement.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

Line Description
----------------
\ **Description**\ 
 \ *Description of the Line*\ 

Statement Line Date
-------------------
\ **Description**\ 
 \ *Date of the Statement Line*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Effective date
--------------
\ **Description**\ 
 \ *Date when money is available*\ 
\ **Help**\ 
 \ *The Effective Date indicates the date that money is available from the bank.*\ 

Reversal
--------
\ **Description**\ 
 \ *This is a reversing transaction*\ 
\ **Help**\ 
 \ *The Reversal check box indicates if this is a reversal of a prior transaction.*\ 

ISO Currency Code
-----------------
\ **Description**\ 
 \ *Three letter ISO 4217 Code of the Currency*\ 
\ **Help**\ 
 \ *For details - http://www.unece.org/trade/rec/rec09en.htm*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Transaction Amount
------------------
\ **Description**\ 
 \ *Amount of a transaction*\ 
\ **Help**\ 
 \ *The Transaction Amount indicates the amount for a single transaction.*\ 

Statement amount
----------------
\ **Description**\ 
 \ *Statement Amount*\ 
\ **Help**\ 
 \ *The Statement Amount indicates the amount of a single statement line.*\ 

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

Interest Amount
---------------
\ **Description**\ 
 \ *Interest Amount*\ 
\ **Help**\ 
 \ *The Interest Amount indicates any interest charged or received on a Bank Statement.*\ 

Charge amount
-------------
\ **Description**\ 
 \ *Charge Amount*\ 
\ **Help**\ 
 \ *The Charge Amount indicates the amount for an additional charge.*\ 

Memo
----
\ **Description**\ 
 \ *Memo Text*\ 

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

Invoice Document No
-------------------
\ **Description**\ 
 \ *Document Number of the Invoice*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Payment Document No
-------------------
\ **Description**\ 
 \ *Document number of the Payment*\ 

Payment
-------
\ **Description**\ 
 \ *Payment identifier*\ 
\ **Help**\ 
 \ *The Payment is a unique identifier of this payment.*\ 

Transaction Type
----------------
\ **Description**\ 
 \ *Type of credit card transaction*\ 
\ **Help**\ 
 \ *The Transaction Type indicates the type of transaction to be submitted to the Credit Card Company.*\ 

Match Bank Statement
--------------------
\ **Description**\ 
 \ *Match Bank Statement Info to Business Partners, Invoices and Payments*\ 

Import Bank Statement
---------------------
\ **Description**\ 
 \ *Import Bank Statement*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Create Payment
--------------
\ **Description**\ 
 \ *Create Payment from Bank Statement Info*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

EFT Statement Reference
-----------------------
\ **Description**\ 
 \ *Electronic Funds Transfer Statement Reference*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Statement Date
------------------
\ **Description**\ 
 \ *Electronic Funds Transfer Statement Date*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Trx ID
----------
\ **Description**\ 
 \ *Electronic Funds Transfer Transaction ID*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Trx Type
------------
\ **Description**\ 
 \ *Electronic Funds Transfer Transaction Type*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Check No
------------
\ **Description**\ 
 \ *Electronic Funds Transfer Check No*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Reference
-------------
\ **Description**\ 
 \ *Electronic Funds Transfer Reference*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Memo
--------
\ **Description**\ 
 \ *Electronic Funds Transfer Memo*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Payee
---------
\ **Description**\ 
 \ *Electronic Funds Transfer Payee information*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Payee Account
-----------------
\ **Description**\ 
 \ *Electronic Funds Transfer Payee Account Information*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Statement Line Date
-----------------------
\ **Description**\ 
 \ *Electronic Funds Transfer Statement Line Date*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Effective Date
------------------
\ **Description**\ 
 \ *Electronic Funds Transfer Valuta (effective) Date*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Currency
------------
\ **Description**\ 
 \ *Electronic Funds Transfer Currency*\ 
\ **Help**\ 
 \ *Information from EFT media*\ 

EFT Amount
----------
\ **Description**\ 
 \ *Electronic Funds Transfer Amount*\ 
