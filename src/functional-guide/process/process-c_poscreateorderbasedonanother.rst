
.. _functional-guide/process/process-c_poscreateorderbasedonanother:

=============================
Create Order based on another
=============================

This process allows generate a new order on a new business partner.

Parameters
==========

Order Source
------------

.. note::
    The field must have a value for the record to be saved to the database.

Invoice Partner
---------------
\ **Description**\ 
 \ *Business Partner to be invoiced*\ 
\ **Help**\ 
 \ *If empty the shipment business partner will be invoiced*\ 

SO Sub Type
-----------
\ **Description**\ 
 \ *Sales Order Sub Type*\ 
\ **Help**\ 
 \ *The SO Sub Type indicates the type of sales order this document refers to.  This field only appears when the Document Base Type is Sales Order.  The selection made here will determine which documents will be generated when an order is processed and which documents must be generated manually or in batches.  
The following outlines this process.
SO Sub Type of \ **Standard Order**\  will generate just the \ **Order**\  document when the order is processed.  
The \ **Delivery Note**\ , \ **Invoice**\  and \ **Receipt**\  must be generated via other processes.  
SO Sub Type of \ **Warehouse Order**\  will generate the \ **Order**\  and \ **Delivery Note**\ . *  The \ **Invoice**\  and \ **Receipt**\  must be generated via other processes.
SO Sub Type of \ **Credit Order**\  will generate the \ **Order**\ , \ **Delivery Note**\  and \ **Invoice**\ . *  The \ **Receipt**\  must be generated via other processes.
SO Sub Type of \ **POS**\  (Point of Sale) will generate all document*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

Include Payments
----------------
\ **Description**\ 
 \ *Include payments in the aging report*\ 

Allocated
---------
\ **Description**\ 
 \ *Indicates if the payment has been allocated*\ 
\ **Help**\ 
 \ *The Allocated checkbox indicates if a payment has been allocated or associated with an invoice or invoices.*\ 
