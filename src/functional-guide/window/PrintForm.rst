
.. _window-printform:

==========
Print Form
==========

Maintain Print Forms (Invoices, Checks, ..) used

Help
====
Define the documents you use for this Client/Organnization.  Note that the check format is defined in the Bank (Account) Window.
The highest priotity has the Print Format, you define on a Document Type (example specific Export Invoice format). The next level is the set of Print Formats, you defined for the organziation of the document printed. The default is the set of Print Formats defines for all organizations of the Client (Organization=*).

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Print Form
----------
\ **Description**\ 
 \ *Maintain Print Form (Invoices, Checks, ..) information*\ 
\ **Help**\ 
 \ *The selection determines what Print Format is used to print a particular Form for your Organization.*\ 

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

Order Print Format
------------------
\ **Description**\ 
 \ *Print Format for Orders, Quotes, Offers*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Order Mail Text
---------------
\ **Description**\ 
 \ *Email text used for sending order acknowledgements or quotations*\ 
\ **Help**\ 
 \ *Standard email template used to send acknowledgements or quotations as attachments.*\ 

Shipment Print Format
---------------------
\ **Description**\ 
 \ *Print Format for Shipments, Receipts, Pick Lists*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Shipment Mail Text
------------------
\ **Description**\ 
 \ *Email text used for sending delivery notes*\ 
\ **Help**\ 
 \ *Standard email template used to send delivery notes as attachments.*\ 

Invoice Print Format
--------------------
\ **Description**\ 
 \ *Print Format for printing Invoices*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Invoice Mail Text
-----------------
\ **Description**\ 
 \ *Email text used for sending invoices*\ 
\ **Help**\ 
 \ *Standard email template used to send invoices as attachments.*\ 

Remittance Print Format
-----------------------
\ **Description**\ 
 \ *Print Format for separate Remittances*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Remittance Mail Text
--------------------
\ **Description**\ 
 \ *Email text used for sending payment remittances*\ 
\ **Help**\ 
 \ *Standard email template used to send remittances as attachments.*\ 

Project Print Format
--------------------
\ **Description**\ 
 \ *Standard Project Print Format*\ 
\ **Help**\ 
 \ *Standard Project Print Format*\ 

Project Mail Text
-----------------
\ **Description**\ 
 \ *Standard text for Project EMails*\ 
\ **Help**\ 
 \ *Standard text for Project EMails*\ 

Distribution Order Print Format
-------------------------------
\ **Description**\ 
 \ *Print Format for printing Distribution Order*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Distribution Order Mail Text
----------------------------
\ **Description**\ 
 \ *Email text used for sending Distribution Order*\ 
\ **Help**\ 
 \ *Standard email template used to send Manufacturing Order as attachments.*\ 

Manufacturing Order Print Format
--------------------------------
\ **Description**\ 
 \ *Print Format for printing Manufacturing Order*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Manufacturing Order Mail Text
-----------------------------
\ **Description**\ 
 \ *Email text used for sending Manufacturing Order*\ 
\ **Help**\ 
 \ *Standard email template used to send Manufacturing Order as attachments.*\ 
