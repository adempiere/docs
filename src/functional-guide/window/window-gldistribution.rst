
.. _functional-guide/window/window-gldistribution:

===============
GL Distribution
===============

General Ledger Distribution

Help
====
If the account combination criteria of the Distribution is met, the posting to the account combination is replaced by the account combinations of the distribution lines.  The distribution is a one-step operation based on the percentage of the lines.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Distribution
------------
\ **Description**\ 
 \ *General Ledger Distribution*\ 
\ **Help**\ 
 \ *If the account combination criteria of the Distribution is met, the posting to the account combination is replaced by the account combinations of the distribution lines.  
The distribution is prorated based on the percentage of the lines. If the total percent is less then 100 and one line is 0 (null), it gets the remainder.  If there is no line with 0, any rounding is adjusted in the line with the biggest amount.*\ 

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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Create Reversal
---------------
\ **Description**\ 
 \ *Indicates that reversal movement will be created, if disabled the original movement will be deleted.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 

Any Organization
----------------
\ **Description**\ 
 \ *Match any value of the Organization segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Any Account
-----------
\ **Description**\ 
 \ *Match any value of the Account segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Any Activity
------------
\ **Description**\ 
 \ *Match any value of the Activity segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Any Product
-----------
\ **Description**\ 
 \ *Match any value of the Product segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Any Bus.Partner
---------------
\ **Description**\ 
 \ *Match any value of the Business Partner segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Any Project
-----------
\ **Description**\ 
 \ *Match any value of the Project segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Any Campaign
------------
\ **Description**\ 
 \ *Match any value of the Campaign segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Any Location From
-----------------
\ **Description**\ 
 \ *Match any value of the Location From segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Location From
-------------
\ **Description**\ 
 \ *Location that inventory was moved from*\ 
\ **Help**\ 
 \ *The Location From indicates the location that a product was moved from.*\ 

Any Location To
---------------
\ **Description**\ 
 \ *Match any value of the Location To segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Location To
-----------
\ **Description**\ 
 \ *Location that inventory was moved to*\ 
\ **Help**\ 
 \ *The Location To indicates the location that a product was moved to.*\ 

Any Sales Region
----------------
\ **Description**\ 
 \ *Match any value of the Sales Region segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Any Trx Organization
--------------------
\ **Description**\ 
 \ *Match any value of the Transaction Organization segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Any User 1
----------
\ **Description**\ 
 \ *Match any value of the User 1 segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Any User 2
----------
\ **Description**\ 
 \ *Match any value of the User 2 segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Any User 3
----------
\ **Description**\ 
 \ *Match any value of the User 3 segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Any User 4
----------
\ **Description**\ 
 \ *Match any value of the User 4 segment*\ 
\ **Help**\ 
 \ *If selected, any value of the account segment will match. If not selected, but no value of the accounting segment is selected, the matched value must be null (i.e. not defined).*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Total Percent
-------------
\ **Description**\ 
 \ *Sum of the Percent details*\ 

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

GL Distribution Copy From
-------------------------
\ **Description**\ 
 \ *Copy from GL Distribution to other GL Distribution.*\ 

Verify
------
\ **Description**\ 
 \ *Verify GL Distribution*\ 

Line
----
\ **Description**\ 
 \ *General Ledger Distribution Target Line*\ 
\ **Help**\ 
 \ *If the account combination criteria of the Distribution is met, the posting to the account combination is replaced by the account combinations of the distribution lines.  The distribution is prorated based on the perecent value of the lines. A Percent value of 0 (null) indicates the remainder to 100. There can only be one line with 0 percent.*\ 

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

GL Distribution
---------------
\ **Description**\ 
 \ *General Ledger Distribution*\ 
\ **Help**\ 
 \ *If the account combination criteria of the Distribution is met, the posting to the account combination is replaced by the account combinations of the distribution lines.  The distribution is prorated based on the ratio of the lines. The distribution must be valid to be used.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Percent
-------
\ **Description**\ 
 \ *Percentage*\ 
\ **Help**\ 
 \ *The Percent indicates the percentage used.*\ 

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

Invert Account Sign
-------------------
\ **Description**\ 
 \ *Enable invert account sign when a GL Distribution rule applied*\ 
\ **Help**\ 
 \ *for instance:

Original:

Debit Expense 1000
Credit Account Payable 1000 

Result :

Debit Account Payable 1000 
Credit Expense 1000*\ 

Overwrite Posting Type
----------------------
\ **Description**\ 
 \ *Overwrite the posting type with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Overwrite Organization
----------------------
\ **Description**\ 
 \ *Overwrite the account segment Organization with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Overwrite Account
-----------------
\ **Description**\ 
 \ *Overwrite the account segment Account with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Overwrite Activity
------------------
\ **Description**\ 
 \ *Overwrite the account segment Activity with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Overwrite Product
-----------------
\ **Description**\ 
 \ *Overwrite the account segment Product with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Overwrite Bus.Partner
---------------------
\ **Description**\ 
 \ *Overwrite the account segment Business Partner with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Overwrite Project
-----------------
\ **Description**\ 
 \ *Overwrite the account segment Project with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Overwrite Campaign
------------------
\ **Description**\ 
 \ *Overwrite the account segment Campaign with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Overwrite Location From
-----------------------
\ **Description**\ 
 \ *Overwrite the account segment Location From with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Location From
-------------
\ **Description**\ 
 \ *Location that inventory was moved from*\ 
\ **Help**\ 
 \ *The Location From indicates the location that a product was moved from.*\ 

Overwrite Location To
---------------------
\ **Description**\ 
 \ *Overwrite the account segment Location From with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Location To
-----------
\ **Description**\ 
 \ *Location that inventory was moved to*\ 
\ **Help**\ 
 \ *The Location To indicates the location that a product was moved to.*\ 

Overwrite Sales Region
----------------------
\ **Description**\ 
 \ *Overwrite the account segment Sales Region with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Overwrite Trx Organuzation
--------------------------
\ **Description**\ 
 \ *Overwrite the account segment Transaction Organization with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

Overwrite User1
---------------
\ **Description**\ 
 \ *Overwrite the account segment User 1 with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Overwrite User2
---------------
\ **Description**\ 
 \ *Overwrite the account segment User 2 with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Overwrite User3
---------------
\ **Description**\ 
 \ *Overwrite the account segment User 3 with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Overwrite User4
---------------
\ **Description**\ 
 \ *Overwrite the account segment User 4 with the value specified*\ 
\ **Help**\ 
 \ *If not overwritten, the value of the original account combination is used. If selected, but not specified, the segment is set to null.*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 
