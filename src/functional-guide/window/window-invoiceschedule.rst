
.. _functional-guide/window/window-invoiceschedule:

================
Invoice Schedule
================

Maintain Invoicing Schedule

Help
====
The Invoice Schedule Window defines the frequency and cut off dates for generating summary invoices.  If a customer requires a single invoice for multiple shipments you would define the appropriate invoice schedule and associate it with the Customer.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Invoice Schedule
----------------
\ **Description**\ 
 \ *Define Invoice Schedule*\ 
\ **Help**\ 
 \ *The Invoice Schedule Tab defines the frequency for which batch invoices will be generated for a Business Partner.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Amount Limit
------------
\ **Description**\ 
 \ *Send invoices only if the amount exceeds the limit*\ 
\ **Help**\ 
 \ *The Amount Limit checkbox indicates if invoices will be sent out if they are below the entered limit.*\ 

Amount
------
\ **Description**\ 
 \ *Amount*\ 
\ **Help**\ 
 \ *Amount*\ 

Invoice Frequency
-----------------
\ **Description**\ 
 \ *How often invoices will be generated*\ 
\ **Help**\ 
 \ *The Invoice Frequency indicates the frequency of invoice generation for a Business Partner.*\ 

Invoice on even weeks
---------------------
\ **Description**\ 
 \ *Send invoices on even weeks*\ 
\ **Help**\ 
 \ *The Invoice on Even Weeks checkbox indicates if biweekly invoices should be sent on even week numbers.*\ 

Invoice Week Day
----------------
\ **Description**\ 
 \ *Day to generate invoices*\ 
\ **Help**\ 
 \ *The Invoice Week Day indicates the day of the week to generate invoices.*\ 

Invoice weekday cutoff
----------------------
\ **Description**\ 
 \ *Last day in the week for shipments to be included*\ 
\ **Help**\ 
 \ *The Invoice Week Day Cutoff indicates the last day of the week a shipment must be made to be included in the invoice schedule.*\ 

Invoice Day
-----------
\ **Description**\ 
 \ *Day of Invoice Generation*\ 
\ **Help**\ 
 \ *The Invoice Day indicates the day of invoice generation.  If twice monthly, the second time is 15 days after this day.*\ 

Invoice day cut-off
-------------------
\ **Description**\ 
 \ *Last day for including shipments*\ 
\ **Help**\ 
 \ *The Invoice Day Cut Off indicates the last day for shipments to be included in the current invoice schedule.  For example, if the invoice schedule is defined for the first day of the month, the cut off day may be the 25th of the month.  An shipment on the 24th of May would be included in the invoices sent on June 1st but a shipment on the 26th would be included in the invoices sent on July 1st.*\ 
