
.. _functional-guide/window/window-performancegoal:

================
Performance Goal
================

Define Performance Goals

Help
====
The Performance Goal Window allows you to define performance goals or all, a role or a user

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Performance Goal
----------------
\ **Description**\ 
 \ *Performance Goal*\ 
\ **Help**\ 
 \ *The Performance Goal Tab defines specific goals for performance.*\ 

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

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

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

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Color Schema
------------
\ **Description**\ 
 \ *Performance Color Schema*\ 
\ **Help**\ 
 \ *Visual representation of performance by color.  The Schema has often three levels (e.g. red-yellow-green).  Adempiere support two levels (e.g. red-green) or four levels (e.g. gray-bronze-silver-gold).  Note that Measures without a goal are represented white.  The percentages could be between 0 and unlimited (i.e. above 100%).*\ 

Parent Goal
-----------
\ **Description**\ 
 \ *Parent Goal*\ 
\ **Help**\ 
 \ *You can create a hierarchy of goals by linking the sub-goals to the summary goal.
The measures are automatically rolled up*\ 

Measure Target
--------------
\ **Description**\ 
 \ *Target value for measure*\ 
\ **Help**\ 
 \ *The Measure Target indicates the target or goal for this measure.  It is used as in comparing against the actual measures*\ 

Measure
-------
\ **Description**\ 
 \ *Concrete Performance Measurement*\ 
\ **Help**\ 
 \ *The Measure identifies a concrete, measurable indicator of performance.  For example, sales dollars, prospects contacted.*\ 

Date From
---------
\ **Description**\ 
 \ *Starting date for a range*\ 
\ **Help**\ 
 \ *The Date From indicates the starting date of a range.*\ 

Date To
-------
\ **Description**\ 
 \ *End date of a date range*\ 
\ **Help**\ 
 \ *The Date To indicates the end date of a range (inclusive)*\ 

Measure Scope
-------------
\ **Description**\ 
 \ *Performance Measure Scope*\ 
\ **Help**\ 
 \ *The scope of the goal can be broken down for initial display. 
Example: Scope is Year, Display is Month - the goal is entered as a yearly number, the display divides the goal by 12*\ 

Measure Display
---------------
\ **Description**\ 
 \ *Measure Scope initially displayed*\ 

Chart Type
----------
\ **Description**\ 
 \ *Type fo chart to render*\ 

Measure Actual
--------------
\ **Description**\ 
 \ *Actual value that has been measured.*\ 
\ **Help**\ 
 \ *The Measure Actual indicates the actual measured value. The measured values are used in determining if a performance goal has been met*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Performance Goal
----------------
\ **Description**\ 
 \ *Target achievement from 0..1*\ 
\ **Help**\ 
 \ *The Goal Performance indicates the target achievement from 0 to 1.*\ 

Relative Weight
---------------
\ **Description**\ 
 \ *Relative weight of this step (0 = ignored)*\ 
\ **Help**\ 
 \ *The relative weight allows you to adjust the project cycle report based on probabilities.  For example, if you have a 1:10 chance in closing a contract when it is in the prospect stage and a 1:2 chance when it is in the contract stage, you may put a weight of 0.1 and 0.5 on those steps. This allows sales funnels or measures of completion of your project.*\ 

Restriction
-----------
\ **Description**\ 
 \ *Performance Goal Restriction*\ 
\ **Help**\ 
 \ *Restriction of the performance measure to the Organization, Business Partner or Product defined.
Example: The performance is only measured for HQ
The measure must support the data, otherwise it is ignored.*\ 

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

Goal
----
\ **Description**\ 
 \ *Performance Goal*\ 
\ **Help**\ 
 \ *The Performance Goal indicates what this users performance will be measured against.*\ 

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

Restriction Type
----------------
\ **Description**\ 
 \ *Goal Restriction Type*\ 
\ **Help**\ 
 \ *Enter one or more records per Goal Restriction Type (e.g. Org o1, o2)*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

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
