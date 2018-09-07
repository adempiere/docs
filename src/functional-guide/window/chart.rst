
.. _functional-guide/window/chart:

=====
Chart
=====

Chart Definition

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Chart
-----

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Chart Type
----------
\ **Description**\ 
 \ *Type fo chart to render*\ 

Window Height
-------------

Display Legend
--------------
\ **Description**\ 
 \ *Display chart legend*\ 
\ **Help**\ 
 \ *Toggles the display of the chart legend*\ 

Orientation
-----------
\ **Description**\ 
 \ *The orientation of the chart.*\ 

Domain Label
------------
\ **Description**\ 
 \ *Label for the domain axis.*\ 

Range Label
-----------
\ **Description**\ 
 \ *Label for the range axis.*\ 

Time Series
-----------
\ **Description**\ 
 \ *The domain data for the chart is organised by time.*\ 
\ **Help**\ 
 \ *A time series chart will automatically group and restrict the data by the time unit and scope specified.*\ 

Time Unit
---------
\ **Description**\ 
 \ *The unit of time for grouping chart data.*\ 

Time Scope
----------
\ **Description**\ 
 \ *The number of time units to include the chart result.*\ 

Datasource
----------

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

Chart
-----

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

Sql FROM
--------
\ **Description**\ 
 \ *SQL FROM clause*\ 
\ **Help**\ 
 \ *The Select Clause indicates the SQL FROM clause to use for selecting the record for a measure calculation. It can have JOIN clauses. Do not include the FROM itself.*\ 

Sql WHERE
---------
\ **Description**\ 
 \ *Fully qualified SQL WHERE clause*\ 
\ **Help**\ 
 \ *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*\ 

Series Column
-------------

Category Column
---------------
\ **Description**\ 
 \ *Fully qualified data category column*\ 
\ **Help**\ 
 \ *The Category Column determines how the chart data is grouped*\ 

Date Column
-----------
\ **Description**\ 
 \ *Fully qualified date column*\ 
\ **Help**\ 
 \ *The Date Column indicates the date to be used when calculating this measurement*\ 

Time Offset
-----------
\ **Description**\ 
 \ *Number of time units to offset displayed chart data from the current date.*\ 
\ **Help**\ 
 \ *For example an offset of -12 with a chart time unit of Month will result in previous year data being displayed.*\ 

Value Column
------------
\ **Description**\ 
 \ *Fully qualified data value column*\ 
\ **Help**\ 
 \ *The Value Column contains the value data for the chart*\ 

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
