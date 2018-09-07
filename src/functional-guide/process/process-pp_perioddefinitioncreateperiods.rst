
.. _functional-guide/process/process-pp_perioddefinitioncreateperiods:

==============
Create Periods
==============

Create calendar periods.

Help
====
This process creates the calendar periods, based on the period definition with an start date specified, if this date is not recorded, then Jan 01 will be the default. The period name is created based on the start date of each period using the Java SimpleDataFormat pattern.

Parameters
==========

Start Date
----------
\ **Description**\ 
 \ *First effective day (inclusive)*\ 
\ **Help**\ 
 \ *The Start Date indicates the first or starting date*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Number of Periods
-----------------

.. note::
    The field must have a value for the record to be saved to the database.

Date Format
-----------
\ **Description**\ 
 \ *Date format used in the input format*\ 
\ **Help**\ 
 \ *The date format is usually detected, but sometimes need to be defined.*\ 
