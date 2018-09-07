
.. _functional-guide/window/servicelevel:

=============
Service Level
=============

Maintain Service Levels

Help
====
Service Levels are generated when an invoice with products based on revenue recognition rules are generated.  You need to update the actual service level by adding an additional line.

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Service Level
-------------
\ **Description**\ 
 \ *View Service Level*\ 
\ **Help**\ 
 \ *The service level is automatically created when creating an invoice with products using revenue recognition based on service levels.*\ 

.. note::
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

Revenue Recognition Plan
------------------------
\ **Description**\ 
 \ *Plan for recognizing or recording revenue*\ 
\ **Help**\ 
 \ *The Revenue Recognition Plan identifies a unique Revenue Recognition Plan.*\ 

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

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *Quantity of product or service invoiced*\ 
\ **Help**\ 
 \ *The Quantity Invoiced indicates the total quantity of a product or service that has been invoiced.*\ 

Quantity Provided
-----------------
\ **Description**\ 
 \ *Quantity of service or product provided*\ 
\ **Help**\ 
 \ *The Quantity Provided indicates the total quantity of a product or service that has been received by the customer.*\ 

Process Now
-----------

Service Level Line
------------------
\ **Description**\ 
 \ *Maintain Service Levels*\ 
\ **Help**\ 
 \ *Add new service level lines to change the recognized amount*\ 

.. note::
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

Service Level
-------------
\ **Description**\ 
 \ *Product Revenue Recognition Service Level*\ 
\ **Help**\ 
 \ *The Service Level defines a unique Service Level.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Service date
------------
\ **Description**\ 
 \ *Date service was provided*\ 
\ **Help**\ 
 \ *The Service Date indicates the date that the service was provided.*\ 

Quantity Provided
-----------------
\ **Description**\ 
 \ *Quantity of service or product provided*\ 
\ **Help**\ 
 \ *The Quantity Provided indicates the total quantity of a product or service that has been received by the customer.*\ 
