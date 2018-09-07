
.. _functional-guide/process/process-drp_calculatedistributionplan:

===========================
Calculate Distribution Plan
===========================

Distribution Resource Planning (DRP) is a method used in business administration for planning orders within a supply chain. 

Help
====
Distribution Resource Planning (DRP) is a method used in business administration for planning orders within a supply chain. 

DRP enables the user to set certain inventory control parameters (like a safety stock) and calculate the time-phased inventory requirements.

DRP uses several variables:
the on-hand inventory at the end of a period.
the backordered demand at the end of a period.
the required quantity of product needed at the beginning of a period.
the constrained quantity of product available at the beginning of a period.
the recommended order quantity at the beginning of a period.

DRP needs the following information:
the demand in a future period.
the scheduled receipts at the beginning of a period.
the safety stock requirement for a period.
the on-hand inventory at the beginning of a period.

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

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 
