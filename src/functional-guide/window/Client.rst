
.. _window-client:

======
Client
======

Maintain Clients/Tenants

Help
====
The Client is the highest level of an independent business entity.  Each Client will have one or more Organizations reporting to it.  Each Client defines the accounting parameters (Accounting Schema, Tree definition, Non Monetary UOM's). To create new Clients, run the Initial Client Setup with the System Administrator Role.
Do not create a new client in this window, but use "Initial Client Setup" to set up the required security and access rules. If you create a new client here, you will not be able to view it and also the required client infrastructure would not have been set up.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Client
------
\ **Description**\ 
 \ *Client/Tenant Definition*\ 
\ **Help**\ 
 \ *The Client Definition Tab defines a unique client.
Do not create a new client in this window, but use "Initial Client Setup" (System Administrator Role) to set up the required security and access rules. If you create a new client here, you will not be able to view it and also the required client infrastructure would not have been set up.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

Fields
======

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Use Beta Functions
------------------
\ **Description**\ 
 \ *Enable the use of Beta Functionality*\ 
\ **Help**\ 
 \ *The exact scope of Beta Functionality is listed in the release note.  It is usually not recommended to enable Beta functionality in production environments.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Multi Lingual Documents
-----------------------
\ **Description**\ 
 \ *Documents are Multi Lingual*\ 
\ **Help**\ 
 \ *If selected, you enable multi lingual documents and need to maintain translations for entities used in documents (examples: Products, Payment Terms, ...).
Please note, that the base language is always English.*\ 

Auto Archive
------------
\ **Description**\ 
 \ *Enable and level of automatic Archive of documents*\ 
\ **Help**\ 
 \ *Adempiere allows to automatically create archives of Documents (e.g. Invoices) or Reports. You view the archived material with the Archive Viewer*\ 

Material Policy
---------------
\ **Description**\ 
 \ *Material Movement Policy*\ 
\ **Help**\ 
 \ *The Material Movement Policy determines how the stock is flowing (FiFo or LiFo) if a specific Product Instance was not selected.  The policy can not contradict the costing method (e.g. FiFo movement policy and LiFo costing method).*\ 

EMail Configuration
-------------------

Request EMail
-------------
\ **Description**\ 
 \ *EMail address to send automated mails from or receive mails for automated processing (fully qualified)*\ 
\ **Help**\ 
 \ *EMails for requests, alerts and escalation are sent from this email address as well as delivery information if the sales rep does not have an email account. The address must be filly qualified (e.g. joe.smith@company.com) and should be a valid address.*\ 

Request Folder
--------------
\ **Description**\ 
 \ *EMail folder to process incoming emails; if empty INBOX is used*\ 
\ **Help**\ 
 \ *Email folder used to read emails to process as requests, If left empty the default mailbox (INBOX) will be used. Requires IMAP services.*\ 

Request User
------------
\ **Description**\ 
 \ *User Name (ID) of the email owner*\ 
\ **Help**\ 
 \ *EMail user name for requests, alerts and escalation are sent from this email address as well as delivery information if the sales rep does not have an email account. Required, if your mail server requires authentification as well as for processing incoming mails.*\ 

Request User Password
---------------------
\ **Description**\ 
 \ *Password of the user name (ID) for mail processing*\ 

Server EMail
------------
\ **Description**\ 
 \ *Send EMail from Server*\ 
\ **Help**\ 
 \ *When selected, mail is sent from the server rather then the client.  This decreases availability.  You would select this when you do not want to enable email relay for the client addresses in your mail server.*\ 

Test EMail
----------
\ **Description**\ 
 \ *Test EMail Connection*\ 
\ **Help**\ 
 \ *Test EMail Connection based on info defined. An EMail is sent from the request user to the request user.  Also, the web store mail settings are tested.*\ 

Model Validation Classes
------------------------
\ **Description**\ 
 \ *List of data model validation classes separated by ;*\ 
\ **Help**\ 
 \ *List of classes implementing the interface org.compiere.model.ModelValidator, separated by semicolon.
The class is called for the client and allows to validate documents in the prepare stage and monitor model changes.*\ 

Cost Immediately
----------------
\ **Description**\ 
 \ *Update Costs immediately for testing*\ 
\ **Help**\ 
 \ *If selected, costs are updated immediately when a Cost Detail record is created (by matching or shipping).  Otherwise the costs are updated by batch or when the costs are needed for posting. You should select this only if you are testing,*\ 

Store Attachments On File System
--------------------------------

Windows Attachment Path
-----------------------

Unix Attachment Path
--------------------

Store Archive On File System
----------------------------

Windows Archive Path
--------------------

Unix Archive Path
-----------------

IsUseASP
--------

Client Info
-----------
\ **Description**\ 
 \ *Client Info*\ 
\ **Help**\ 
 \ *The Client Info Tab defines the details for each client.  The accounting rules and high level defaults are defined here. The Calendar is used to determine if a period is open or closed.*\ 

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

Discount calculated from Line Amounts
-------------------------------------
\ **Description**\ 
 \ *Payment Discount calculation does not include Taxes and Charges*\ 
\ **Help**\ 
 \ *If the payment discount is calculated from line amounts only, the tax and charge amounts are not included. This is e.g. business practice in the US.  If not selected the total invoice amount is used to calculate the payment discount.*\ 

Calendar
--------
\ **Description**\ 
 \ *Accounting Calendar Name*\ 
\ **Help**\ 
 \ *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*\ 

Primary Accounting Schema
-------------------------
\ **Description**\ 
 \ *Primary rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting  Schema defines the rules used accounting such as costing method, currency and calendar.*\ 

UOM for Volume
--------------
\ **Description**\ 
 \ *Standard Unit of Measure for Volume*\ 
\ **Help**\ 
 \ *The Standard UOM for Volume indicates the UOM to use for products referenced by volume in a document.*\ 

UOM for Weight
--------------
\ **Description**\ 
 \ *Standard Unit of Measure for Weight*\ 
\ **Help**\ 
 \ *The Standard UOM for Weight indicates the UOM to use for products referenced by weight in a document.*\ 

UOM for Length
--------------
\ **Description**\ 
 \ *Standard Unit of Measure for Length*\ 
\ **Help**\ 
 \ *The Standard UOM for Length indicates the UOM to use for products referenced by length in a document.*\ 

UOM for Time
------------
\ **Description**\ 
 \ *Standard Unit of Measure for Time*\ 
\ **Help**\ 
 \ *The Standard UOM for Time indicates the UOM to use for products referenced by time in a document.*\ 

Template B.Partner
------------------
\ **Description**\ 
 \ *Business Partner used for creating new Business Partners on the fly*\ 
\ **Help**\ 
 \ *When creating a new Business Partner from the Business Partner Search Field (right-click: Create), the selected business partner is used as a template, e.g. to define price list, payment terms, etc.*\ 

Product for Freight
-------------------

Days to keep Log
----------------
\ **Description**\ 
 \ *Number of days to keep the log entries*\ 
\ **Help**\ 
 \ *Older Log entries may be deleted*\ 

Organization Tree
-----------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting and security access (via role)*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting and security access (via role)*\ 

Menu Tree
---------
\ **Description**\ 
 \ *Tree of the menu*\ 
\ **Help**\ 
 \ *Menu access tree*\ 

BPartner Tree
-------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Product Tree
------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Project Tree
------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Sales Region Tree
-----------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Campaign Tree
-------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Activity Tree
-------------
\ **Description**\ 
 \ *Trees are used for (financial) reporting*\ 
\ **Help**\ 
 \ *Trees are used for (finanial) reporting*\ 

Logo
----

Logo Report
-----------

Logo Web
--------

Client Share
------------
\ **Description**\ 
 \ *Force (not) sharing of client/org entities*\ 
\ **Help**\ 
 \ *Business Partner can be either defined on Client level (shared) or on Org level (not shared).  You can define here of Products are always shared (i.e. always created under Organization "*") or if they are not shared (i.e. you cannot enter them with Organization "*").
The creation of  "Client and Org" shared records is the default and is ignored.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
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

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Share Type
----------
\ **Description**\ 
 \ *Type of sharing*\ 
\ **Help**\ 
 \ *Defines if a table is shared within a client or not.*\ 
