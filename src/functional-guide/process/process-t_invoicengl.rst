
.. _functional-guide/process/process-t_invoicengl:

==============================
Invoice Not Realized Gain/Loss
==============================

Invoice Not Realized Gain & Loss Report

Help
====
The Report lists not fully paid invoices with open amount, the GL amounts and the revalued amounts.  If an invoice is partially paid, the percentage of the open amount is used to calculate the revaluation amount.
If you select a currency, only invoices of that currency are included; if you select Include All Currencies, all invoices are included and you can use the report to reconcile your AP/AR accounts.
If you select a GL Document Type, a GL Journal is created. 
Note that the report only includes posted invoices.

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

Revaluation Conversion Type
---------------------------
\ **Description**\ 
 \ *Revaluation Currency Conversion Type*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Revaluation Date
----------------
\ **Description**\ 
 \ *Date of Revaluation*\ 

.. note::
    The field must have a value for the record to be saved to the database.

AP - AR
-------
\ **Description**\ 
 \ *Include Receivables and/or Payables transactions*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Include All Currencies
----------------------
\ **Description**\ 
 \ *Report not just foreign currency Invoices*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Revaluation Document Type
-------------------------
\ **Description**\ 
 \ *Document Type for Revaluation Journal*\ 
