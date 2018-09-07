
.. _functional-guide/process/rv_t_aging:

=====
Aging
=====

Aging Report

Help
====
The aging report allows you to report on Open Items (Invoices). Select the aging buckets, you want to have in your report. If you select a currency, you get only invoices of that currency, otherwise the amounts are converted to your primary accounting currency. If you do not select a Statement Date, the system date is used to calculate the buckets. If you do not list the individual invoices, the Due Date is the earliest due date for the business partner and the Due Days are the average due days of all invoices.

If you select an Account Date the report will generate the Aging as of that date. The report will exclude documents after the selected date.

For example: A customer has one invoice for $100 with the Account Date of 03/31/08 and one payment for $100 with the Account Date of 05/01/08. The report will show the following balances based on the Account Date selected: 03/15/08= 0; 04/15/08=100; 05/15/08 = 0.

Parameters
==========

Statement date
--------------
\ **Description**\ 
 \ *Date of the statement*\ 
\ **Help**\ 
 \ *The Statement Date field defines the date of the statement.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

List Invoices
-------------
\ **Description**\ 
 \ *Include List of Invoices*\ 
