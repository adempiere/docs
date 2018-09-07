
.. _window-role:

====
Role
====

Maintain User Responsibilities

Help
====
The Role Window allows you to define the different roles that users of this system will have.  Roles control access to windows, tasks, reports, etc. For a client an Administrator and User role are predefined. You may add additional roles to control access for specific functionality or data.
You can add users to the role.
Note that access information is cached and requires re-login or reset of cache.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Role
----
\ **Description**\ 
 \ *Define responsibility roles*\ 
\ **Help**\ 
 \ *Define the role and add the client and organizations the role has access to. You can give users access to this role and modify the access of this role to windows, forms, processes and reports as well as tasks. 
If the Role User Level is Manual, the assigned acces rights are not automatically updated (e.g. if a role has a restricted number of Windows/Processes it can access). You need to add organizational access unless the role has access to all organizations. The SuperUser and the user creating a new role are assigned to the role automatically.  
If you select an Organization Tree, the user has access to the leaves of  summary organizations.
Note: You cannot change the System Administrator role.*\ 

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

User Level
----------
\ **Description**\ 
 \ *System Client Organization*\ 
\ **Help**\ 
 \ *The User Level field determines if users of this Role will have access to System level data, Organization level data, Client level data or Client and Organization level data.*\ 

Manual
------
\ **Description**\ 
 \ *This is a manual process*\ 
\ **Help**\ 
 \ *The Manual check box indicates if the process will done manually.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Approval Amount
---------------
\ **Description**\ 
 \ *The approval amount limit for this role*\ 
\ **Help**\ 
 \ *The Approval Amount field indicates the amount limit this Role has for approval of documents.*\ 

Approve own Documents
---------------------
\ **Description**\ 
 \ *Users with this role can approve their own documents*\ 
\ **Help**\ 
 \ *If a user cannot approve their own documents (orders, etc.), it needs to be approved by someone else.*\ 

UserDiscount
------------

Supervisor
----------
\ **Description**\ 
 \ *Supervisor for this user/organization - used for escalation and approval*\ 
\ **Help**\ 
 \ *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*\ 

Menu Tree
---------
\ **Description**\ 
 \ *Tree of the menu*\ 
\ **Help**\ 
 \ *Menu access tree*\ 

Overwrite Price Limit
---------------------
\ **Description**\ 
 \ *Overwrite Price Limit if the Price List  enforces the Price Limit*\ 
\ **Help**\ 
 \ *The Price List allows to enforce the Price Limit. If set, a user with this role can overwrite the price limit (i.e. enter any price).*\ 

Preference Level
----------------
\ **Description**\ 
 \ *Determines what preferences the user can set*\ 
\ **Help**\ 
 \ *Preferences allow you to define default values.  If set to None, you cannot set any preference nor value preference. Only if set to Client, you can see the Record Info Change Log.*\ 

Maintain Change Log
-------------------
\ **Description**\ 
 \ *Maintain a log of changes*\ 
\ **Help**\ 
 \ *If selected, a log of all changes is maintained.*\ 

Show Accounting
---------------
\ **Description**\ 
 \ *Users with this role can see accounting information*\ 
\ **Help**\ 
 \ *This allows to prevent access to any accounting information.*\ 

Access all Orgs
---------------
\ **Description**\ 
 \ *Access all Organizations (no org access control) of the client*\ 
\ **Help**\ 
 \ *When selected, the role has access to all organizations of the client automatically. This also increases performance where you have many organizations.*\ 

Organization Tree
-----------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting and security access (via role)*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting and security access (via role)*\ 

Use User Org Access
-------------------
\ **Description**\ 
 \ *Use Org Access defined by user instead of Role Org Access*\ 
\ **Help**\ 
 \ *You can define the access to Organization either by Role or by User.  You would select this, if you have many organizations.*\ 

Can Report
----------
\ **Description**\ 
 \ *Users with this role can create reports*\ 
\ **Help**\ 
 \ *You can restrict the ability to report on data.*\ 

Can Export
----------
\ **Description**\ 
 \ *Users with this role can export data*\ 
\ **Help**\ 
 \ *You can restrict the ability to export data from Adempiere.*\ 

Can Load
--------
\ **Description**\ 
 \ *Users with this role can load data*\ 
\ **Help**\ 
 \ *You can restrict the ability to load data from Adempiere.*\ 

Personal Lock
-------------
\ **Description**\ 
 \ *Allow users with role to lock access to personal records*\ 
\ **Help**\ 
 \ *If enabled, the user with the role can prevent access of others to personal records.  If a record is locked, only the user or people who can read personal locked records can see the record.*\ 

