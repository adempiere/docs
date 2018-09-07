
.. _functional-guide/window/window-changeaudit:

============
Change Audit
============

Audit of data changes

Help
====
Log of data changes

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Change Audit
------------
\ **Description**\ 
 \ *Log of data changes*\ 
\ **Help**\ 
 \ *Log of data changes*\ 

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

Session
-------
\ **Description**\ 
 \ *User Session Online or Web*\ 
\ **Help**\ 
 \ *Online or Web Session Information*\ 

Transaction
-----------
\ **Description**\ 
 \ *Name of the transaction*\ 
\ **Help**\ 
 \ *Internal name of the transaction*\ 

Change Log
----------
\ **Description**\ 
 \ *Log of data changes*\ 
\ **Help**\ 
 \ *Log of data changes*\ 

Updated
-------
\ **Description**\ 
 \ *Date this record was updated*\ 
\ **Help**\ 
 \ *The Updated field indicates the date that this record was updated.*\ 

Updated By
----------
\ **Description**\ 
 \ *User who updated this records*\ 
\ **Help**\ 
 \ *The Updated By field indicates the user who updated this record.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 

Column
------
\ **Description**\ 
 \ *Column in the table*\ 
\ **Help**\ 
 \ *Link to the database column of the table*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Customization
-------------
\ **Description**\ 
 \ *The change is a customization of the data dictionary and can be applied after Migration*\ 
\ **Help**\ 
 \ *The migration "resets" the system to the current/original setting.  If selected you can save the customization and re-apply it.  Please note that you need to check, if your customization has no negative side effect in the new release.*\ 

Event Change Log
----------------
\ **Description**\ 
 \ *Type of Event in Change Log*\ 

Old Value
---------
\ **Description**\ 
 \ *The old file data*\ 
\ **Help**\ 
 \ *Old data overwritten in the field*\ 

New Value
---------
\ **Description**\ 
 \ *New field value*\ 
\ **Help**\ 
 \ *New data entered in the field*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Un-Do Changes
-------------
\ **Description**\ 
 \ *Undo changes*\ 
\ **Help**\ 
 \ *You can undo certain changes.*\ 

Re-Do Changes
-------------
\ **Description**\ 
 \ *Reapply changes*\ 
\ **Help**\ 
 \ *You can reapply certain changes.*\ 
