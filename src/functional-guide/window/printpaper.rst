
.. _functional-guide/window/printpaper:

===========
Print Paper
===========

Maintain Print Paper

Help
====
Printer Paper Size, Orientation and Margins

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Print Paper
-----------
\ **Description**\ 
 \ *Maintain Print Paper*\ 
\ **Help**\ 
 \ *Printer Paper Size, Orientation and Margins. 
The Validation Code contains the Media Size name. The names of the media sizes correspond to those in the IPP 1.1 RFC 2911 - http://www.ietf.org/rfc/rfc2911.txt  
If the name is not found, the SizeX/Y with the dimension is used. Size and dimension are ignored, if a valid media size name is used.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Landscape
---------
\ **Description**\ 
 \ *Landscape orientation*\ 

Validation code
---------------
\ **Description**\ 
 \ *Validation Code*\ 
\ **Help**\ 
 \ *The Validation Code displays the date, time and message of the error.*\ 

Dimension Units
---------------
\ **Description**\ 
 \ *Units of Dimension*\ 

Size X
------
\ **Description**\ 
 \ *X (horizontal) dimension size*\ 
\ **Help**\ 
 \ *Size of X (horizontal) dimension in Units*\ 

Size Y
------
\ **Description**\ 
 \ *Y (vertical) dimension size*\ 
\ **Help**\ 
 \ *Size of Y (vertical) dimension in Units*\ 

Top Margin
----------
\ **Description**\ 
 \ *Top Space in 1/72 inch*\ 
\ **Help**\ 
 \ *Space on top of a page in 1/72 inch*\ 

Bottom Margin
-------------
\ **Description**\ 
 \ *Bottom Space in 1/72 inch*\ 
\ **Help**\ 
 \ *Space on bottom of a page in 1/72 inch*\ 

Left Margin
-----------
\ **Description**\ 
 \ *Left Space in 1/72 inch*\ 
\ **Help**\ 
 \ *Space on left side of a page in 1/72 inch*\ 

Right Margin
------------
\ **Description**\ 
 \ *Right Space in 1/72 inch*\ 
\ **Help**\ 
 \ *Space on right side of a page in 1/72 inch*\ 

Set Print Format
----------------
\ **Description**\ 
 \ *Set for all Print Formats with same Landscape/Portrait*\ 
