
.. _functional-guide/process/m_product_uomconvert:

===================
Product UOM Convert
===================

Brack-up or repackage same Products with different UOM

Help
====
Example: "Product EA" has a defined UOM Conversion to "Product 6Pack" and vice versa.  
This is a one-step replacement for defining BOM and creating/processes a Production.

.. note::
    Beta functionality is not fully tested or completed.

Parameters
==========

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

To Product
----------
\ **Description**\ 
 \ *Product to be converted to (must have UOM Conversion defined to From Product)*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
