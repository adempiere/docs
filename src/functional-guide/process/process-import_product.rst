
.. _functional-guide/process/process-import_product:

===============
Import Products
===============

Imports products from a file into the application

Help
====
Import Products will bring a file of products, in a predefined format into the application.
The Parameters are default values for null import record values, they do not overwrite any data.
If you select an existing price list and you have List, Standard, and Limit Price defined, they are directly created/updated.

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

Delete old imported records
---------------------------
\ **Description**\ 
 \ *Before processing delete old imported records in the import table*\ 

Price List Version
------------------
\ **Description**\ 
 \ *Identifies a unique instance of a Price List*\ 
\ **Help**\ 
 \ *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*\ 
