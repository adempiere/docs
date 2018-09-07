
.. _functional-guide/process/process-m_generatemovement:

=================
Generate Movement
=================

Generate and print Movement from open Distribution Orders

Help
====
Movement for open Distribution Orders are created based on the delivery rule of the Distribution Order and the relative order priority.  If a Promise Date is selected only orders up to (including) the date are selected.
If several Distribution Orders of a business partner have the same location, the Distribution orders can be consolidated into one Movement.
You can also include Distibution orders who have outstanding confirmations (e.g. ordered=10 - not confirmed movements=4 - would create a new movement of 6 if available).

Parameters
==========

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Movement Date
-------------
\ **Description**\ 
 \ *Date a product was moved in or out of inventory*\ 
\ **Help**\ 
 \ *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*\ 

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
