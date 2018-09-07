
.. _functional-guide/window/click:

=====
Click
=====

Maintain Web Click

Help
====
Web Clicks allow you to track number of clicks.  Example:
&lt;a href="http://www.adempiere.com/wstore/click?http://www.adempiere.de" target="_blank"&gt;
where "http://www.adempiere.com/wstore/click" is your side and "http://www.adempiere.de" is the target page.
If you created a web click for http://www.adempiere.de, you will be able to see details and total of web clicks.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Click
-----
\ **Description**\ 
 \ *Click Count*\ 
\ **Help**\ 
 \ *Define the link / target you want to track.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Target URL
----------
\ **Description**\ 
 \ *URL for the Target*\ 
\ **Help**\ 
 \ *URL of the Target Site*\ 

Counter
-------
\ **Description**\ 
 \ *Count Value*\ 
\ **Help**\ 
 \ *Number counter*\ 

Individual Click
----------------
\ **Description**\ 
 \ *Details of someone clicking on the link*\ 

.. note::
    The Read Only indicates that this field may only be Read.  It may not be updated.

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

Click Count
-----------
\ **Description**\ 
 \ *Web Click Management*\ 
\ **Help**\ 
 \ *Web Click Management*\ 

Created
-------
\ **Description**\ 
 \ *Date this record was created*\ 
\ **Help**\ 
 \ *The Created field indicates the date that this record was created.*\ 

Target URL
----------
\ **Description**\ 
 \ *URL for the Target*\ 
\ **Help**\ 
 \ *URL of the Target Site*\ 

Referrer
--------
\ **Description**\ 
 \ *Referring web address*\ 

Remote Addr
-----------
\ **Description**\ 
 \ *Remote Address*\ 
\ **Help**\ 
 \ *The Remote Address indicates an alternative or external address.*\ 

Remote Host
-----------
\ **Description**\ 
 \ *Remote host Info*\ 

Accept Language
---------------
\ **Description**\ 
 \ *Language accepted based on browser information*\ 

User Agent
----------
\ **Description**\ 
 \ *Browser Used*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 
