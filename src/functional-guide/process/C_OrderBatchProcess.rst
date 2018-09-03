
.. _process-c_orderbatchprocess:

===================
Order Batch Process
===================

Process Orders in Batch

Help
====
Based on the selection criteria, the orders are processed using the document action selected.  Make sure that the document action is valid for the documents.

Parameters
==========

Target Document Type
--------------------
\ **Description**\ 
 \ *Target document type for conversing documents*\ 
\ **Help**\ 
 \ *You can convert document types (e.g. from Offer to Order or Invoice).  The conversion is then reflected in the current type.  This processing is initiated by selecting the appropriate Document Action.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Document Status
---------------
\ **Description**\ 
 \ *The current status of the document*\ 
\ **Help**\ 
 \ *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Delivered
---------

Invoiced
--------
\ **Description**\ 
 \ *Is this invoiced?*\ 
\ **Help**\ 
 \ *If selected, invoices are created*\ 

Date Ordered
------------
\ **Description**\ 
 \ *Date of Order*\ 
\ **Help**\ 
 \ *Indicates the Date an item was ordered.*\ 

.. note::
    The Range checkbox indicates that this parameter is a range of values.

Document Action
---------------
\ **Description**\ 
 \ *The targeted status of the document*\ 
\ **Help**\ 
 \ *You find the current status in the Document Status field. The options are listed in a popup*\ 

.. note::
    The field must have a value for the record to be saved to the database.
