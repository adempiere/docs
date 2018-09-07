
.. _window-cashjournal:

============
Cash Journal
============

Cash transactions

Help
====
The Cash Journal Window is used to record disbursements from and receipts to Petty Cash

Window Type
-----------
\ **Transaction**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Cash Journal
------------
\ **Description**\ 
 \ *Cash Journal*\ 
\ **Help**\ 
 \ *The Cash Journal Tab defines the parameters for this journal.*\ 

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

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Cash Book
---------
\ **Description**\ 
 \ *Cash Book for recording petty cash transactions*\ 
\ **Help**\ 
 \ *The Cash Book identifies a unique cash book.  The cash book is used to record cash transactions.*\ 

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

Statement date
--------------
\ **Description**\ 
 \ *Date of the statement*\ 
\ **Help**\ 
 \ *The Statement Date field defines the date of the statement.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

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

Beginning Balance
-----------------
\ **Description**\ 
 \ *Balance prior to any transactions*\ 
\ **Help**\ 
 \ *The Beginning Balance is the balance prior to making any adjustments for payments or disbursements.*\ 

Approved
--------
\ **Description**\ 
 \ *Indicates if this document requires approval*\ 
\ **Help**\ 
 \ *The Approved checkbox indicates if this document requires approval before it can be processed.*\ 

Statement difference
--------------------
\ **Description**\ 
 \ *Difference between statement ending balance and actual ending balance*\ 
\ **Help**\ 
 \ *The Statement Difference reflects the difference between the Statement Ending Balance and the Actual Ending Balance.*\ 

Ending balance
--------------
\ **Description**\ 
 \ *Ending  or closing balance*\ 
\ **Help**\ 
 \ *The Ending Balance is the result of adjusting the Beginning Balance by any payments or disbursements.*\ 

Document Status
---------------
\ **Description**\ 
 \ *The current status of the document*\ 
\ **Help**\ 
 \ *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*\ 

Process Cash
------------

Posted
------
\ **Description**\ 
 \ *Posting status*\ 
\ **Help**\ 
 \ *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*\ 

Cash Line
---------
\ **Description**\ 
 \ *Cash Line*\ 
\ **Help**\ 
 \ *The Cash Line Tab defines the individual lines for this journal.*\ 

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

Cash Journal
------------
\ **Description**\ 
 \ *Cash Journal*\ 
\ **Help**\ 
 \ *The Cash Journal uniquely identifies a Cash Journal.  The Cash Journal will record transactions for the cash bank account*\ 

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

Cash Type
---------
\ **Description**\ 
 \ *Source of Cash*\ 
\ **Help**\ 
 \ *The Cash Type indicates the source for this Cash Journal Line.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Amount
------
\ **Description**\ 
 \ *Amount in a defined currency*\ 
\ **Help**\ 
 \ *The Amount indicates the amount for this document line.*\ 

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Discount Amount
---------------
\ **Description**\ 
 \ *Calculated amount of discount*\ 
\ **Help**\ 
 \ *The Discount Amount indicates the discount amount for a document or line.*\ 

Write-off Amount
----------------
\ **Description**\ 
 \ *Amount to write-off*\ 
\ **Help**\ 
 \ *The Write Off Amount indicates the amount to be written off as uncollectible.*\ 
