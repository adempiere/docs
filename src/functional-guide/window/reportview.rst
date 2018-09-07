
.. _functional-guide/window/reportview:

===========
Report View
===========

Maintain Report Views

Help
====
The Report View Window defines the views used when generating reports.  This window is for System Admin use only.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Report View
-----------
\ **Description**\ 
 \ *Define Report View*\ 
\ **Help**\ 
 \ *The Define Report View defines the views used in report generation*\ 

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

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

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

Centrally maintained
--------------------
\ **Description**\ 
 \ *Information maintained in System Element table*\ 
\ **Help**\ 
 \ *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Sql WHERE
---------
\ **Description**\ 
 \ *Fully qualified SQL WHERE clause*\ 
\ **Help**\ 
 \ *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*\ 

Sql ORDER BY
------------
\ **Description**\ 
 \ *Fully qualified ORDER BY clause*\ 
\ **Help**\ 
 \ *The ORDER BY Clause indicates the SQL ORDER BY clause to use for record selection*\ 

Classname
---------
\ **Description**\ 
 \ *Java Classname*\ 
\ **Help**\ 
 \ *The Classname identifies the Java classname used by this report or process.*\ 

Translation
-----------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

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

Report View
-----------
\ **Description**\ 
 \ *View used to generate this report*\ 
\ **Help**\ 
 \ *The Report View indicates the view used to generate this report.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Report View Column
------------------
\ **Description**\ 
 \ *Report View Column*\ 
\ **Help**\ 
 \ *The Report View Column Tab defines any columns which will be overridden in the generation of the select SQL*\ 

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

Report View
-----------
\ **Description**\ 
 \ *View used to generate this report*\ 
\ **Help**\ 
 \ *The Report View indicates the view used to generate this report.*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Function Column
---------------
\ **Description**\ 
 \ *Overwrite Column with Function*\ 
\ **Help**\ 
 \ *The Function Column indicates that the column will be overridden with a function*\ 

SQL Group Function
------------------
\ **Description**\ 
 \ *This function will generate a Group By Clause*\ 
\ **Help**\ 
 \ *The SQL Group Function checkbox indicates that this function will generate a Group by Clause in the resulting SQL.*\ 
