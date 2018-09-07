
.. _functional-guide/window/performanceratio:

=================
Performance Ratio
=================

Maintain Performance Ratios

Help
====
Calculation instruction for a ratio

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Ratio
-----
\ **Description**\ 
 \ *Performance Ratio*\ 
\ **Help**\ 
 \ *Calculation instruction set  for a performance ratio*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Element
-------
\ **Description**\ 
 \ *Performance Ratio Element*\ 
\ **Help**\ 
 \ *Individual calculation instruction for a ratio*\ 

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

Ratio
-----
\ **Description**\ 
 \ *Performance Ratio*\ 
\ **Help**\ 
 \ *Calculation instruction set  for a performance ratio*\ 

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

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Operand
-------
\ **Description**\ 
 \ *Ratio Operand*\ 
\ **Help**\ 
 \ *Operand how data is calculated.  If it is the first in the series, 'minus' will create a negative value, otherwise ignored.*\ 

Element Type
------------
\ **Description**\ 
 \ *Ratio Element Type*\ 
\ **Help**\ 
 \ *Type of data used for the calculation*\ 

Measure Calculation
-------------------
\ **Description**\ 
 \ *Calculation method for measuring performance*\ 
\ **Help**\ 
 \ *The Measure Calculation indicates the method of measuring performance.*\ 

Constant Value
--------------
\ **Description**\ 
 \ *Constant value*\ 

Ratio Used
----------
\ **Description**\ 
 \ *Performance Ratio Used*\ 
\ **Help**\ 
 \ *Existing Performance Ratio to be used in the calculation.  Make sure that the Ratio is not self-referencing (loop).*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 
