
.. _window-webposterminal:

================
Web POS Terminal
================


.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Terminal
--------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Auto Lock
---------
\ **Description**\ 
 \ *Whether to automatically lock the terminal when till is closed*\ 

Locked
------
\ **Description**\ 
 \ *Whether the terminal is locked*\ 

Lock Time
---------
\ **Description**\ 
 \ *Time in minutes the terminal should be kept in a locked state.*\ 

Last Lock Time
--------------
\ **Description**\ 
 \ *Last time at which the terminal was locked*\ 

UnlockingTime
-------------
\ **Description**\ 
 \ *Time at which the terminal should be unlocked*\ 

Template BPartner
-----------------
\ **Description**\ 
 \ *BPartner that is to be used as template when new customers are created*\ 

Printer Name
------------
\ **Description**\ 
 \ *Name of the Printer*\ 
\ **Help**\ 
 \ *Internal (Operating System) Name of the Printer; Please mote that the printer name may be different on different clients. Enter a printer name, which applies to ALL clients (e.g. printer on a server). 
If none is entered, the default printer is used. You specify your default printer when you log in. You can also change the default printer in Preferences.*\ 

Purchase Pricelist
------------------
\ **Description**\ 
 \ *Price List used by this Business Partner*\ 
\ **Help**\ 
 \ *Identifies the price list used by a Vendor for products purchased by this organization.*\ 

Sales Pricelist
---------------

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Card Transfer Type
------------------

Card Bank Account
-----------------
\ **Description**\ 
 \ *Bank Account on which card transactions will be processed*\ 

Transfer Card trx to
--------------------
\ **Description**\ 
 \ *Cash Book on which to transfer all Card transactions*\ 

Transfer Card trx to
--------------------
\ **Description**\ 
 \ *Bank account on which to transfer Card transactions*\ 

Cash Book Transfer Type
-----------------------
\ **Description**\ 
 \ *Where the money in the cash book should be transfered to. Either a Bank Account or another Cash Book*\ 

Cash Book
---------
\ **Description**\ 
 \ *Cash Book for recording petty cash transactions*\ 
\ **Help**\ 
 \ *The Cash Book identifies a unique cash book.  The cash book is used to record cash transactions.*\ 

Cash BPartner
-------------
\ **Description**\ 
 \ *BPartner to be used for Cash transactions*\ 

Transfer Cash trx to
--------------------
\ **Description**\ 
 \ *Cash Book on which to transfer all Cash transactions*\ 

Transfer Cash trx to
--------------------
\ **Description**\ 
 \ *Bank Account on which to transfer all Cash transactions*\ 

Check Transfer Type
-------------------

Check Bank Account
------------------
\ **Description**\ 
 \ *Bank Account to be used for processing Check transactions*\ 

Transfer Check trx to
---------------------
\ **Description**\ 
 \ *Cash Book on which to transfer all Check transactions*\ 

Tranfer Check trx to
--------------------
\ **Description**\ 
 \ *Bank account on which to transfer Check transactions*\ 
