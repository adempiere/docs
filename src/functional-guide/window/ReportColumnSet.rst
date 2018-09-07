
.. _window-reportcolumnset:

=================
Report Column Set
=================

Maintain Financial Report Column Sets

Help
====
The Report Column Set defines what data is printed in the columns of a report.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Report Column Set
-----------------
\ **Description**\ 
 \ *Maintain Financial Report Column Sets*\ 
\ **Help**\ 
 \ *Column Sets are the combination of Columns to be included in a Financial Report*\ 

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

Copy Columns
------------
\ **Description**\ 
 \ *Copy Report Columns from other Column Set*\ 
\ **Help**\ 
 \ *Copy columns at the end of this Column Set. Please note that you need to re-set the calculation operands.*\ 

Sequence
--------
\ **Description**\ 
 \ *Sequence of Column*\ 

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Report Column
-------------
\ **Description**\ 
 \ *Maintain Financial Report Column*\ 
\ **Help**\ 
 \ *A column represents a column in a Financial Report*\ 

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

Report Column Set
-----------------
\ **Description**\ 
 \ *Collection of Columns for Report*\ 
\ **Help**\ 
 \ *The Report Column Set identifies the columns used in a Report.*\ 

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

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Column Type
-----------

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

Amount Type
-----------
\ **Description**\ 
 \ *PA Amount Type for reporting*\ 
\ **Help**\ 
 \ *The amount type to report on: Quantity, Credit Only, Debit Only, Balance (expected sign) or Balance (accounted sign). "Expected sign" adjusts the sign of the result based on the Account Type and Expected Sign of each Account Element, whereas "accounted sign" always returns DR-CR.*\ 

Amount Type
-----------
\ **Description**\ 
 \ *Type of amount to report*\ 
\ **Help**\ 
 \ *You can choose between the total and period amounts as well as the balance or just the debit/credit amounts.*\ 

Period Type
-----------
\ **Description**\ 
 \ *PA Period Type*\ 
\ **Help**\ 
 \ *The Period Type to report on: Period, Year, Total or Natural. Natural = Year for P & L accounts, Total for Balance Sheet accounts.*\ 

Currency Type
-------------

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Adhoc Conversion
----------------
\ **Description**\ 
 \ *Perform conversion for all amounts to currency*\ 
\ **Help**\ 
 \ *If a currency is selected, only this currency will be reported. If adhoc conversion is selected, all currencies are converted to the defined currency*\ 

Relative Period
---------------
\ **Description**\ 
 \ *Period offset (0 is current)*\ 

Relative Period To
------------------
\ **Description**\ 
 \ *Period offset (0 is current)*\ 

Calculation
-----------

Operand 1
---------
\ **Description**\ 
 \ *First operand for calculation*\ 

Operand 2
---------
\ **Description**\ 
 \ *Second operand for calculation*\ 

Type
----
\ **Description**\ 
 \ *Element Type (account or user defined)*\ 
\ **Help**\ 
 \ *The Element Type indicates if this element is the Account element or is a User Defined element.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Include Nulls in Org
--------------------
\ **Description**\ 
 \ *Include nulls in the selection of the organization*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Include Nulls in Org Trx
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the organization transaction*\ 

Account Element
---------------
\ **Description**\ 
 \ *Account Element*\ 
\ **Help**\ 
 \ *Account Elements can be natural accounts or user defined values.*\ 

Include Nulls in Account
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the account*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Include Nulls in Product
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the product*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Include Nulls in Campaign
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the campaign*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Include Nulls in BPartner
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the business partner*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Include Nulls in Project
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the project*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Include Nulls in Location
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the location*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Include Nulls in Sales Region
-----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the sales region*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Include Nulls in Activity
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the activity*\ 

User Element 1
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Include Nulls in User Element 1
-------------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user element 1*\ 

User Element 2
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Include Nulls in User Element 2
-------------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user element 2*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Format Pattern
--------------
\ **Description**\ 
 \ *The pattern used to format a number or date.*\ 
\ **Help**\ 
 \ *A string complying with either Java SimpleDateFormat or DecimalFormat pattern syntax used to override the default presentation format of a date or number type field.*\ 

Include Nulls in User 1
-----------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user 1*\ 

Factor
------
\ **Description**\ 
 \ *Scaling factor.*\ 
\ **Help**\ 
 \ *Numbers are divided by the scaling factor for presentation.  E.g. 123,000 with a scaling factor of 1,000 will display as 123.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User 2
-----------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user 2*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User 3
-----------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user 3*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User 4
-----------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user 4*\ 

Allow Opposite Sign
-------------------
\ **Description**\ 
 \ *Allow column values to be displayed with the opposite sign*\ 
\ **Help**\ 
 \ *Allows values to be displayed with the opposite sign to the calculated value if the "Show Opposite Sign" flag is set on the Report Line. Note that all report calculations are performed before the sign is reversed.*\ 

Report Source
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

Report Column
-------------
\ **Description**\ 
 \ *Column in Report*\ 

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

List Sources
------------
\ **Description**\ 
 \ *List Report Line Sources*\ 
\ **Help**\ 
 \ *List the Source Accounts for Summary Accounts selected*\ 

List Transactions
-----------------
\ **Description**\ 
 \ *List the report transactions*\ 
\ **Help**\ 
 \ *List the transactions of the report source lines*\ 

Type
----
\ **Description**\ 
 \ *Element Type (account or user defined)*\ 
\ **Help**\ 
 \ *The Element Type indicates if this element is the Account element or is a User Defined element.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Include Nulls in Org
--------------------
\ **Description**\ 
 \ *Include nulls in the selection of the organization*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Include Nulls in Org Trx
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the organization transaction*\ 

Account Element
---------------
\ **Description**\ 
 \ *Account Element*\ 
\ **Help**\ 
 \ *Account Elements can be natural accounts or user defined values.*\ 

Include Nulls in Account
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the account*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Include Nulls in BPartner
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the business partner*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Include Nulls in Product
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the product*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Include Nulls in Location
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the location*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Include Nulls in Project
------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the project*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Include Nulls in Sales Region
-----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the sales region*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Include Nulls in Activity
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the activity*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Include Nulls in Campaign
-------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the campaign*\ 

User Element 1
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Include Nulls in User Element 1
-------------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user element 1*\ 

User Element 2
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Include Nulls in User Element 2
-------------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the user element 2*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User List 1
----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the User List 1*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User List 2
----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the User List 2*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User List 3
----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the User List 3*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Include Nulls in User List 4
----------------------------
\ **Description**\ 
 \ *Include nulls in the selection of the User List 4*\ 
