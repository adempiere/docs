
.. _process-m_costdetailgeneratecosttransaction:

=========================
Generate Cost Transaction
=========================

Generate Cost Transaction

Help
====
The Generate Cost Transaction process allows the detailed cost calculation and cost generation  beginning from a date. If you have not yet set COGs Adjustment, you should execute this process before a period's end in order to fix the cost layers.

Parameters
==========

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Cost Type
---------
\ **Description**\ 
 \ *Type of Cost (e.g. Current, Plan, Future)*\ 
\ **Help**\ 
 \ *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*\ 

Cost Element
------------
\ **Description**\ 
 \ *Product Cost Element*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
The Range checkbox indicates that this parameter is a range of values.
