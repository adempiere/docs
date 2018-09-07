
.. _functional-guide/process/process-yearendclosing:

==============
YearEndClosing
==============

A Process to clear the account of costs and income

Help
====
This process is used at the end of the financial year to clear all cost and income accounts.
The destination account is selected as a parameter.
The process creates a GL Journal Batch with GL Journals for every account with a balance.
After completing the Journal Batch the balance of all income/cost accounts is zero, the transferred ammount corresponds to the gross revenue.

Parameters
==========

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

.. note::
    The field must have a value for the record to be saved to the database.

TargetAccount_ID
----------------

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

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

.. note::
    The field must have a value for the record to be saved to the database.

GL Category
-----------
\ **Description**\ 
 \ *General Ledger Category*\ 
\ **Help**\ 
 \ *The General Ledger Category is an optional, user defined method of grouping journal lines.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
