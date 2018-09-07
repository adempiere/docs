
.. _functional-guide/window/window-tableandcolumn:

================
Table and Column
================

Maintain Tables and Columns

Help
====
The Table and Column Window defines all tables with their columns

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Table
-----
\ **Description**\ 
 \ *Table definitions*\ 
\ **Help**\ 
 \ *Table (header) definition - Note that the name of most tables is automatically syncronized.*\ 

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

DB Table Name
-------------
\ **Description**\ 
 \ *Name of the table in the database*\ 
\ **Help**\ 
 \ *The DB Table Name indicates the name of the table in database.*\ 

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

View
----
\ **Description**\ 
 \ *This is a view*\ 
\ **Help**\ 
 \ *This is a view rather than a table.  A view is always treated as read only in the system.*\ 

Data Access Level
-----------------
\ **Description**\ 
 \ *Access Level required*\ 
\ **Help**\ 
 \ *Indicates the access level required for this record or process.*\ 

Maintain Change Log
-------------------
\ **Description**\ 
 \ *Maintain a log of changes*\ 
\ **Help**\ 
 \ *If selected, a log of all changes is maintained.*\ 

Replication Type
----------------
\ **Description**\ 
 \ *Type of Data Replication*\ 
\ **Help**\ 
 \ *The Type of data Replication determines the direction of the data replication.  
Reference means that the data in this system is read only -> 
Local means that the data in this system is not replicated to other systems - 
Merge means that the data in this system is synchronized with the other system <-> * *\ 

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

PO Window
---------
\ **Description**\ 
 \ *Purchase Order Window*\ 
\ **Help**\ 
 \ *Window for Purchase Order (AP) Zooms*\ 

Records deletable
-----------------
\ **Description**\ 
 \ *Indicates if records can be deleted from the database*\ 
\ **Help**\ 
 \ *The Records Deletable checkbox indicates if a record can be deleted from the database.  If records cannot be deleted, you can only deselect the Active flag*\ 

High Volume
-----------
\ **Description**\ 
 \ *Use Search instead of Pick list*\ 
\ **Help**\ 
 \ *The High Volume Checkbox indicates if a search screen will display as opposed to a pick list for selecting records from this table.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Create Columns from DB
----------------------
\ **Description**\ 
 \ *Create Dictionary Columns of Table not existing as a Column but in the Database*\ 
\ **Help**\ 
 \ *If you have added columns in the database to this table, this procedure creates the Column records in the Dictionary.  Please be aware, that they may deleted, if the entity type is not set to User.*\ 

Copy Columns from Table
-----------------------
\ **Description**\ 
 \ *Create Dictionary Columns for a Table taking another as base*\ 

Centrally maintained
--------------------
\ **Description**\ 
 \ *Information maintained in System Element table*\ 
\ **Help**\ 
 \ *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*\ 

Auto Complete Min Length
------------------------
\ **Description**\ 
 \ *Identifier autocomplete trigger length*\ 

Is Document
-----------
\ **Description**\ 
 \ *This flag determinate if the record is a document*\ 
\ **Help**\ 
 \ *This flag is used to mark those tables that behave like documents and allow create automatically columns like: C_DocType_ID, DocumentNo, DateDoc, DocAction, DocStatus, Processed, IsApproved, Description*\ 

Ignore Migration
----------------
\ **Description**\ 
 \ *Ignore this record in log migration*\ 

Context Info
------------
\ **Description**\ 
 \ *Context Info Maintainig*\ 

Table Translation
-----------------
\ **Description**\ 
 \ *Table Translation*\ 
\ **Help**\ 
 \ *Note that many Table names will be overwritten / translated automatically*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

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

Zoom Condition
--------------

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

Zoom Logic
----------
\ **Description**\ 
 \ *the result determines if the zoom condition is applied*\ 
\ **Help**\ 
 \ *format := {expression} [{logic} {expression}]*  
expression := @{context}@{operand}{value} or @{context}@{operand}{value}*  
logic := {|}|{&}
context := any global or window context 
value := strings or numbers
logic operators	:= AND or OR with the previous result from left to right 
operand := eq{=}, gt{&gt;}, le{&lt;}, not{~^!} 
Examples: 
@AD_Table_ID@=14 | @Language@!GERGER 
@PriceLimit@>10 | @PriceList@>@PriceActual@
@Name@>J
Strings may be in single quotes (optional)*\ 

