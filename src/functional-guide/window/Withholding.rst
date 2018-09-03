
.. _window-withholding:

===========
Withholding
===========

Define Withholding

Help
====
The Withholding Window defines withholding information for business partners.

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Withholding
-----------
\ **Description**\ 
 \ *Define Withholding (Beta)*\ 
\ **Help**\ 
 \ *The Withholding Tab defines any withholding information for this business partner.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Withholding
-----------
\ **Description**\ 
 \ *Withholding type defined*\ 
\ **Help**\ 
 \ *The Withholding indicates the type of withholding to be calculated.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Mandatory Withholding
---------------------
\ **Description**\ 
 \ *Monies must be withheld*\ 
\ **Help**\ 
 \ *The Mandatory Withholding checkbox indicates that monies must be withheld from this employee.*\ 

Temporary exempt
----------------
\ **Description**\ 
 \ *Temporarily do not withhold taxes*\ 
\ **Help**\ 
 \ *The Temporary Exempt checkbox indicates that for a limited time, taxes will not be withheld for this employee.*\ 

Exempt reason
-------------
\ **Description**\ 
 \ *Reason for not withholding*\ 
\ **Help**\ 
 \ *The Exempt Reason indicates the reason that monies are not withheld from this employee.*\ 
