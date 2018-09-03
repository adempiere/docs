
.. _window-projectold:

===========
Project Old
===========

Maintain Projects

Help
====
The Project Window is used to define the projects which will can be tracked by phases and tasks.

Window Type
-----------
\ **Transaction**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Project
-------
\ **Description**\ 
 \ *Define Project*\ 
\ **Help**\ 
 \ *The Project Tab is used to define the Value, Name and Description for each project.  It also is defines the tracks the amounts assigned to, committed to and used for this project. Note that when the project Type is changed, the Phases and Tasks are re-created.*\ 

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

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

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

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Line Level
----------
\ **Description**\ 
 \ *Project Line Level*\ 
\ **Help**\ 
 \ *Level on which Project Lines are maintained*\ 

Set Project Type
----------------
\ **Description**\ 
 \ *Set Project Type and for Service Projects copy Phases and Tasks of Project Type into Project*\ 
\ **Help**\ 
 \ **\ 

Standard Phase
--------------
\ **Description**\ 
 \ *Standard Phase of the Project Type*\ 
\ **Help**\ 
 \ *Phase of the project with standard performance information with standard work*\ 

Contract Date
-------------
\ **Description**\ 
 \ *The (planned) effective date of this document.*\ 
\ **Help**\ 
 \ *The contract date is used to determine when the document becomes effective. This is usually the contract date.  The contract date is used in reports and report parameters.*\ 

Finish Date
-----------
\ **Description**\ 
 \ *Finish or (planned) completion date*\ 
\ **Help**\ 
 \ *The finish date is used to indicate when the project is expected to be completed or has been completed.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

BPartner (Agent)
----------------
\ **Description**\ 
 \ *Business Partner (Agent or Sales Rep)*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Order Reference
---------------
\ **Description**\ 
 \ *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*\ 
\ **Help**\ 
 \ *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Planned Quantity
----------------
\ **Description**\ 
 \ *Planned quantity for this project*\ 
\ **Help**\ 
 \ *The Planned Quantity indicates the anticipated quantity for this project or project line*\ 

Planned Margin
--------------
\ **Description**\ 
 \ *Project's planned margin amount*\ 
\ **Help**\ 
 \ *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*\ 

Invoice Rule
------------
\ **Description**\ 
 \ *Invoice Rule for the project*\ 
\ **Help**\ 
 \ *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Committed Quantity
------------------
\ **Description**\ 
 \ *The (legal) commitment Quantity*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Invoiced Amount
---------------
\ **Description**\ 
 \ *The amount invoiced*\ 
\ **Help**\ 
 \ *The amount invoiced*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *The quantity invoiced*\ 

Project Balance
---------------
\ **Description**\ 
 \ *Total Project Balance*\ 
\ **Help**\ 
 \ *The project balance is the sum of all invoices and payments*\ 

Copy Details
------------
\ **Description**\ 
 \ *Copy Lines/Phases/Tasks from other Project*\ 

Close Project
-------------

Project Line
------------
\ **Description**\ 
 \ *Maintain Project Lines*\ 
\ **Help**\ 
 \ *Maintain Project Level Lines*\ 

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

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Planned Price
-------------
\ **Description**\ 
 \ *Planned price for this project line*\ 
\ **Help**\ 
 \ *The Planned Price indicates the anticipated price for this project line.*\ 

Planned Quantity
----------------
\ **Description**\ 
 \ *Planned quantity for this project*\ 
\ **Help**\ 
 \ *The Planned Quantity indicates the anticipated quantity for this project or project line*\ 

Get Price
---------
\ **Description**\ 
 \ *Get Price for Project Line based on Project Price List*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Planned Margin
--------------
\ **Description**\ 
 \ *Project's planned margin amount*\ 
\ **Help**\ 
 \ *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Committed Quantity
------------------
\ **Description**\ 
 \ *The (legal) commitment Quantity*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Invoiced Amount
---------------
\ **Description**\ 
 \ *The amount invoiced*\ 
\ **Help**\ 
 \ *The amount invoiced*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *The quantity invoiced*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Purchase Order
--------------
\ **Description**\ 
 \ *Purchase Order*\ 

Project Issue
-------------
\ **Description**\ 
 \ *Project Issues (Material, Labor)*\ 
\ **Help**\ 
 \ *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Phase
-----
\ **Description**\ 
 \ *Maintain Actual Project Phase*\ 
\ **Help**\ 
 \ *Actual Phase of the Project with Status information - generated from Phase of Project Type.*\ 

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

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Standard Phase
--------------
\ **Description**\ 
 \ *Standard Phase of the Project Type*\ 
\ **Help**\ 
 \ *Phase of the project with standard performance information with standard work*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

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

Complete
--------
\ **Description**\ 
 \ *It is complete*\ 
\ **Help**\ 
 \ *Indication that this is complete*\ 

Start Date
----------
\ **Description**\ 
 \ *First effective day (inclusive)*\ 
\ **Help**\ 
 \ *The Start Date indicates the first or starting date*\ 

