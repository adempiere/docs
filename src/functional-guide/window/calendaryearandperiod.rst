
.. _functional-guide/window/calendaryearandperiod:

========================
Calendar Year and Period
========================

Maintain Calendars Years Periods

Help
====
The Calendar Year and Periods defines the calendars that will be used for period control and reporting. You can also define non-standard calendars (e.g. business year from July to June).

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Calendar
--------
\ **Description**\ 
 \ *Define your calendar*\ 
\ **Help**\ 
 \ *The Calendar Tab defines each calendar that will be used by an Organization.*\ 

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

Year
----
\ **Description**\ 
 \ *Define Calendar Year*\ 
\ **Help**\ 
 \ *The Year Window is used to define each year for the specified calendar.*\ 

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

Calendar
--------
\ **Description**\ 
 \ *Accounting Calendar Name*\ 
\ **Help**\ 
 \ *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*\ 

Year
----
\ **Description**\ 
 \ *The Fiscal Year*\ 
\ **Help**\ 
 \ *The Year identifies the accounting year for a calendar.*\ 

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

Create Periods
--------------
\ **Description**\ 
 \ *Create 12 standard calendar periods.*\ 
\ **Help**\ 
 \ *Creates 12 calendar month long standard periods from the specified start date.  If no start date is specified, 1st of Jan will be used.  The period name will be generated from the start date of each period using the java SimpleDateFormat pattern provided.*\ 

Period
------
\ **Description**\ 
 \ *Define Calendar Periods*\ 
\ **Help**\ 
 \ *The Period Tab defines a Period No, Name and Start Date for each Calendar Year.  Each period begins on the defined Start Date and ends one day prior to the next period's Start Date.*\ 

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

Year
----
\ **Description**\ 
 \ *Calendar Year*\ 
\ **Help**\ 
 \ *The Year uniquely identifies an accounting year for a calendar.*\ 

Period No
---------
\ **Description**\ 
 \ *Unique Period Number*\ 
\ **Help**\ 
 \ *The Period No identifies a specific period for this year. Each period is defined by a start and end date.  Date ranges for a calendar and year cannot overlap.*\ 

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

Period Type
-----------
\ **Description**\ 
 \ *Period Type*\ 
\ **Help**\ 
 \ *The Period Type indicates the type (Standard or Adjustment) of period.*\ 

Open/Close All
--------------
\ **Description**\ 
 \ *Change Period Status for all Period Controls of this Period*\ 

Period Control
--------------
\ **Description**\ 
 \ *Define Period Control*\ 
\ **Help**\ 
 \ *The Period Control Tab displays the status of a Period (Never Opened, Opened, Closed).*\ 

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

Period
------
\ **Description**\ 
 \ *Period of the Calendar*\ 
\ **Help**\ 
 \ *The Period indicates an exclusive range of dates for a calendar.*\ 

Document BaseType
-----------------
\ **Description**\ 
 \ *Logical type of document*\ 
\ **Help**\ 
 \ *The Document Base Type identifies the base or starting point for a document.  Multiple document types may share a single document base type.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Period Status
-------------
\ **Description**\ 
 \ *Current state of this period*\ 
\ **Help**\ 
 \ *The Period Status indicates the current status for this period.  For example 'Closed', 'Open', 'Never Opened'.*\ 

Period Action
-------------
\ **Description**\ 
 \ *Action taken for this period*\ 
\ **Help**\ 
 \ *The Period Action indicates the action to be taken for this period.  For example 'Close Period' or 'Open Period'.*\ 

Open/Close
----------
\ **Description**\ 
 \ *Change Period Status*\ 

Non Business Day
----------------
\ **Description**\ 
 \ *Define Non Business Days*\ 
\ **Help**\ 
 \ *The Non Business Days Tab defines those days to exclude when calculating the due date for given payment terms.  For example, if an invoice terms was Net 10 days and the Invoice Date was 2/17/2000 the due date would be 2/27/2000.  If 2/27/2000 was defined as a non business day then the due date  on the Invoice would be 2/28/2000.*\ 

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

Calendar
--------
\ **Description**\ 
 \ *Accounting Calendar Name*\ 
\ **Help**\ 
 \ *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*\ 

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

Date
----
\ **Description**\ 
 \ *Date when business is not conducted*\ 
\ **Help**\ 
 \ *The Date field identifies a calendar date on which business will not be conducted.*\ 
