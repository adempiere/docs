
.. _functional-guide/window/window-distributionlist:

=================
Distribution List
=================

Maintain Distribution Lists

Help
====
Distribution list contain business partners and a distribution quantity or ratio for creating Orders

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Distribution List
-----------------
\ **Description**\ 
 \ *Distribution Lists allow to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution list contain business partners and a distribution quantity or ratio for creating Orders*\ 

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

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Total Ratio
-----------
\ **Description**\ 
 \ *Total of relative weight in a distribution*\ 
\ **Help**\ 
 \ *The total relative weight of an distribution. If the total of all ratios is 100, it is the same as percent.*\ 

Distribution Line
-----------------
\ **Description**\ 
 \ *Distribution List Line with Business Partner and Quantity/Percentage*\ 
\ **Help**\ 
 \ *The distribution can be based on Ratio, fixed quantity or both.
If the ratio and quantity is not 0, the quantity is calculated based on the ratio, but with the Quantity as a minimum.*\ 

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

Distribution List
-----------------
\ **Description**\ 
 \ *Distribution Lists allow to distribute products to a selected list of partners*\ 
\ **Help**\ 
 \ *Distribution list contain business partners and a distribution quantity or ratio for creating Orders*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Ratio
-----
\ **Description**\ 
 \ *Relative Ratio for Distributions*\ 
\ **Help**\ 
 \ *The relative weight of an distribution. If the total of all ratios is 100, it is the same as percent.*\ 

Minimum Quantity
----------------
\ **Description**\ 
 \ *Minimum quantity for the business partner*\ 
\ **Help**\ 
 \ *If a minimum quantity is defined, and the quantity is based on the percentage is lower, the minimum quantity is used.*\ 
