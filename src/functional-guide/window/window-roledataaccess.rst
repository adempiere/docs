
.. _functional-guide/window/window-roledataaccess:

================
Role Data Access
================

Maintain Data Access Rules

Help
====
Maintain Data Access Roles of Roles/Responsibilties.
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
 \ *Role with Data Access Restriction*\ 
\ **Help**\ 
 \ *Select Role for with Data Access Restrictions.
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

Table Access
------------
\ **Description**\ 
 \ *Maintain Table Access*\ 
\ **Help**\ 
 \ *If listed here, the Role can(not) access all data of this table, even if the role has access to the functionality.
* If you Include Access to a table and select Read Only, you can only read data (otherwise full access).
* If you Exclude Access to a table and select Read Only, you can only read data (otherwise no access).
* Please note that table access rules here are in addition to the Data Access Levels defined for a Table and the User Level defined for a Role. These rules are evaulated first and you only need to define the exceptions to these rules here.

Note that access information is cached and requires re-login or reset of cache. Be aware that if you use Include rules, that you need to include also several supporting entiries. As an alternative, grant access only to functionality required.*\ 

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Exclude
-------
\ **Description**\ 
 \ *Exclude access to the data - if not selected Include access to the data*\ 
\ **Help**\ 
 \ *If selected (excluded), the role cannot access the data specified.  If not selected (included), the role can ONLY access the data specified. Exclude items represent a negative list (i.e. you don't have access to the listed items). Include items represent a positive list (i.e. you only have access to the listed items).
* You would usually  not mix Exclude and Include. If you have one include rule in your list, you would only have access to that item anyway.*\ 

Access Type
-----------
\ **Description**\ 
 \ *The type of access for this rule*\ 
\ **Help**\ 
 \ *If you restrict Access to the entity, you also cannot Report or Export it (i.e. to have access is a requirement that you can report or export the data).  The Report and Export rules are further restrictions if you have access.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

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

Column Access
-------------
\ **Description**\ 
 \ *Maintain Column Access*\ 
\ **Help**\ 
 \ *If listed here, the Role can(not) access the column of this table, even if the role has access to the functionality.
* If you Include Access to a column and select Read Only, you can only read data (otherwise full access).
* If you Exclude Access to a column and select Read Only, you can only read data (otherwise no access).
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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

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

Exclude
-------
\ **Description**\ 
 \ *Exclude access to the data - if not selected Include access to the data*\ 
\ **Help**\ 
 \ *If selected (excluded), the role cannot access the data specified.  If not selected (included), the role can ONLY access the data specified. Exclude items represent a negative list (i.e. you don't have access to the listed items). Include items represent a positive list (i.e. you only have access to the listed items).
* You would usually  not mix Exclude and Include. If you have one include rule in your list, you would only have access to that item anyway.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

Record Access
-------------
\ **Description**\ 
 \ *Maintain Record Access*\ 
\ **Help**\ 
 \ *You create Record Access records by enabling "Personal Lock" for the administrative role and Ctl-Lock (holding the Ctrl key while clicking on the Lock button).

If listed here, the Role can(not) access the data records of this table, even if the role has access to the functionality.
* If you Include Access to a record and select Read Only, you can only read data (otherwise full access).
* If you Exclude Access to a recorf and select Read Only, you can only read data (otherwise no access).
Note that access information is cached and requires re-login or reset of cache.*\ 

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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Exclude
-------
\ **Description**\ 
 \ *Exclude access to the data - if not selected Include access to the data*\ 
\ **Help**\ 
 \ *If selected (excluded), the role cannot access the data specified.  If not selected (included), the role can ONLY access the data specified. Exclude items represent a negative list (i.e. you don't have access to the listed items). Include items represent a positive list (i.e. you only have access to the listed items).
* You would usually  not mix Exclude and Include. If you have one include rule in your list, you would only have access to that item anyway.*\ 

Read Only
---------
\ **Description**\ 
 \ *Field is read only*\ 
\ **Help**\ 
 \ *The Read Only indicates that this field may only be Read.  It may not be updated.*\ 

Dependent Entities
------------------
\ **Description**\ 
 \ *Also check access in dependent entities*\ 
\ **Help**\ 
 \ *Also dependent entities are included.  Please be aware, that enabling this rule has severe consequences and that this is only wanted in some circumstances.
Example Rule: "Include Payment Term Immediate with Dependent Entities"
* Primary effect: users with this role can only select the payment term Immediate
* Secondary effect (dependent entities): users with this role can see only invoices/orders with the payment term immediate.*\ 
