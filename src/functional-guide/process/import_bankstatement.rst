
.. _functional-guide/process/import_bankstatement:

=====================
Import Bank Statement
=====================

Import Bank Statement

Help
====
The Parameters are default values for null import record values, they do not overwrite any data.

Parameters
==========

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Delete old imported records
---------------------------
\ **Description**\ 
 \ *Before processing delete old imported records in the import table*\ 
