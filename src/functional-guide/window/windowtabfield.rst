
.. _functional-guide/window/windowtabfield:

===================
Window, Tab & Field
===================

Maintain Windows, Tabs & Fields

Help
====
The Window, Tab & Field Window defines the presentation of tables and columns within each window.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Window
------
\ **Description**\ 
 \ *Window header definitions*\ 
\ **Help**\ 
 \ *The Window Tab defines each window in the system. The default flag indicates that this window should be used as the default Zoom windows for the tables in this window.*\ 

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

Beta Functionality
------------------
\ **Description**\ 
 \ *This functionality is considered Beta*\ 
\ **Help**\ 
 \ *Beta functionality is not fully tested or completed.*\ 

WindowType
----------
\ **Description**\ 
 \ *Type or classification of a Window*\ 
\ **Help**\ 
 \ *The Window Type indicates the type of window being defined (Maintain, Transaction or Query)*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

System Color
------------
\ **Description**\ 
 \ *Color for backgrounds or indicators*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Window Width
------------

Window Height
-------------

Copy Window Tabs
----------------
\ **Description**\ 
 \ *Copy all Tabs and Fields from other Window*\ 

Context Info
------------
\ **Description**\ 
 \ *Context Info Maintainig*\ 

Window Translation
------------------

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

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

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

Access
------
\ **Description**\ 
 \ *Window Access*\ 
\ **Help**\ 
 \ *The Window Access Tab defines the Roles which have access to this Window.*\ 

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

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Read Write
----------
\ **Description**\ 
 \ *Field is read / write*\ 
\ **Help**\ 
 \ *The Read Write indicates that this field may be read and updated.*\ 

Tab Sequence
------------
\ **Description**\ 
 \ *Sequence of Tab for Window*\ 

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Tab
---
\ **Description**\ 
 \ *Tab definition within a window holds fields*\ 
\ **Help**\ 
 \ *The Tab Tab defines each Tab within a Window.  Each Tab contains a discrete selection of fields. Note that the display and read only logic is evaluated when loading the window.*\ 

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

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Tab Level
---------
\ **Description**\ 
 \ *Hierarchical Tab Level (0 = top)*\ 
\ **Help**\ 
 \ *Hierarchical level of the tab. If the level is 0, it is the top entity. Level 1 entries are dependent on level 0, etc.*\ 

Single Row Layout
-----------------
\ **Description**\ 
 \ *Default for toggle between Single- and Multi-Row (Grid) Layout*\ 
\ **Help**\ 
 \ *The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.*\ 

Advanced Tab
------------
\ **Description**\ 
 \ *This Tab contains advanced Functionality*\ 
\ **Help**\ 
 \ *The tab with advanced functionality is only displayed, if enabled in Tools>Preference.*\ 

Has Tree
--------
\ **Description**\ 
 \ *Window has Tree Graph*\ 
\ **Help**\ 
 \ *The Has Tree checkbox indicates if this window displays a tree metaphor.*\ 

Accounting Tab
--------------
\ **Description**\ 
 \ *This Tab contains accounting information*\ 
\ **Help**\ 
 \ *The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.*\ 

Order Tab
---------
\ **Description**\ 
 \ *The Tab determines the Order*\ 

TranslationTab
--------------
\ **Description**\ 
 \ *This Tab contains translation information*\ 
\ **Help**\ 
 \ *The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.*\ 

Order Column
------------
\ **Description**\ 
 \ *Column determining the order*\ 
\ **Help**\ 
 \ *Integer Column of the table determining the order (display, sort, ..). If defined, the Order By replaces the default Order By clause. It should be fully qualified (i.e. "tablename.columnname").*\ 

Included Column
---------------
\ **Description**\ 
 \ *Column determining if a Table Column is included in Ordering*\ 
\ **Help**\ 
 \ *If a Included Column is defined, it decides, if a column is active in the ordering - otherwise it is determined that the Order Column has a value of one or greater*\ 

