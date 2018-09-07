
.. _functional-guide/process/process-m_pricelistcreate:

=================
Create Price List
=================

Create Prices based on parameters of this version

Help
====
Create Prices for this pricelist version in the sequence of the Discount Schema Price List.
Lines with a higher sequence overwrite existing prices.  The sequence should be from generic to specific.

Parameters
==========

Delete old/existing records
---------------------------
\ **Description**\ 
 \ *Otherwise records will be added*\ 

.. note::
    The field must have a value for the record to be saved to the database.
