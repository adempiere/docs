
.. _functional-guide/window/importgljournal:

=================
Import GL Journal
=================

Import General Ledger Journals

Help
====
You way want to check the balance of the import with "Validate Only" before importing. 
Unbalanced Journals are imported; the handling is based on your settings for the posting process. The optional balance check checks the entire import, not individual batches and journals.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

General Ledger
--------------
\ **Description**\ 
 \ *Import General Ledger*\ 
\ **Help**\ 
 \ *A new Journal Batch is created, if the Batch Document No or accounting schema are different. A new Journal is created, if the Document No, Currency, Document Type, GL Category, Posting Type or Accounting type is different. You can also force the creation of a new Batch or Jornal by selecting the creat new flag.
Please note that there are three Organization Fields: The Document Organization is the owner of the document and set directly or per parameter default. The Organization is part of the accounting key and only required id no Valid Account Comination is specified; If not defined it is derived from the Document Organization. The Transaction Organization is part of the account combination.
The optional balance check applies to the entire import, not for individual batches or journals.
* The document numbers will be overwritten if the document type is not set to manual sequences.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import GL Journal
-----------------
\ **Description**\ 
 \ *Import General Ledger Journal*\ 

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

Client Key
----------
\ **Description**\ 
 \ *Key of the Client*\ 

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Document Org
------------
\ **Description**\ 
 \ *Document Organization (independent from account organization)*\ 

Batch Document No
-----------------
\ **Description**\ 
 \ *Document Number of the Batch*\ 

Create New Batch
----------------
\ **Description**\ 
 \ *If selected a new batch is created*\ 
\ **Help**\ 
 \ *Note that the balance check does not check that individual batches are balanced.*\ 

Batch Description
-----------------
\ **Description**\ 
 \ *Description of the Batch*\ 

Journal
-------
\ **Description**\ 
 \ *General Ledger Journal*\ 
\ **Help**\ 
 \ *The General Ledger Journal identifies a group of journal lines which represent a logical business transaction*\ 

Journal Document No
-------------------
\ **Description**\ 
 \ *Document number of the Journal*\ 

Create New Journal
------------------
\ **Description**\ 
 \ *If selected a new journal within the batch is created*\ 
\ **Help**\ 
 \ *Note that the balance check does not check that individual journals are balanced.*\ 

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

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Budget
------
\ **Description**\ 
 \ *General Ledger Budget*\ 
\ **Help**\ 
 \ *The General Ledger Budget identifies a user defined budget.  These can be used in reporting as a comparison against your actual amounts.*\ 

Document Type Name
------------------
\ **Description**\ 
 \ *Name of the Document Type*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Category Name
-------------
\ **Description**\ 
 \ *Name of the Category*\ 

GL Category
-----------
\ **Description**\ 
 \ *General Ledger Category*\ 
\ **Help**\ 
 \ *The General Ledger Category is an optional, user defined method of grouping journal lines.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Period
------
\ **Description**\ 
 \ *Period of the Calendar*\ 
\ **Help**\ 
 \ *The Period indicates an exclusive range of dates for a calendar.*\ 

Journal Line
------------
\ **Description**\ 
 \ *General Ledger Journal Line*\ 
\ **Help**\ 
 \ *The General Ledger Journal Line identifies a single transaction in a journal.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Source Debit
------------
\ **Description**\ 
 \ *Source Debit Amount*\ 
\ **Help**\ 
 \ *The Source Debit Amount indicates the credit amount for this line in the source currency.*\ 

Source Credit
-------------
\ **Description**\ 
 \ *Source Credit Amount*\ 
\ **Help**\ 
 \ *The Source Credit Amount indicates the credit amount for this line in the source currency.*\ 

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

Currency Type Key
-----------------
\ **Description**\ 
 \ *Key value for the Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The date type key for the conversion of foreign currency transactions*\ 

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

Rate
----
\ **Description**\ 
 \ *Currency Conversion Rate*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate indicates the rate to use when converting the source currency to the accounting currency*\ 

Accounted Debit
---------------
\ **Description**\ 
 \ *Accounted Debit Amount*\ 
\ **Help**\ 
 \ *The Account Debit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

Accounted Credit
----------------
\ **Description**\ 
 \ *Accounted Credit Amount*\ 
\ **Help**\ 
 \ *The Account Credit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Alias
-----
\ **Description**\ 
 \ *Defines an alternate method of indicating an account combination.*\ 
\ **Help**\ 
 \ *The Alias field allows you to define a alternate method for referring to a full account combination.  For example, the Account Receivable Account for Garden World may be aliased as GW_AR.*\ 

Combination
-----------
\ **Description**\ 
 \ *Valid Account Combination*\ 
\ **Help**\ 
 \ *The Combination identifies a valid combination of element which represent a GL account.*\ 

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

UPC/EAN
-------
\ **Description**\ 
 \ *Bar Code (Universal Product Code or its superset European Article Number)*\ 
\ **Help**\ 
 \ *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*\ 

SKU
---
\ **Description**\ 
 \ *Stock Keeping Unit*\ 
\ **Help**\ 
 \ *The SKU indicates a user defined stock keeping unit.  It may be used for an additional bar code symbols or your own schema.*\ 

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

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

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

Import Journal
--------------
\ **Description**\ 
 \ *Import General Ledger Batch/Journal/Line*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
