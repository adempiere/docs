
.. _functional-guide/process/c_posreversethesalestransaction:

=============================
Reverse The Sales Transaction
=============================

This process allows reverse the sales transaction

Parameters
==========

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Invoice Partner
---------------
\ **Description**\ 
 \ *Business Partner to be invoiced*\ 
\ **Help**\ 
 \ *If empty the shipment business partner will be invoiced*\ 

Cancelled
---------
\ **Description**\ 
 \ *The transaction was cancelled*\ 

Ship/Receipt Confirmation
-------------------------
\ **Description**\ 
 \ *Require Ship or Receipt Confirmation before processing*\ 
\ **Help**\ 
 \ *The processing of the Shipment (Receipt) requires Ship (Receipt) Confirmation. Note that shipments for automatic documents like POS/Warehouse Orders cannot have confirmations!*\ 
