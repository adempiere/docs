
.. _process-sb_inoutgeneratefromorderline:

=============================
SB_InOutGenerateFromOrderLine
=============================

Generate and print Shipments from open Orders

Help
====
Shipments for open Orders are created based on the delivery rule of the Order and the relative order priority.  If a Promise Date is selected only orders up to (including) the date are selected.
If several Orders of a business partner have the same location, the orders can be consolidated into one Shipment.
You can also include orders who have outstanding confirmations (e.g. ordered=10 - not confirmed shipments=4 - would create a new shipment of 6 if available).

Parameters
==========

Shipment Date
-------------
\ **Description**\ 
 \ *Date printed on shipment*\ 
\ **Help**\ 
 \ *The Shipment Date indicates the date printed on the shipment.*\ 

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

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 