Personal Access
---------------
\ **Description**\ 
 \ *Allow access to all personal records*\ 
\ **Help**\ 
 \ *Users of this role have access to all records locked as personal.*\ 

Confirm Query Records
---------------------
\ **Description**\ 
 \ *Require Confirmation if more records will be returned by the query (If not defined 500)*\ 
\ **Help**\ 
 \ *Enter the number of records the query will return without confirmation to avoid unnecessary system load.  If 0, the system default of 500 is used.*\ 

Max Query Records
-----------------
\ **Description**\ 
 \ *If defined, you cannot query more records as defined - the query criteria needs to be changed to query less records*\ 
\ **Help**\ 
 \ *Enter the number of records a user will be able to query to avoid unnecessary system load.  If 0, no restrictions are imposed.*\ 

Connection Profile
------------------
\ **Description**\ 
 \ *How a Java Client connects to the server(s)*\ 
\ **Help**\ 
 \ *Depending on the connection profile, different protocols are used and tasks are performed on the server rather then the client. Usually the user can select different profiles, unless it is enforced by the User or Role definition. The User level profile overwrites the Role based profile.*\ 

Allow Info Account
------------------

Allow Info Asset
----------------

Allow Info BPartner
-------------------

Allow Info CashJournal
----------------------

Allow Info InOut
----------------

Allow Info Invoice
------------------

Allow Info Order
----------------

Allow Info Payment
------------------

Allow Info Product
------------------

Allow Info Resource
-------------------

Allow Info Schedule
-------------------

Allow Info CRP
--------------

Allow Info MRP
--------------

Allow XLS View
--------------

Allow HTML View
---------------

Org Access
----------
\ **Description**\ 
 \ *Maintain Role Org Access*\ 
\ **Help**\ 
 \ *Add the client and organizations the user has access to. Entries here are ignored, if User Org Access is selected or the role has access to all roles.
Note that access information is cached and requires re-login or reset of cache.*\ 

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

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

User Assignment
---------------
\ **Description**\ 
 \ *Users with this Role*\ 
\ **Help**\ 
 \ *The User Assignment Tab displays Users who have been defined for this Role.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Window Access
-------------
\ **Description**\ 
 \ *Window Access*\ 
\ **Help**\ 
 \ *The Window Access Tab defines the Windows and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Window
------
\ **Description**\ 
 \ *Data entry or display window*\ 
\ **Help**\ 
 \ *The Window field identifies a unique Window in the system.*\ 

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

Process Access
--------------
\ **Description**\ 
 \ *Process Access*\ 
\ **Help**\ 
 \ *The Process Access Tab defines the Processes and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Process
-------
\ **Description**\ 
 \ *Process or Report*\ 
\ **Help**\ 
 \ *The Process field identifies a unique Process or Report in the system.*\ 

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

Form Access
-----------
\ **Description**\ 
 \ *Form Access*\ 
\ **Help**\ 
 \ *The Form Access Tab defines the Forms and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Special Form
------------
\ **Description**\ 
 \ *Special Form*\ 
\ **Help**\ 
 \ *The Special Form field identifies a unique Special Form in the system.*\ 

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

Browse Access
-------------
\ **Description**\ 
 \ *Browse Access*\ 
\ **Help**\ 
 \ *The Browse Access Tab defines the Browses and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Smart Browse
------------

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

Workflow Access
---------------
\ **Description**\ 
 \ *Workflow Access*\ 
\ **Help**\ 
 \ *The Workflow Access Tab defines the Workflows and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

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

Task Access
-----------
\ **Description**\ 
 \ *Task Access*\ 
\ **Help**\ 
 \ *The Task Access Tab defines the Task and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

OS Task
-------
\ **Description**\ 
 \ *Operation System Task*\ 
\ **Help**\ 
 \ *The Task field identifies a Operation System Task in the system.*\ 

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

Dashboard Access
----------------
\ **Description**\ 
 \ *Dashboard*\ 
\ **Help**\ 
 \ *TheDashboard Access Tab defines the Dashboard and type of access that this Role is granted.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Dashboard Content
-----------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Document Action Access
----------------------
\ **Description**\ 
 \ *Define access to document type / document action / role combinations.*\ 
\ **Help**\ 
 \ *Define access to document type / document action / role combinations.*\ 

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Reference List
--------------
\ **Description**\ 
 \ *Reference List based on Table*\ 
\ **Help**\ 
 \ *The Reference List field indicates a list of reference values from a database tables.  Reference lists populate drop down list boxes in data entry screens*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Included roles
--------------

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Included Role
-------------
