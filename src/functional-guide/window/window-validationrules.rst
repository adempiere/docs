
.. _functional-guide/window/window-validationrules:

================
Validation Rules
================

Maintain dynamic Validation Rules for columns and fields

Help
====
The Validation Rules Window defines all dynamic rules used when entering and maintaining columns and fields.  This window is for System Admin use only.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Validation
----------
\ **Description**\ 
 \ *Validation Rules*\ 
\ **Help**\ 
 \ *The Validation Rules Tab defines all dynamic rules used when entering and maintaining columns and fields.*\ 

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

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Type
----
\ **Description**\ 
 \ *Type of Validation (SQL, Java Script, Java Language)*\ 
\ **Help**\ 
 \ *The Type indicates the type of validation that will occur.  This can be SQL, Java Script or Java Language.*\ 

Validation code
---------------
\ **Description**\ 
 \ *Validation Code*\ 
\ **Help**\ 
 \ *The Validation Code displays the date, time and message of the error.*\ 

Used in Column
--------------
\ **Description**\ 
 \ *Used in Column*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

System Element
--------------
\ **Description**\ 
 \ *System Element enables the central maintenance of column description and help.*\ 
\ **Help**\ 
 \ *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*\ 

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

Reference Key
-------------
\ **Description**\ 
 \ *Required to specify, if data type is Table or List*\ 
\ **Help**\ 
 \ *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*\ 

Dynamic Validation
------------------
\ **Description**\ 
 \ *Dynamic Validation Rule*\ 
\ **Help**\ 
 \ *These rules define how an entry is determined to valid. You can use variables for dynamic (context sensitive) validation.*\ 

Used in Field
-------------
\ **Description**\ 
 \ *Used in Field*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Used in Process Parameter
-------------------------
\ **Description**\ 
 \ *Used in Process Parameter*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

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

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Centrally maintained
--------------------
\ **Description**\ 
 \ *Information maintained in System Element table*\ 
\ **Help**\ 
 \ *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

DB Column Name
--------------
\ **Description**\ 
 \ *Name of the column in the database*\ 
\ **Help**\ 
 \ *The Column Name indicates the name of a column on a table as defined in the database.*\ 

System Element
--------------
\ **Description**\ 
 \ *System Element enables the central maintenance of column description and help.*\ 
\ **Help**\ 
 \ *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*\ 

Reference
---------
\ **Description**\ 
 \ *System Reference and Validation*\ 
\ **Help**\ 
 \ *The Reference could be a display type, list or table validation.*\ 

Reference Key
-------------
\ **Description**\ 
 \ *Required to specify, if data type is Table or List*\ 
\ **Help**\ 
 \ *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*\ 

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

Dynamic Validation
------------------
\ **Description**\ 
 \ *Dynamic Validation Rule*\ 
\ **Help**\ 
 \ *These rules define how an entry is determined to valid. You can use variables for dynamic (context sensitive) validation.*\ 

Length
------
\ **Description**\ 
 \ *Length of the column in the database*\ 
\ **Help**\ 
 \ *The Length indicates the length of a column as defined in the database.*\ 

Mandatory
---------
\ **Description**\ 
 \ *Data entry is required in this column*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Range
-----
\ **Description**\ 
 \ *The parameter is a range of values*\ 
\ **Help**\ 
 \ *The Range checkbox indicates that this parameter is a range of values.*\ 

Default Logic
-------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

Default Logic 2
---------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

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

Used in Browse Field
--------------------
\ **Description**\ 
 \ *Used in Browse Field*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Smart Browse
------------

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

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Centrally maintained
--------------------
\ **Description**\ 
 \ *Information maintained in System Element table*\ 
\ **Help**\ 
 \ *The Centrally Maintained checkbox indicates if the Name, Description and Help maintained in 'System Element' table  or 'Window' table.*\ 

View Column
-----------
\ **Description**\ 
 \ *Column of View*\ 

System Element
--------------
\ **Description**\ 
 \ *System Element enables the central maintenance of column description and help.*\ 
\ **Help**\ 
 \ *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*\ 

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

Reference Key
-------------
\ **Description**\ 
 \ *Required to specify, if data type is Table or List*\ 
\ **Help**\ 
 \ *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*\ 

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

