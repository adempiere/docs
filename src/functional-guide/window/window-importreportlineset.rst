
.. _functional-guide/window/window-importreportlineset:

======================
Import Report Line Set
======================

Import Report Line Sets

Help
====
The Import Report Line Set Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Report Line Set
----------------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Report Line Set
----------------------
\ **Description**\ 
 \ *Import Report Line Set values*\ 

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

Report Line Set Name
--------------------
\ **Description**\ 
 \ *Name of the Report Line Set*\ 

Report Line Set
---------------

Report Line
-----------

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

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

Line Type
---------

Calculation
-----------

Report Source
-------------
\ **Description**\ 
 \ *Restriction of what will be shown in Report Line*\ 

Element Key
-----------
\ **Description**\ 
 \ *Key of the element*\ 

Account Element
---------------
\ **Description**\ 
 \ *Account Element*\ 
\ **Help**\ 
 \ *Account Elements can be natural accounts or user defined values.*\ 

Import Report Line Set
----------------------
\ **Description**\ 
 \ *Import Report Line Set information*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Tab Level
---------
\ **Description**\ 
 \ *Hierarchical Tab Level (0 = top)*\ 
\ **Help**\ 
 \ *Hierarchical level of the tab. If the level is 0, it is the top entity. Level 1 entries are dependent on level 0, etc.*\ 

Report Line Style
-----------------
