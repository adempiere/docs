
.. _window-workflow:

========
Workflow
========

Maintain Workflow

Help
====
The Workflow Window defines Workflows in the system, the access level for the Workflow and the Nodes or Steps within the Workflow.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Workflow
--------
\ **Description**\ 
 \ *Define Workflow*\ 
\ **Help**\ 
 \ *The Workflow Tab defines Workflows in the system.*\ 

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

Workflow Type
-------------
\ **Description**\ 
 \ *Type of Workflow*\ 
\ **Help**\ 
 \ *The type of workflow determines how the workflow is started.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Document Value Logic
--------------------
\ **Description**\ 
 \ *Logic to determine Workflow Start - If true, a workflow process is started for the document*\ 
\ **Help**\ 
 \ *You can enter simple logic using variables like @Created@=@Updated@, which fires, when a record is created. If you need to evaluate also values of other records, you need to use SQL logic and need to prefix this logic with "SQL=". Example: start a Order verify workflow, when a business partner ordered something and is over the credit limit  "SQL=EXISTS (SELECT * FROM C_BPartner bp WHERE C_Order. C_BPartner_ID=bp. C_BPartner_ID AND SO_CreditUsed > SO_CreditLimit)".
Note that the SQL based logic checks for duplicate workflows (i.e. a workflow is started only once per record).*\ 

Data Access Level
-----------------
\ **Description**\ 
 \ *Access Level required*\ 
\ **Help**\ 
 \ *Indicates the access level required for this record or process.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Workflow Responsible
--------------------
\ **Description**\ 
 \ *Responsible for Workflow Execution*\ 
\ **Help**\ 
 \ *The ultimate responsibility for a workflow is with an actual user. The Workflow Responsible allows to define ways to find that actual User.*\ 

Priority
--------
\ **Description**\ 
 \ *Indicates if this request is of a high, medium or low priority.*\ 
\ **Help**\ 
 \ *The Priority indicates the importance of this request.*\ 

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

Publication Status
------------------
\ **Description**\ 
 \ *Status of Publication*\ 
\ **Help**\ 
 \ *Used for internal documentation*\ 

Version
-------
\ **Description**\ 
 \ *Version of the table definition*\ 
\ **Help**\ 
 \ *The Version indicates the version of this table definition.*\ 

Author
------
\ **Description**\ 
 \ *Author/Creator of the Entity*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Start Node
----------
\ **Description**\ 
 \ *Workflow Node, step or process*\ 
\ **Help**\ 
 \ *The Workflow Node indicates a unique step or process in a Workflow.*\ 

Workflow Processor
------------------
\ **Description**\ 
 \ *Workflow Processor Server*\ 
\ **Help**\ 
 \ *Workflow Processor Server*\ 

Duration Unit
-------------
\ **Description**\ 
 \ *Unit of Duration*\ 
\ **Help**\ 
 \ *Unit to define the length of time for the execution*\ 

Duration Limit
--------------
\ **Description**\ 
 \ *Maximum Duration in Duration Unit*\ 
\ **Help**\ 
 \ *Maximum (critical) Duration for time management purposes (e.g. starting an escalation procedure, etc.) in Duration Units.*\ 

Duration
--------
\ **Description**\ 
 \ *Normal Duration in Duration Unit*\ 
\ **Help**\ 
 \ *Expected (normal) Length of time for the execution*\ 

Cost
----
\ **Description**\ 
 \ *Cost information*\ 

Working Time
------------
\ **Description**\ 
 \ *Workflow Simulation Execution Time*\ 
\ **Help**\ 
 \ *Amount of time the performer of the activity needs to perform the task in Duration Unit*\ 

Waiting Time
------------
\ **Description**\ 
 \ *Workflow Simulation Waiting time*\ 
\ **Help**\ 
 \ *Amount of time needed to prepare the performance of the task on Duration Units*\ 

Validate Workflow
-----------------
\ **Description**\ 
 \ *Validate thet the workflos is correct*\ 
\ **Help**\ 
 \ *(limited checking)*\ 

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

Workflow Translation
--------------------

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

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

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
 \ *Workflow Access*\ 
\ **Help**\ 
 \ *The Workflow Access Tab defines the Roles who have access to this Workflow.*\ 

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

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

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

Block
-----
\ **Description**\ 
 \ *Workflow Transaction Execution Block*\ 
\ **Help**\ 
 \ *A workflow execution block is optional and allows all work to be performed in a single transaction. If one step (node activity) fails, the entire work is rolled back.*\ 

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

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

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

Node
----
\ **Description**\ 
 \ *Define workflow nodes*\ 
\ **Help**\ 
 \ *The Node Tab defines each Node, Activity or step in this Workflow.
