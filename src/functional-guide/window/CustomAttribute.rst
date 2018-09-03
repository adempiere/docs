
.. _window-customattribute:

================
Custom Attribute
================

Maintain custom entity attributes

Help
====
This is a System only Window.  Customer Attributes allow the entry of additional information to an entity.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Custom Attribute
----------------
\ **Description**\ 
 \ *Define Custom Attribute*\ 
\ **Help**\ 
 \ *The Custom Attribute Tab defines additional attributes or information for a product or entity.*\ 

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

Updatable
---------
\ **Description**\ 
 \ *Determines, if the field can be updated*\ 
\ **Help**\ 
 \ *The Updatable checkbox indicates if a field can be updated by the user.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

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

Display Length
--------------
\ **Description**\ 
 \ *Length of the display in characters*\ 
\ **Help**\ 
 \ *The display length is mainly for String fields. The length has no impact, if the data type of the field is - Integer, Number, Amount	(length determined by the system) - YesNo	(Checkbox) - List, Table, TableDir	(length of combo boxes are determined by their content at runtime)*\ 

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

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

Same Line
---------
\ **Description**\ 
 \ *Displayed on same line as previous field*\ 
\ **Help**\ 
 \ *The Same Line checkbox indicates that the field will display on the same line as the previous field.*\ 

Field Only
----------
\ **Description**\ 
 \ *Label is not displayed*\ 
\ **Help**\ 
 \ *The Field Only checkbox indicates that the column will display without a label.*\ 

Heading only
------------
\ **Description**\ 
 \ *Field without Column - Only label is displayed*\ 
\ **Help**\ 
 \ *The Heading Only checkbox indicates if just the label will display on the screen*\ 

Encrypted
---------
\ **Description**\ 
 \ *Display or Storage is encrypted*\ 
\ **Help**\ 
 \ *Display encryption (in Window/Tab/Field) - all characters are displayed as '*' - in the database it is stored in clear text. You will not be able to report on these columns.
Data storage encryption (in Table/Column) - data is stored encrypted in the database (dangerous!) and you will not be able to report on those columns. Independent from Display encryption.*\ 
