
.. _functional-guide/window/window-advertisement:

=============
Advertisement
=============

Web Advertisement

Help
====
Maintain Advertisements on the Web

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Advertisement
-------------
\ **Description**\ 
 \ *Web Advertisement*\ 
\ **Help**\ 
 \ *Advertisement on the Web*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Publication Status
------------------
\ **Description**\ 
 \ *Status of Publication*\ 
\ **Help**\ 
 \ *Used for internal documentation*\ 

Version
-------
\ **Description**\ 
 \ *Version of the table definition*\ 
\ **Help**\ 
 \ *The Version indicates the version of this table definition.*\ 

Image URL
---------
\ **Description**\ 
 \ *URL of  image*\ 
\ **Help**\ 
 \ *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*\ 

Advertisement Text
------------------
\ **Description**\ 
 \ *Text of the Advertisement*\ 
\ **Help**\ 
 \ *The text of the advertisement with optional HTML tags. The HTML tags are not checked for correctness and may impact the remaining page.*\ 

Counter Count
-------------
\ **Description**\ 
 \ *Web Counter Count Management*\ 
\ **Help**\ 
 \ *Web Counter Information*\ 

Click Count
-----------
\ **Description**\ 
 \ *Web Click Management*\ 
\ **Help**\ 
 \ *Web Click Management*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

Valid to
--------
\ **Description**\ 
 \ *Valid to including this date (last day)*\ 
\ **Help**\ 
 \ *The Valid To date indicates the last day of a date range*\ 

Web Parameter 1
---------------
\ **Description**\ 
 \ *Web Site Parameter 1 (default: header image)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam1 - By default, it is positioned on the upper left side with 130 pixel width.*\ 

Web Parameter 2
---------------
\ **Description**\ 
 \ *Web Site Parameter 2 (default index page)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam2 - By default, it is positioned after the header on the web store index page.*\ 

Web Parameter 3
---------------
\ **Description**\ 
 \ *Web Site Parameter 3 (default left - menu)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam3 - By default, it is positioned at the end in the menu column with 130 pixel width.*\ 

Web Parameter 4
---------------
\ **Description**\ 
 \ *Web Site Parameter 4 (default footer left)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam4 - By default, it is positioned on the left side of the footer with 130 pixel width.*\ 