The action (actibity) type determines the execution: "Route" may be used in routing control conditions.  "None" identifies manual execution.*\ 

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

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

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

Workflow Responsible
--------------------
\ **Description**\ 
 \ *Responsible for Workflow Execution*\ 
\ **Help**\ 
 \ *The ultimate responsibility for a workflow is with an actual user. The Workflow Responsible allows to define ways to find that actual User.*\ 

Priority
--------
\ **Description**\ 
 \ *Indicates if this request is of a high, medium or low priority.*\ 
\ **Help**\ 
 \ *The Priority indicates the importance of this request.*\ 

Start Mode
----------
\ **Description**\ 
 \ *Workflow Activity Start Mode*\ 
\ **Help**\ 
 \ *How is the execution of an activity triggered. Automatic are triggered implicitly by the system, Manual explicitly by the User.*\ 

Finish Mode
-----------
\ **Description**\ 
 \ *Workflow Activity Finish Mode*\ 
\ **Help**\ 
 \ *How the system operated at the end of an activity. Automatic  implies return when the invoked applications finished control - Manual the user has to explicitly terminate the activity.*\ 

Join Element
------------
\ **Description**\ 
 \ *Semantics for multiple incoming Transitions*\ 
\ **Help**\ 
 \ *Semantics for multiple incoming Transitions for a Node/Activity. AND joins all concurrent threads - XOR requires one thread (no synchronization).*\ 

Split Element
-------------
\ **Description**\ 
 \ *Semantics for multiple outgoing Transitions*\ 
\ **Help**\ 
 \ *Semantics for multiple outgoing Transitions for a Node/Activity.  AND represents multiple concurrent threads - XOR represents the first transition with a true Transition condition.*\ 

Action
------
\ **Description**\ 
 \ *Indicates the Action to be performed*\ 
\ **Help**\ 
 \ *The Action field is a drop down list box which indicates the Action to be performed for this Item.*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

Special Form
------------
\ **Description**\ 
 \ *Special Form*\ 
\ **Help**\ 
 \ *The Special Form field identifies a unique Special Form in the system.*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Smart Browse
------------

View
----
\ **Description**\ 
 \ *View allows you to create dynamic views of information from the dictionary application*\ 
\ **Help**\ 
 \ *These views can be based on tables and views of the dictionary application.*\ 

Attribute Name
--------------
\ **Description**\ 
 \ *Name of the Attribute*\ 
\ **Help**\ 
 \ *Identifier of the attribute*\ 

Attribute Value
---------------
\ **Description**\ 
 \ *Value of the Attribute*\ 
\ **Help**\ 
 \ *Adempiere converts the (string) field values to the attribute data type.  Booleans (Yes-No) may have the values "true" and "false", the date format is YYYY-MM-DD*\ 

EMail Recipient
---------------
\ **Description**\ 
 \ *Recipient of the EMail*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

Duration Limit
--------------
\ **Description**\ 
 \ *Maximum Duration in Duration Unit*\ 
\ **Help**\ 
 \ *Maximum (critical) Duration for time management purposes (e.g. starting an escalation procedure, etc.) in Duration Units.*\ 

OS Task
-------
\ **Description**\ 
 \ *Operation System Task*\ 
\ **Help**\ 
 \ *The Task field identifies a Operation System Task in the system.*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique workflow.   A workflow is a grouping of related tasks, in a specified sequence and optionally including approvals*\ 

Subflow Execution
-----------------
\ **Description**\ 
 \ *Mode how the sub-workflow is executed*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

Workflow Block
--------------
\ **Description**\ 
 \ *Workflow Transaction Execution Block*\ 
\ **Help**\ 
 \ *A workflow execution block is optional and allows all work to be performed in a single transaction. If one step (node activity) fails, the entire work is rolled back.*\ 

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Wait Time
---------
\ **Description**\ 
 \ *Time in minutes to wait (sleep)*\ 
\ **Help**\ 
 \ *Time in minutes to be suspended (sleep)*\ 

Dynamic Priority Unit
---------------------
\ **Description**\ 
 \ *Change of priority when Activity is suspended waiting for user*\ 
\ **Help**\ 
 \ *Starting with the Process / Node priority level, the priority of the suspended activity can be changed dynamically. Example +5 every 10 minutes*\ 

Dynamic Priority Change
-----------------------
\ **Description**\ 
 \ *Change of priority when Activity is suspended waiting for user*\ 
\ **Help**\ 
 \ *Starting with the Process / Node priority level, the priority of the suspended activity can be changed dynamically. Example +5 every 10 minutes*\ 

Duration
--------
\ **Description**\ 
 \ *Normal Duration in Duration Unit*\ 
