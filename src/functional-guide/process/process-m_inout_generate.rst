
.. _functional-guide/process/process-m_inout_generate:

==================
Generate Shipments
==================

Generate and print Shipments from open Orders

Help
====
Shipments for open Orders are created based on the delivery rule of the Order and the relative order priority.  If a Promise Date is selected only orders up to (including) the date are selected.
If several Orders of a business partner have the same location, the orders can be consolidated into one Shipment.
You can also include orders who have outstanding confirmations (e.g. ordered=10 - not confirmed shipments=4 - would create a new shipment of 6 if available).

Parameters
==========

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Shipment Date
-------------
\ **Description**\ 
 \ *Date printed on shipment*\ 
\ **Help**\ 
 \ *The Shipment Date indicates the date printed on the shipment.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Date Promised
-------------
\ **Description**\ 
 \ *Date Order was promised*\ 
\ **Help**\ 
 \ *The Date Promised indicates the date, if any, that an Order was promised for.*\ 

Orders with unconfirmed Shipments
---------------------------------
\ **Description**\ 
 \ *Generate shipments for Orders with open delivery confirmations?*\ 
\ **Help**\ 
 \ *You can also include orders who have outstanding confirmations (e.g. ordered=10 - not confirmed shipments=4 - would create a new shipment of 6 if available).*\ 

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Consolidate to one Document
---------------------------
\ **Description**\ 
 \ *Consolidate Lines into one Document*\ 
