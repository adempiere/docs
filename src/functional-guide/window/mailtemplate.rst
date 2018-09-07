
.. _functional-guide/window/mailtemplate:

=============
Mail Template
=============

Maintain Mail Template

Help
====
Mail templates can contain variables of the user, business partner or a general object.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Mail Template
-------------
\ **Description**\ 
 \ *Maintain Mail Template*\ 
\ **Help**\ 
 \ *A mail template can contain variables, e.g. @Name@.  
The variables are replaced based on the context. First, the the User is searched to find the variables.
Additional objects are used for dunning (business partner, dunning entry), asset delivery (asset) and invoice print (business partner, invoice)*\ 

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
 \ *Mail Header (Subject)*\ 
\ **Help**\ 
 \ *The subject of the mail message*\ 

Mail Text
---------
\ **Description**\ 
 \ *Text used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

Mail Text 2
-----------
\ **Description**\ 
 \ *Optional second text part used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

Mail Text 3
-----------
\ **Description**\ 
 \ *Optional third text part used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

HTML
----
\ **Description**\ 
 \ *Text has HTML tags*\ 

Translation
-----------
\ **Description**\ 
 \ *Translation*\ 

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

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

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

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Subject
-------
\ **Description**\ 
 \ *Mail Header (Subject)*\ 
\ **Help**\ 
 \ *The subject of the mail message*\ 

Mail Text
---------
\ **Description**\ 
 \ *Text used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

Mail Text 2
-----------
\ **Description**\ 
 \ *Optional second text part used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

Mail Text 3
-----------
\ **Description**\ 
 \ *Optional third text part used for Mail message*\ 
\ **Help**\ 
 \ *The Mail Text indicates the text used for mail messages.*\ 

User Mail
---------
\ **Description**\ 
 \ *Mail sent to the user*\ 

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

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Message ID
----------
\ **Description**\ 
 \ *EMail Message ID*\ 
\ **Help**\ 
 \ *SMTP Message ID for tracking purposes*\ 

Delivery Confirmation
---------------------
\ **Description**\ 
 \ *EMail Delivery confirmation*\ 

Delivered
---------
