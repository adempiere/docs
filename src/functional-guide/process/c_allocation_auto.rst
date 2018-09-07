
.. _functional-guide/process/c_allocation_auto:

===============
Auto Allocation
===============

Automatic allocation of invoices to payments

Help
====
Try to allocate invoices to payments for a business partner or group.  You may want to reset existing allocations first.
The allocation is based on (1) payments entered with reference to invoices (2) payment selections (3) business partner balance (4) matching amount of invoice & payment.  Allocation is based on exact amount and includes AP/AR imvoices/payments.
Optionally as (5), you can enable to allocate payments to the oldest invoice. In this case, there might be an unallocated amount remaining.

Parameters
==========

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

AP - AR
-------
\ **Description**\ 
 \ *Include Receivables and/or Payables transactions*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Allocate Oldest First
---------------------
\ **Description**\ 
 \ *Allocate payments to the oldest invoice*\ 
\ **Help**\ 
 \ *Allocate payments to the oldest invoice. There might be an unallocated amount remaining.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