Link Column
-----------
\ **Description**\ 
 \ *Link Column for Multi-Parent tables*\ 
\ **Help**\ 
 \ *The Link Column indicates which column is the primary key for those situations where there is more than one parent.  Only define it, if the table has more than one parent column (e.g. AD_User_Roles).*\ 

Parent Column
-------------
\ **Description**\ 
 \ *The link column on the parent tab.*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Display Logic
-------------
\ **Description**\ 
 \ *If the Field is displayed, the result determines if the field is actually displayed*\ 
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

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

Insert Record
-------------
\ **Description**\ 
 \ *The user can insert a new Record*\ 
\ **Help**\ 
 \ *If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.*\ 

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

Commit Warning
--------------
\ **Description**\ 
 \ *Warning displayed when saving*\ 
\ **Help**\ 
 \ *Warning or information displayed when committing the record*\ 

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

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

Context Info
------------
\ **Description**\ 
 \ *Context Info Maintainig*\ 

Create Fields
-------------
\ **Description**\ 
 \ *Create Field from Table Column, which do not exist in the Tab yet*\ 
\ **Help**\ 
 \ *Based on the table columns of this Tab, this procedure creates the missing Fields*\ 

Copy Tab Fields
---------------
\ **Description**\ 
 \ *Copy Fields from other Tab*\ 

Tab Translation
---------------

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

Tab
---
\ **Description**\ 
 \ *Tab within a Window*\ 
\ **Help**\ 
 \ *The Tab indicates a tab that displays within a window.*\ 

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

Commit Warning
--------------
\ **Description**\ 
 \ *Warning displayed when saving*\ 
\ **Help**\ 
 \ *Warning or information displayed when committing the record*\ 

Field Sequence
--------------
\ **Description**\ 
 \ *Sequence if the Fields in a Tab*\ 

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Field
-----
\ **Description**\ 
 \ *Field definitions in tabs in windows*\ 
\ **Help**\ 
 \ *The Field Tab defines the Fields displayed within a tab.  Changes made to the Field Tab become visible after restart due to caching. If the Sequence is negative, the record are ordered descending. Note that the name, description and help is automatically synchronized if centrally maintained.*\ 

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

Tab
---
\ **Description**\ 
 \ *Tab within a Window*\ 
\ **Help**\ 
 \ *The Tab indicates a tab that displays within a window.*\ 

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Included Tab
------------
\ **Description**\ 
 \ *Included Tab in this Tab (Master Detail)*\ 
\ **Help**\ 
 \ *You can include a Tab in a Tab. If displayed in single row record, the included tab is displayed as multi-row table.*\ 

Is Embedded
-----------
\ **Description**\ 
 \ *When checked of include tab is embedded*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Field Group
-----------
\ **Description**\ 
 \ *Logical grouping of fields*\ 
\ **Help**\ 
 \ *The Field Group indicates the logical group that this field belongs to (History, Amounts, Quantities)*\ 

Centrally maintained
--------------------
\ **Description**\ 
 \ *Information maintained in System Element table*\ 
\ **Help**\ 
 \ *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*\ 

Displayed
---------
\ **Description**\ 
 \ *Determines, if this field is displayed*\ 
\ **Help**\ 
 \ *If the field is displayed, the field Display Logic will determine at runtime, if it is actually displayed*\ 

Displayed in Grid
-----------------
\ **Description**\ 
 \ *Determines, if this field is displayed in grid view*\ 
\ **Help**\ 
 \ *Default whether this field is displayed when grid view is selected.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

Allow Copy
----------
\ **Description**\ 
 \ *Defines whether the value of this field is considered in the copy of record*\ 
\ **Help**\ 
 \ *The default value is yes, it is recommended that values such as ID, document action, document status  should be defined as no.*\ 

