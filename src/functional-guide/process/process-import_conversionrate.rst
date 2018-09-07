
.. _functional-guide/process/process-import_conversionrate:

======================
Import Conversion Rate
======================

Import Currency Conversion Rate

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

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Create Reciprocal Rate
----------------------
\ **Description**\ 
 \ *Create Reciprocal Rate from current information*\ 
\ **Help**\ 
 \ *If selected, the imported USD->EUR rate is used to create/calculate the reciprocal rate EUR->USD.*\ 

Delete old imported records
---------------------------
\ **Description**\ 
 \ *Before processing delete old imported records in the import table*\ 