Sql WHERE
---------
\ **Description**\ 
 \ *Fully qualified SQL WHERE clause*\ 
\ **Help**\ 
 \ *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*\ 

Column
------
\ **Description**\ 
 \ *Table Column definitions*\ 
\ **Help**\ 
 \ *Defines the columns of a table. Note thet the name of the column is automatically syncronized.*\ 

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

DB Column Name
--------------
\ **Description**\ 
 \ *Name of the column in the database*\ 
\ **Help**\ 
 \ *The Column Name indicates the name of a column on a table as defined in the database.*\ 

Column SQL
----------
\ **Description**\ 
 \ *Virtual Column (r/o)*\ 
\ **Help**\ 
 \ *You can define virtual columns (not stored in the database). If defined, the Column name is the synonym of the SQL expression defined here. The SQL expression must be valid.
Example: "Updated-Created" would list the age of the entry in days*\ 

System Element
--------------
\ **Description**\ 
 \ *System Element enables the central maintenance of column description and help.*\ 
\ **Help**\ 
 \ *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

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

Version
-------
\ **Description**\ 
 \ *Version of the table definition*\ 
\ **Help**\ 
 \ *The Version indicates the version of this table definition.*\ 

Length
------
\ **Description**\ 
 \ *Length of the column in the database*\ 
\ **Help**\ 
 \ *The Length indicates the length of a column as defined in the database.*\ 

Reference
---------
\ **Description**\ 
 \ *System Reference and Validation*\ 
\ **Help**\ 
 \ *The Reference could be a display type, list or table validation.*\ 

Dynamic Validation
------------------
\ **Description**\ 
 \ *Dynamic Validation Rule*\ 
\ **Help**\ 
 \ *These rules define how an entry is determined to valid. You can use variables for dynamic (context sensitive) validation.*\ 

Value Format
------------
\ **Description**\ 
 \ *Format of the value; Can contain fixed format elements, Variables: "_lLoOaAcCa09"*\ 
\ **Help**\ 
 \ *\ **Validation elements:**\ 
 	(Space) any character
_	Space (fixed character)
l	any Letter a..Z NO space
L	any Letter a..Z NO space converted to upper case
o	any Letter a..Z or space
O	any Letter a..Z or space converted to upper case
a	any Letters & Digits NO space
A	any Letters & Digits NO space converted to upper case
c	any Letters & Digits or space
C	any Letters & Digits or space converted to upper case
0	Digits 0..9 NO space
9	Digits 0..9 or space

Example of format "(000)_000-0000"*\ 

Autocomplete
------------
\ **Description**\ 
 \ *Automatic completion for textfields*\ 
\ **Help**\ 
 \ *The autocompletion uses all existing values (from the same client and organization) of the field.*\ 

Format Pattern
--------------
\ **Description**\ 
 \ *The pattern used to format a number or date.*\ 
\ **Help**\ 
 \ *A string complying with either Java SimpleDateFormat or DecimalFormat pattern syntax used to override the default presentation format of a date or number type field.*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Chart
-----

Reference Key
-------------
\ **Description**\ 
 \ *Required to specify, if data type is Table or List*\ 
\ **Help**\ 
 \ *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*\ 

Info Factory Class
------------------
\ **Description**\ 
 \ *Fully qualified class name that implements the InfoFactory interface*\ 
\ **Help**\ 
 \ *Fully qualified class name that implements the InfoFactory interface. This can be use to provide custom Info class for column.*\ 

Min. Value
----------
\ **Description**\ 
 \ *Minimum Value for a field*\ 
\ **Help**\ 
 \ *The Minimum Value indicates the lowest  allowable value for a field.*\ 

Max. Value
----------
\ **Description**\ 
 \ *Maximum Value for a field*\ 
\ **Help**\ 
 \ *The Maximum Value indicates the highest allowable value for a field*\ 

Default Logic
-------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

Key column
----------
\ **Description**\ 
 \ *This column is the key in this table*\ 
\ **Help**\ 
 \ *The key column must also be display sequence 0 in the field definition and may be hidden.*\ 

Parent link column
------------------
\ **Description**\ 
 \ *This column is a link to the parent table (e.g. header from lines) - incl. Association key columns*\ 
\ **Help**\ 
 \ *The Parent checkbox indicates if this column is a link to the parent table.*\ 