End Date
--------
\ **Description**\ 
 \ *Last effective date (inclusive)*\ 
\ **Help**\ 
 \ *The End Date indicates the last date in this range.*\ 

Invoice Rule
------------
\ **Description**\ 
 \ *Invoice Rule for the project*\ 
\ **Help**\ 
 \ *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Generate Order
--------------
\ **Description**\ 
 \ *Generate Order from Project Phase*\ 
\ **Help**\ 
 \ *The Generate Order process will generate a new Order document based on the project phase or tasks. A price list and warehouse/service point must be defined on the project.  If a product is defined on phase level, the Phase information is used as the basis for the Order (milestone invoicing) - otherwise the individual tasks.*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Phase Line
----------
\ **Description**\ 
 \ *Project Lines of Phase*\ 
\ **Help**\ 
 \ *Maintain Project Lines on Phase Level*\ 

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

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Planned Price
-------------
\ **Description**\ 
 \ *Planned price for this project line*\ 
\ **Help**\ 
 \ *The Planned Price indicates the anticipated price for this project line.*\ 

Planned Quantity
----------------
\ **Description**\ 
 \ *Planned quantity for this project*\ 
\ **Help**\ 
 \ *The Planned Quantity indicates the anticipated quantity for this project or project line*\ 

Get Price
---------
\ **Description**\ 
 \ *Get Price for Project Line based on Project Price List*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Planned Margin
--------------
\ **Description**\ 
 \ *Project's planned margin amount*\ 
\ **Help**\ 
 \ *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Committed Quantity
------------------
\ **Description**\ 
 \ *The (legal) commitment Quantity*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Invoiced Amount
---------------
\ **Description**\ 
 \ *The amount invoiced*\ 
\ **Help**\ 
 \ *The amount invoiced*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *The quantity invoiced*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Purchase Order
--------------
\ **Description**\ 
 \ *Purchase Order*\ 

Project Issue
-------------
\ **Description**\ 
 \ *Project Issues (Material, Labor)*\ 
\ **Help**\ 
 \ *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Task
----
\ **Description**\ 
 \ *Actual Project Task*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 

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

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Standard Task
-------------
\ **Description**\ 
 \ *Standard Project Type Task*\ 
\ **Help**\ 
 \ *Standard Project Task in a Project Phase with standard effort*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

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

Invoice Rule
------------
\ **Description**\ 
 \ *Invoice Rule for the project*\ 
\ **Help**\ 
 \ *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Task Line
---------
\ **Description**\ 
 \ *Project Lines of Tasks*\ 
\ **Help**\ 
 \ *Maintain Project Lines of Tasks*\ 

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

Project Task
------------
\ **Description**\ 
 \ *Actual Project Task in a Phase*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Planned Price
-------------
\ **Description**\ 
 \ *Planned price for this project line*\ 
\ **Help**\ 
 \ *The Planned Price indicates the anticipated price for this project line.*\ 

Planned Quantity
----------------
\ **Description**\ 
 \ *Planned quantity for this project*\ 
\ **Help**\ 
 \ *The Planned Quantity indicates the anticipated quantity for this project or project line*\ 

Get Price
---------
\ **Description**\ 
 \ *Get Price for Project Line based on Project Price List*\ 

Planned Amount
--------------
\ **Description**\ 
 \ *Planned amount for this project*\ 
\ **Help**\ 
 \ *The Planned Amount indicates the anticipated amount for this project or project line.*\ 

Printed
-------
\ **Description**\ 
 \ *Indicates if this document / line is printed*\ 
\ **Help**\ 
 \ *The Printed checkbox indicates if this document or line will included when printing.*\ 

Planned Margin
--------------
\ **Description**\ 
 \ *Project's planned margin amount*\ 
\ **Help**\ 
 \ *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*\ 

Committed Amount
----------------
\ **Description**\ 
 \ *The (legal) commitment amount*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Committed Quantity
------------------
\ **Description**\ 
 \ *The (legal) commitment Quantity*\ 
\ **Help**\ 
 \ *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*\ 

Invoiced Amount
---------------
\ **Description**\ 
 \ *The amount invoiced*\ 
\ **Help**\ 
 \ *The amount invoiced*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *The quantity invoiced*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Purchase Order
--------------
\ **Description**\ 
 \ *Purchase Order*\ 

Project Issue
-------------
\ **Description**\ 
 \ *Project Issues (Material, Labor)*\ 
\ **Help**\ 
 \ *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Accounting
----------
\ **Description**\ 
 \ *Define Project Accounting*\ 
\ **Help**\ 
 \ *The Accounting Tab is used to define the Asset Account to use when a project is completed and the associated asset realized.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.

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

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Project Asset
-------------
\ **Description**\ 
 \ *Project Asset Account*\ 
\ **Help**\ 
 \ *The Project Asset account is the account used as the final asset account in capital projects*\ 

Work In Progress
----------------
\ **Description**\ 
 \ *Account for Work in Progress*\ 
\ **Help**\ 
 \ *The Work in Process account is the account used in capital projects until the project is completed*\ 
