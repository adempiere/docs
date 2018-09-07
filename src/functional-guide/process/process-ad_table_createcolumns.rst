
.. _functional-guide/process/process-ad_table_createcolumns:

======================
Create Columns from DB
======================

Create Dictionary Columns of Table not existing as a Column but in the Database

Help
====
If you have added columns in the database to this table, this procedure creates the Column records in the Dictionary.  Please be aware, that they may deleted, if the entity type is not set to User.

Parameters
==========

Entity Type
-----------
\ **Description**\ 
 \ *Dictionary Entity Type; Determines ownership and synchronization*\ 
\ **Help**\ 
 \ *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Check all DB Tables
-------------------
\ **Description**\ 
 \ *Check not just this table*\ 

.. note::
    The field must have a value for the record to be saved to the database.
