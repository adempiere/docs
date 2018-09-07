
.. _functional-guide/window/window-reportprocess:

================
Report & Process
================

Maintain Reports & Processes

Help
====
The Report & Process Window is used to define the parameters and access rules for every Report and Process within the system.  This window is for System Admin use only.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Report & Process
----------------
\ **Description**\ 
 \ *Define Report & Process*\ 
\ **Help**\ 
 \ *The Report and Process Tab defines each report and process run in the system.  
Please note that the Print Format is only used for Document Print when you want to share a common format defined on System level. For normal reports and formats, you would not define a Print Format here, but modify the generated print format and set it as the default.*\ 

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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Data Access Level
-----------------
\ **Description**\ 
 \ *Access Level required*\ 
\ **Help**\ 
 \ *Indicates the access level required for this record or process.*\ 

Report
------
\ **Description**\ 
 \ *Indicates a Report record*\ 
\ **Help**\ 
 \ *The Report checkbox indicates that this record is a report as opposed to a process*\ 

Server Process
--------------
\ **Description**\ 
 \ *Run this Process on Server only*\ 
\ **Help**\ 
 \ *Enabling this flag disables to run the process on the client.  This potentially decreases the availability.*\ 

Classname
---------
\ **Description**\ 
 \ *Java Classname*\ 
\ **Help**\ 
 \ *The Classname identifies the Java classname used by this report or process.*\ 

Procedure
---------
\ **Description**\ 
 \ *Name of the Database Procedure*\ 
\ **Help**\ 
 \ *The Procedure indicates the name of the database procedure called by this report or process.*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

Special Form
------------
\ **Description**\ 
 \ *Special Form*\ 
\ **Help**\ 
 \ *The Special Form field identifies a unique Special Form in the system.*\ 

Smart Browse
------------

Report View
-----------
\ **Description**\ 
 \ *View used to generate this report*\ 
\ **Help**\ 
 \ *The Report View indicates the view used to generate this report.*\ 

Direct print
------------
\ **Description**\ 
 \ *Print without dialog*\ 
\ **Help**\ 
 \ *The Direct Print checkbox indicates that this report will print without a print dialog box being displayed.*\ 

Print Format
------------
\ **Description**\ 
 \ *Data Print Format*\ 
\ **Help**\ 
 \ *The print format determines how data is rendered for print.*\ 

Show Help
---------

Create Parameters
-----------------
\ **Description**\ 
 \ *Copy settings from one report and process to another or create parameters from a Report View Columns*\ 
\ **Help**\ 
 \ *You can select the parameters to copy or create in the current process*\ 

Generate Class from Process
---------------------------
\ **Description**\ 
 \ *Generate a class for process when is own java*\ 

Statistic Count
---------------
\ **Description**\ 
 \ *Internal statistics how often the entity was used*\ 
\ **Help**\ 
 \ *For internal use.*\ 

Statistic Seconds
-----------------
\ **Description**\ 
 \ *Internal statistics how many seconds a process took*\ 
\ **Help**\ 
 \ *For internal use*\ 

Jasper Report
-------------

Report Translation
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

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

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

Report Access
-------------
\ **Description**\ 
 \ *Report Access*\ 
\ **Help**\ 
 \ *The Report Access Tab determines who can access a report or process*\ 

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

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

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

Parameter Sequence
------------------

.. note::
    null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Parameter
---------
\ **Description**\ 
 \ *Report Parameter*\ 
\ **Help**\ 
 \ *The Report Parameter Tab defines any parameters required to execute a report or process.*\ 

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

Is Information Only
-------------------
\ **Description**\ 
 \ *When a Parameter is Information Only*\ 

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

Parameter Translation
---------------------

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

Process Parameter
-----------------

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
