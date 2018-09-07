
.. _functional-guide/window/forecastrule:

=============
Forecast Rule
=============

The Forecasting Rules define the business logic to calculate the forecast according with a previously implemented algorithm

Help
====
These rules are used in the Forecast Definition to set the rules and forecast calculation ranges.


The rules can be identified by a name and a description, to identify the different forecast calculation algorithms.


The calculus java class: it’s the implementation of the java interface for each forecast rule.


Currently the system supports multiple forecast calculation implementations, which are executed by the forecast engine.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Forecast Rule
-------------
\ **Description**\ 
 \ *Forecast Rules define the business logic according to a previously implemented algorithm.*\ 
\ **Help**\ 
 \ *These rules are used by the Forecast definition  to determine the forecast calculations.*\ 

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

Calculation Class
-----------------
\ **Description**\ 
 \ *Java Class for calculation, implementing Interface Measure*\ 
\ **Help**\ 
 \ *The Calculation Class indicates the Java Class used for calculating measures.


Forecast Engine.


The forecasting engine has the function to expose the implementations for each forecast rule, the interface ForecastRule.java is the interface to implement each forecast rule.


The developers can use this interface to implement their own calculation algorithms.
* *\ 