\ **Help**\ 
 \ *Expected (normal) Length of time for the execution*\ 

Cost
----
\ **Description**\ 
 \ *Cost information*\ 

Working Time
------------
\ **Description**\ 
 \ *Workflow Simulation Execution Time*\ 
\ **Help**\ 
 \ *Amount of time the performer of the activity needs to perform the task in Duration Unit*\ 

Waiting Time
------------
\ **Description**\ 
 \ *Workflow Simulation Waiting time*\ 
\ **Help**\ 
 \ *Amount of time needed to prepare the performance of the task on Duration Units*\ 

Parameter
---------
\ **Description**\ 
 \ *Workflow Node Parameter*\ 
\ **Help**\ 
 \ *Parameter for the execution of the Workflow Node*\ 

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

Node
----
\ **Description**\ 
 \ *Workflow Node (activity), step or process*\ 
\ **Help**\ 
 \ *The Workflow Node indicates a unique step or process in a Workflow.*\ 

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

Attribute Name
--------------
\ **Description**\ 
 \ *Name of the Attribute*\ 
\ **Help**\ 
 \ *Identifier of the attribute*\ 

Attribute Value
---------------
\ **Description**\ 
 \ *Value of the Attribute*\ 
\ **Help**\ 
 \ *Adempiere converts the (string) field values to the attribute data type.  Booleans (Yes-No) may have the values "true" and "false", the date format is YYYY-MM-DD*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Node Translation
----------------
\ **Description**\ 
 \ *Node Translation*\ 

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

Node
----
\ **Description**\ 
 \ *Workflow Node (activity), step or process*\ 
\ **Help**\ 
 \ *The Workflow Node indicates a unique step or process in a Workflow.*\ 

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

Transition
----------
\ **Description**\ 
 \ *Workflow Node Transition*\ 
\ **Help**\ 
 \ *The Next Nodes Tab defines the order or Nodes or Steps in a Workflow.*\ 

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

Node
----
\ **Description**\ 
 \ *Workflow Node (activity), step or process*\ 
\ **Help**\ 
 \ *The Workflow Node indicates a unique step or process in a Workflow.*\ 

Next Node
---------
\ **Description**\ 
 \ *Next Node in workflow*\ 
\ **Help**\ 
 \ *The Next Node indicates the next step or task in this Workflow.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

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

Std User Workflow
-----------------
\ **Description**\ 
 \ *Standard Manual User Approval Workflow*\ 
\ **Help**\ 
 \ *If selected, only documents with an open status (drafted, in progress, approved, rejected, invalid) and standard user actions (prepare, complete, approve, reject) are allowed to continue.  Use this to prevent having to define details on how automatic processes (unlock, invalidate, post, re-activate) and when the document is closed for normal user action (completed, waiting, closed, voided, reversed).*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Previous Node
-------------

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

Node
----
\ **Description**\ 
 \ *Workflow Node (activity), step or process*\ 
\ **Help**\ 
 \ *The Workflow Node indicates a unique step or process in a Workflow.*\ 

Next Node
---------
\ **Description**\ 
 \ *Next Node in workflow*\ 
\ **Help**\ 
 \ *The Next Node indicates the next step or task in this Workflow.*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Transition Code
---------------
\ **Description**\ 
 \ *Code resulting in TRUE of FALSE*\ 
\ **Help**\ 
 \ *The transition is executed, if the code results in TRUE (or is empty)*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Std User Workflow
-----------------
\ **Description**\ 
 \ *Standard Manual User Approval Workflow*\ 
\ **Help**\ 
 \ *If selected, only documents with an open status (drafted, in progress, approved, rejected, invalid) and standard user actions (prepare, complete, approve, reject) are allowed to continue.  Use this to prevent having to define details on how automatic processes (unlock, invalidate, post, re-activate) and when the document is closed for normal user action (completed, waiting, closed, voided, reversed).*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Condition
---------
\ **Description**\ 
 \ *Workflow Node Transition Condition*\ 
\ **Help**\ 
 \ *Optional restriction of transition of one node to the next. The (string) value is converted to the datatype.  Booleans (Yes-No) are represented by "true" and "false", the date format is YYYY-mm-DD*\ 

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

Node Transition
---------------
\ **Description**\ 
 \ *Workflow Node Transition*\ 
\ **Help**\ 
 \ *The Next Nodes Tab defines the order or Nodes or Steps in a Workflow.*\ 

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

And/Or
------
\ **Description**\ 
 \ *Logical operation: AND or OR*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Operation
---------
\ **Description**\ 
 \ *Compare Operation*\ 

Value
-----
\ **Description**\ 
 \ *Condition Value*\ 

Value To
--------
\ **Description**\ 
 \ *Value To*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 