Info Factory Class
------------------
\ **Description**\ 
 \ *Fully qualified class name that implements the InfoFactory interface*\ 
\ **Help**\ 
 \ *Fully qualified class name that implements the InfoFactory interface. This can be use to provide custom Info class for column.*\ 

Displayed
---------
\ **Description**\ 
 \ *Determines, if this field is displayed*\ 
\ **Help**\ 
 \ *If the field is displayed, the field Display Logic will determine at runtime, if it is actually displayed*\ 

Length
------
\ **Description**\ 
 \ *Length of the column in the database*\ 
\ **Help**\ 
 \ *The Length indicates the length of a column as defined in the database.*\ 

Order by
--------
\ **Description**\ 
 \ *Include in sort order*\ 
\ **Help**\ 
 \ *The records are ordered by the value of this column. If a column is used for grouping, it needs to be included in the sort order as well.*\ 

Record Sort No
--------------
\ **Description**\ 
 \ *Determines in what order the records are displayed*\ 
\ **Help**\ 
 \ *The Record Sort No indicates the ascending sort sequence of the records. If the number is negative, the records are sorted descending. 
Example: A tab with C_DocType_ID (1), DocumentNo (-2) will be sorted ascending by document type and descending by document number (SQL: ORDER BY C_DocType, DocumentNo DESC)*\ 

Key column
----------
\ **Description**\ 
 \ *This column is the key in this table*\ 
\ **Help**\ 
 \ *The key column must also be display sequence 0 in the field definition and may be hidden.*\ 

Identifier
----------
\ **Description**\ 
 \ *This column is part of the record identifier*\ 
\ **Help**\ 
 \ *The Identifier checkbox indicates that this column is part of the identifier or key for this table.*\ 

Mandatory
---------
\ **Description**\ 
 \ *Data entry is required in this column*\ 
\ **Help**\ 
 \ *The field must have a value for the record to be saved to the database.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

Query Criteria
--------------
\ **Description**\ 
 \ *The column is also used as a query criteria*\ 
\ **Help**\ 
 \ *The column is used to enter queries - the SQL cannot be an expression*\ 

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

Range
-----
\ **Description**\ 
 \ *The parameter is a range of values*\ 
\ **Help**\ 
 \ *The Range checkbox indicates that this parameter is a range of values.*\ 

Default Logic
-------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

Callout
-------
\ **Description**\ 
 \ *Fully qualified class names and method - separated by semicolons*\ 
\ **Help**\ 
 \ *A Callout allow you to create Java extensions to perform certain tasks always after a value changed. Callouts should not be used for validation but consequences of a user selecting a certain value.
The callout is a Java class implementing org.compiere.model.Callout and a method name to call.  Example: "org.compiere.model.CalloutRequest.copyText" instantiates the class "CalloutRequest" and calls the method "copyText". You can have multiple callouts by separating them via a semicolon*\ 

Default Logic 2
---------------
\ **Description**\ 
 \ *Default value hierarchy, separated by ;*\ 
\ **Help**\ 
 \ *The defaults are evaluated in the order of definition, the first not null value becomes the default value of the column. The values are separated by comma or semicolon. a) Literals:. 'Text' or 123 b) Variables - in format @Variable@ - Login e.g. #Date, #AD_Org_ID, #AD_Client_ID - Accounting Schema: e.g. $C_AcctSchema_ID, $C_Calendar_ID - Global defaults: e.g. DateFormat - Window values (all Picks, CheckBoxes, RadioButtons, and DateDoc/DateAcct) c) SQL code with the tag: @SQL=SELECT something AS DefaultValue FROM ... The SQL statement can contain variables.  There can be no other value other than the SQL statement. The default is only evaluated, if no user preference is defined.  Default definitions are ignored for record columns as Key, Parent, Client as well as Buttons.*\ 

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

Axis Column
-----------
\ **Description**\ 
 \ *Axis the link column.*\ 
\ **Help**\ 
 \ *Axis Column defines the base column to show the records on this table as columns inside the browser*\ 

Axis Parent Column
------------------
\ **Description**\ 
 \ *The link Axis column view on the parent key*\ 
\ **Help**\ 
 \ *Axis Parent Column filters the records used by Axis Column, the values for the filter are obtained from the context of the Field Browser defined as query criteria
context.*\ 
