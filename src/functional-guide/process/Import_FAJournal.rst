
.. _process-import_fajournal:

=================
Import FA Journal
=================

Import FA Batch/Journal/Line

Help
====
The Parameters are default values for null import record values they do not overwrite any data.

.. note::
    Beta functionality is not fully tested or completed.

Parameters
==========

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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Only Validate Data
------------------
\ **Description**\ 
 \ *Validate the date and do not process*\ 

Import only if No Errors
------------------------
\ **Description**\ 
 \ *Only start the import, if there are no validation Errors*\ 

Delete old imported records
---------------------------
\ **Description**\ 
 \ *Before processing delete old imported records in the import table*\ 
