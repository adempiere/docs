
.. _functional-guide/window/window-budgetcontrol:

==============
Budget Control
==============

Maintain Budget Controls

Help
====
Budget Control allows you to restrict the use of expenditures, commitments (Purchase Orders) and reservations (Requisitions). If defined, you mey not be able to approve Requisitions, Purchse Orders, or AP Invoices.

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Budget Control
--------------
\ **Description**\ 
 \ *Maintain Budget Controls*\ 
\ **Help**\ 
 \ *Budget Control allows you to restrict the use of expenditures, commitments (Purchase Orders) and reservations (Requisitions). If defined, you mey not be able to approve Requisitions, Purchse Orders, or AP Invoices.*\ 

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

Budget
------
\ **Description**\ 
 \ *General Ledger Budget*\ 
\ **Help**\ 
 \ *The General Ledger Budget identifies a user defined budget.  These can be used in reporting as a comparison against your actual amounts.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Commitment Type
---------------
\ **Description**\ 
 \ *Create Commitment and/or Reservations for Budget Control*\ 
\ **Help**\ 
 \ *The Posting Type Commitments is created when posting Purchase Orders; The Posting Type Reservation is created when posting Requisitions.  This is used for budgetary control.*\ 

Before Approval
---------------
\ **Description**\ 
 \ *The Check is before the (manual) approval*\ 
\ **Help**\ 
 \ *If selected, the Budget Approval is before manual approvals - i.e. is only approved if budget is available.  This may cause that the use of the budget is delayed (after the approval)*\ 

Control Scope
-------------
\ **Description**\ 
 \ *Scope of the Budget Control*\ 
