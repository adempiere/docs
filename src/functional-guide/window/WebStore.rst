
.. _window-webstore:

=========
Web Store
=========

Define Web Store

Help
====
Define the web store setup.  

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Web Store
---------
\ **Description**\ 
 \ *Define Web Store*\ 
\ **Help**\ 
 \ *Define the web store settings. The web server context must be unique and determines the settings used in the actual transaction. The selected warehouse determines the organization.  The email settings are tested with the client email settings.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Web Context
-----------
\ **Description**\ 
 \ *Web Server Context - e.g. /wstore*\ 
\ **Help**\ 
 \ *Unique Web Server Context for this Web Store - will set context-root in application.xml.
The web context usually starts with / and needs to be a valid context name (not checked).*\ 

Stylesheet
----------
\ **Description**\ 
 \ *CSS (Stylesheet) used*\ 
\ **Help**\ 
 \ *Base Stylesheet (.css file) to use - if empty, the default (standard.css) is used. The Style sheet can be a URL.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Web Store Info
--------------
\ **Description**\ 
 \ *Web Store Header Information*\ 
\ **Help**\ 
 \ *Display HTML Info in the Web Store - by default in the header.*\ 

Web Store EMail
---------------
\ **Description**\ 
 \ *EMail address used as the sender (From)*\ 
\ **Help**\ 
 \ *The EMail address is used to send mails to users of the web store*\ 

Web Order EMail
---------------
\ **Description**\ 
 \ *EMail address to receive notifications when web orders were processed*\ 
\ **Help**\ 
 \ *When processing a web order, a confirmation is sent to the EMail address of the customer from the request EMail address copying this email address when entered.*\ 

WebStore User
-------------
\ **Description**\ 
 \ *User ID of the Web Store EMail address*\ 
\ **Help**\ 
 \ *User ID to connect to the Mail Server*\ 

WebStore Password
-----------------
\ **Description**\ 
 \ *Password of the Web Store EMail address*\ 
\ **Help**\ 
 \ *Password to connect to the Mail Server*\ 

EMail Header
------------
\ **Description**\ 
 \ *Header added to EMails*\ 
\ **Help**\ 
 \ *The header is added to every email.*\ 

EMail Footer
------------
\ **Description**\ 
 \ *Footer added to EMails*\ 
\ **Help**\ 
 \ *The footer is added to every email.*\ 

Menu Orders
-----------
\ **Description**\ 
 \ *Show Menu Orders*\ 

Menu Shipments
--------------
\ **Description**\ 
 \ *Show Menu Shipments*\ 

Menu Invoices
-------------
\ **Description**\ 
 \ *Show Menu Invoices*\ 

Menu Assets
-----------
\ **Description**\ 
 \ *Show Menu Assets*\ 

Menu Payments
-------------
\ **Description**\ 
 \ *Show Menu Payments*\ 

Menu RfQs
---------
\ **Description**\ 
 \ *Show Menu RfQs*\ 

Menu Requests
-------------
\ **Description**\ 
 \ *Show Menu Requests*\ 

Menu Registrations
------------------
\ **Description**\ 
 \ *Show Menu Registrations*\ 

Menu Interests
--------------
\ **Description**\ 
 \ *Show Menu Interests*\ 

Menu Contact
------------
\ **Description**\ 
 \ *Show Menu Contact*\ 

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

Web Parameter 5
---------------
\ **Description**\ 
 \ *Web Site Parameter 5 (default footer center)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam5 - By default, it is positioned in the center of the footer.*\ 

Web Parameter 6
---------------
\ **Description**\ 
 \ *Web Site Parameter 6 (default footer right)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam6 - By default, it is positioned on the right side of the footer.*\ 

Store Translation
-----------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Web Store
---------
\ **Description**\ 
 \ *A Web Store of the Client*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Web Store Info
--------------
\ **Description**\ 
 \ *Web Store Header Information*\ 
\ **Help**\ 
 \ *Display HTML Info in the Web Store - by default in the header.*\ 

EMail Header
------------
\ **Description**\ 
 \ *Header added to EMails*\ 
\ **Help**\ 
 \ *The header is added to every email.*\ 

EMail Footer
------------
\ **Description**\ 
 \ *Footer added to EMails*\ 
\ **Help**\ 
 \ *The footer is added to every email.*\ 

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

Web Parameter 5
---------------
\ **Description**\ 
 \ *Web Site Parameter 5 (default footer center)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam5 - By default, it is positioned in the center of the footer.*\ 

Web Parameter 6
---------------
\ **Description**\ 
 \ *Web Site Parameter 6 (default footer right)*\ 
\ **Help**\ 
 \ *The parameter could be used in the JSP page for variables like logos, passwords, URLs or entire HTML blocks. The access is via ctx.webParam6 - By default, it is positioned on the right side of the footer.*\ 

Web Store Message
-----------------
\ **Description**\ 
 \ *Definine Web Store Messages*\ 

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

Web Store
---------
\ **Description**\ 
 \ *A Web Store of the Client*\ 

Message Type
------------
\ **Description**\ 
 \ *Mail Message Type*\ 

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

Subject
-------
\ **Description**\ 
 \ *Email Message Subject*\ 
\ **Help**\ 
 \ *Subject of the EMail*\ 

Message
-------
\ **Description**\ 
 \ *EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 

Message 2
---------
\ **Description**\ 
 \ *Optional second part of the EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 

Message 3
---------
\ **Description**\ 
 \ *Optional third part of the EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 

Message Translation
-------------------

.. note::
    The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Mail Message
------------
\ **Description**\ 
 \ *Web Store Mail Message Template*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Subject
-------
\ **Description**\ 
 \ *Email Message Subject*\ 
\ **Help**\ 
 \ *Subject of the EMail*\ 

Message
-------
\ **Description**\ 
 \ *EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 

Message 2
---------
\ **Description**\ 
 \ *Optional second part of the EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 

Message 3
---------
\ **Description**\ 
 \ *Optional third part of the EMail Message*\ 
\ **Help**\ 
 \ *Message of the EMail*\ 
