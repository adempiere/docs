
.. _functional-guide/process/c_invoice_writeoff:

=====================
Receivables Write-Off
=====================

Write off open receivables

Help
====
Write-off receivables causes the invoices selected by the criteria to be marked as paid and the open invoice amount to be written off.  Alternatively you can create payments.

Parameters
==========

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

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Collection Status
-----------------
\ **Description**\ 
 \ *Invoice Collection Status*\ 
\ **Help**\ 
 \ *Status of the invoice collection process*\ 

Dunning Level
-------------

Maximum write-off per Invoice
-----------------------------
\ **Description**\ 
 \ *Maximum invoice amount to be written off in invoice currency*\ 

.. note::
    The field must have a value for the record to be saved to the database.

AP - AR
-------
\ **Description**\ 
 \ *Include Receivables and/or Payables transactions*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Date Invoiced
-------------
\ **Description**\ 
 \ *Date printed on Invoice*\ 
\ **Help**\ 
 \ *The Date Invoice indicates the date printed on the invoice.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
The Range checkbox indicates that this parameter is a range of values.

Simulation
----------
\ **Description**\ 
 \ *Performing the function is only simulated*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Create Payment
--------------

.. note::
    The field must have a value for the record to be saved to the database.

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 
