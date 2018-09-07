
.. _functional-guide/process/process-rv_t_combinedagingrevalue:

==============================
Aging with payments (revalued)
==============================

Aging Report with payments (revalued)

Help
====
The aging report allows you to report on Open Items (Invoices and Payments) as at the date selected. Select the aging buckets, you want to have in your report. All amounts are converted to the currency of the select accounting schema, using the rate for the selected currency conversion type and as at the statement date. If you do not select a Statement Date, the system date is used. If you do not list the individual invoices, the Due Date is the earliest due date for the business partner and the Due Days are the average due days of all invoices.* 

Parameters
==========

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

Statement date
--------------
\ **Description**\ 
 \ *Date of the statement*\ 
\ **Help**\ 
 \ *The Statement Date field defines the date of the statement.*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

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

List Sources
------------
\ **Description**\ 
 \ *List Report Line Sources*\ 
\ **Help**\ 
 \ *List the Source Accounts for Summary Accounts selected*\ 

Include Payments
----------------
\ **Description**\ 
 \ *Include payments in the aging report*\ 