Display Logic
-------------
\ **Description**\ 
 \ *If the Field is displayed, the result determines if the field is actually displayed*\ 
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

Display Length
--------------
\ **Description**\ 
 \ *Length of the display in characters*\ 
\ **Help**\ 
 \ *The display length is mainly for String fields. The length has no impact, if the data type of the field is - Integer, Number, Amount	(length determined by the system) - YesNo	(Checkbox) - List, Table, TableDir	(length of combo boxes are determined by their content at runtime)*\ 

Preferred Width
---------------
\ **Description**\ 
 \ *Preferred width in pixels*\ 

Encrypted
---------
\ **Description**\ 
 \ *Display or Storage is encrypted*\ 
\ **Help**\ 
 \ *Display encryption (in Window/Tab/Field) - all characters are displayed as '*' - in the database it is stored in clear text. You will not be able to report on these columns.
Data storage encryption (in Table/Column) - data is stored encrypted in the database (dangerous!) and you will not be able to report on those columns. Independent from Display encryption.*\ 

Same Line
---------
\ **Description**\ 
 \ *Displayed on same line as previous field*\ 
\ **Help**\ 
 \ *The Same Line checkbox indicates that the field will display on the same line as the previous field.*\ 

Record Sort No
--------------
\ **Description**\ 
 \ *Determines in what order the records are displayed*\ 
\ **Help**\ 
 \ *The Record Sort No indicates the ascending sort sequence of the records. If the number is negative, the records are sorted descending. 
Example: A tab with C_DocType_ID (1), DocumentNo (-2) will be sorted ascending by document type and descending by document number (SQL: ORDER BY C_DocType, DocumentNo DESC)*\ 

Obscure
-------
\ **Description**\ 
 \ *Type of obscuring the data (limiting the display)*\ 

Heading only
------------
\ **Description**\ 
 \ *Field without Column - Only label is displayed*\ 
\ **Help**\ 
 \ *The Heading Only checkbox indicates if just the label will display on the screen*\ 

Field Only
----------
\ **Description**\ 
 \ *Label is not displayed*\ 
\ **Help**\ 
 \ *The Field Only checkbox indicates that the column will display without a label.*\ 

Reference Overwrite
-------------------
\ **Description**\ 
 \ *System Reference - optional Overwrite*\ 
\ **Help**\ 
 \ *You can overwrite the Display Type, but only use this if you aware of the consequences.*\ 

Dynamic Validation
------------------
\ **Description**\ 
 \ *Dynamic Validation Rule*\ 
\ **Help**\ 
 \ *These rules define how an entry is determined to valid. You can use variables for dynamic (context sensitive) validation.*\ 

Reference Key
-------------
\ **Description**\ 
 \ *Required to specify, if data type is Table or List*\ 
\ **Help**\ 
 \ *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*\ 

Mandatory Overwrite
-------------------
\ **Description**\ 
 \ *Overwrite Field Mandatory status*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Quick Entry
-----------
\ **Description**\ 
 \ *Display in Quick Entry Form*\ 
\ **Help**\ 
 \ *The field will be displayed in Quick Entry Form for easy encoding.*\ 

Default Logic
-------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

Info Factory Class
------------------
\ **Description**\ 
 \ *Fully qualified class name that implements the InfoFactory interface*\ 
\ **Help**\ 
 \ *Fully qualified class name that implements the InfoFactory interface. This can be use to provide custom Info class for column.*\ 

Context Info
------------
\ **Description**\ 
 \ *Context Info Maintainig*\ 

Field Translation
-----------------
\ **Description**\ 
 \ *Menu Translation - May not need to be translated*\ 
\ **Help**\ 
 \ *Fields are automatically translated, if centrally maintained.  You only need to translate not centrally maintained Fields.*\ 

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

Field
-----
\ **Description**\ 
 \ *Field on a database table*\ 
\ **Help**\ 
 \ *The Field identifies a field on a database table.*\ 

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
