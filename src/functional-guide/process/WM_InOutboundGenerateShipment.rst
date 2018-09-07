
.. _process-wm_inoutboundgenerateshipment:

======================================
Generate Shipments from Outbound Order
======================================

These process allows to generate multiple shipments for products that were succesfuly picked from an Outbound Order.

Help
====


Once the Picking process is completed the process to generate shipments can be fulfilled.

Parameters
==========

IsIncludeNotAvailable
---------------------
\ **Description**\ 
 \ *The product not available lines are include in the shipment*\ 

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
