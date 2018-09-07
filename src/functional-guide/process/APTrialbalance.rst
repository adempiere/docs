
.. _process-aptrialbalance:

================
AP Trial balance
================

Trial Balance for a period or date range

Help
====
Select a Period (current period if empty) or enter a Account Date Range. If an account is selected, the balance is calculated based on the account type and the primary calendar of the client (i.e. for revenue/expense accounts from the beginning of the year). If no account is selected, the balance is the sum of all transactions before the selected account range or first day of the period selected. You can select an alternative Reporting Hierarchy.

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

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
The Range checkbox indicates that this parameter is a range of values.

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Reporting Hierarchy
-------------------
\ **Description**\ 
 \ *Optional Reporting Hierarchy - If not selected the default hierarchy trees are used.*\ 
\ **Help**\ 
 \ *Reporting Hierarchy allows you to select different Hierarchies/Trees for the report.
Accounting Segments like Organization, Account, Product may have several hierarchies to accomodate different views on the business.*\ 
