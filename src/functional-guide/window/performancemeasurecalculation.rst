
.. _functional-guide/window/performancemeasurecalculation:

===============================
Performance Measure Calculation
===============================

Define how you calculate your performance measures

Help
====
The Performance Measure Calculation defines how performance measures will be calculated. 
The sql needs to return a single value.  Please check examples.
The date trestriction is defined in the Goal. 
Any restrictions for Organizations, Business Partners, Products, etc. are  as Performance Goal Restrictions.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Performance Measure Calculation
-------------------------------
\ **Description**\ 
 \ *Maintain your Performance Measure Calculation*\ 
\ **Help**\ 
 \ *The Performance Measure Calculation defines how performance measures will be calculated. See examples.
The SELECT definition must contain the SELECT and FROM keywords in upper case, the WHERE definition must contain the WHERE keyword in upper case.  The main table must not have an alias!  The WHERE clause can only contain values of the main table (e.g. when selecting from Header and lines, only header variables can be used in the where clause) and be fully qualified if there is more then one table.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Sql SELECT
----------
\ **Description**\ 
 \ *SQL SELECT clause*\ 
\ **Help**\ 
 \ *The Select Clause indicates the SQL SELECT clause to use for selecting the record for a measure calculation. Do not include the SELECT itself.*\ 

Sql WHERE
---------
\ **Description**\ 
 \ *Fully qualified SQL WHERE clause*\ 
\ **Help**\ 
 \ *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*\ 

Date Column
-----------
\ **Description**\ 
 \ *Fully qualified date column*\ 
\ **Help**\ 
 \ *The Date Column indicates the date to be used when calculating this measurement*\ 

Org Column
----------
\ **Description**\ 
 \ *Fully qualified Organization column (AD_Org_ID)*\ 
\ **Help**\ 
 \ *The Organization Column indicates the organization to be used in calculating this measurement.*\ 

B.Partner Column
----------------
\ **Description**\ 
 \ *Fully qualified Business Partner key column (C_BPartner_ID)*\ 
\ **Help**\ 
 \ *The Business Partner Column indicates the Business Partner to use when calculating this measurement*\ 

Product Column
--------------
\ **Description**\ 
 \ *Fully qualified Product column (M_Product_ID)*\ 
\ **Help**\ 
 \ *The Product Column indicates the product to use to use when calculating this measurement.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Key Column
----------
\ **Description**\ 
 \ *Key Column for Table*\ 