Mandatory
---------
\ **Description**\ 
 \ *Data entry is required in this column*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Column Encryption
-----------------
\ **Description**\ 
 \ *Test and enable Column Encryption*\ 
\ **Help**\ 
 \ *To enable storage encryption or remove encryption is dangerous as you may loose data. You need to verify that the column is big enough to hold the encrypted value.  You can provide your own encryption method, but cannot change it once enabled.  
The default implementation supports US ASCII String conversion (not Unicode, Numbers, Dates)
Note that support is restricted to setup and test, but not data recovery.*\ 

Updatable
---------
\ **Description**\ 
 \ *Determines, if the field can be updated*\ 
\ **Help**\ 
 \ *The Updatable checkbox indicates if a field can be updated by the user.*\ 

Always Updateable
-----------------
\ **Description**\ 
 \ *The column is always updateable, even if the record is not active or processed*\ 
\ **Help**\ 
 \ *If selected and if the window / tab is not read only, you can always update the column.  This might be useful for comments, etc.*\ 

Allow Copy
----------
\ **Description**\ 
 \ *Defines whether the value of this field is considered in the copy of record*\ 
\ **Help**\ 
 \ *The default value is yes, it is recommended that values such as ID, document action, document status  should be defined as no.*\ 

Allow Logging
-------------
\ **Description**\ 
 \ *Determine if a column must be recorded into the change log*\ 

Identifier
----------
\ **Description**\ 
 \ *This column is part of the record identifier*\ 
\ **Help**\ 
 \ *The Identifier checkbox indicates that this column is part of the identifier or key for this table.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Selection Column
----------------
\ **Description**\ 
 \ *Is this column used for finding rows in windows*\ 
\ **Help**\ 
 \ *If selected, the column is listed in the first find window tab and in the selection part of the window*\ 

Range
-----
\ **Description**\ 
 \ *The parameter is a range of values*\ 
\ **Help**\ 
 \ *The Range checkbox indicates that this parameter is a range of values.*\ 

Read Only Logic
---------------
\ **Description**\ 
 \ *Logic to determine if field is read only (applies only when field is read-write)*\ 
\ **Help**\ 
 \ *format := {expression} [{logic} {expression}]*  
expression := @{context}@{operand}{value} or @{context}@{operand}{value}*  
logic := {|}|{&}
context := any global or window context 
value := strings or numbers
logic operators	:= AND or OR with the previous result from left to right 
operand := eq{=}, gt{&gt;}, le{&lt;}, not{~^!} 
Examples: 
@AD_Table_ID@=14 | @Language@!GERGER 
@PriceLimit@>10 | @PriceList@>@PriceActual@
@Name@>J
Strings may be in single quotes (optional)*\ 

Mandatory Logic
---------------

Callout
-------
\ **Description**\ 
 \ *Fully qualified class names and method - separated by semicolons*\ 
\ **Help**\ 
 \ *A Callout allow you to create Java extensions to perform certain tasks always after a value changed. Callouts should not be used for validation but consequences of a user selecting a certain value.
The callout is a Java class implementing org.compiere.model.Callout and a method name to call.  Example: "org.compiere.model.CalloutRequest.copyText" instantiates the class "CalloutRequest" and calls the method "copyText". You can have multiple callouts by separating them via a semicolon*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Synchronize Column
------------------
\ **Description**\ 
 \ *Change database table definition from application dictionary*\ 
\ **Help**\ 
 \ *When selected, the database column definition is updated based on your entries in the Column definition of the Application Dictionary. Note that not all changes are supported by the database and may result in an error.*\ 

Column Translation
------------------
\ **Description**\ 
 \ *Column Translation*\ 
\ **Help**\ 
 \ *Do not translate - overwritten / translated automatically*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

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

Identifier Sequence
-------------------

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Used in Field
-------------

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

Fields
======

Tab
---
\ **Description**\ 
 \ *Tab within a Window*\ 
\ **Help**\ 
 \ *The Tab indicates a tab that displays within a window.*\ 

Field
-----
\ **Description**\ 
 \ *Field on a database table*\ 
\ **Help**\ 
 \ *The Field identifies a field on a database table.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Table Script Validator
----------------------

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Event Model Validator
---------------------

Rule
----

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Linked Process
--------------

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

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Linked Process Para
-------------------

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

Column Link Process
-------------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Process Parameter
-----------------

Default Logic
-------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

Assign Process
--------------

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
