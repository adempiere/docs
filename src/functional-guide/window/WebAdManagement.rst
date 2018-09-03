
.. _window-webadmanagement:

=================
Web Ad Management
=================

Content Management Ad Management defines the needed categories and items

Help
====
Ad Management is used to create and manage advertisements in your conten management

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Advertisement Category
----------------------
\ **Description**\ 
 \ *Defines the categories to group Ads*\ 

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

Web Project
-----------
\ **Description**\ 
 \ *A web project is the main data container for Containers, URLs, Ads, Media etc.*\ 
\ **Help**\ 
 \ *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*\ 

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

Advertisement
-------------
\ **Description**\ 
 \ *The Advertisement*\ 

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

Advertisement Category
----------------------
\ **Description**\ 
 \ *Advertisement Category like Banner Homepage*\ 
\ **Help**\ 
 \ *The advertisement category defines a container for ad's like for example all banners used on the homepage in rotation are stored in a category "Banner Homepage" etc.*\ 

Media Item
----------
\ **Description**\ 
 \ *Contains media content like images, flash movies etc.*\ 
\ **Help**\ 
 \ *This table contains all the media content like images, flash movies etc.*\ 

Actual Click Count
------------------
\ **Description**\ 
 \ *How many clicks have been counted*\ 
\ **Help**\ 
 \ *Contains info on the actual click count until now*\ 

Max Click Count
---------------
\ **Description**\ 
 \ *Maximum Click Count until banner is deactivated*\ 
\ **Help**\ 
 \ *A banner has a maximum number of clicks after which it will get deactivated*\ 

Actual Impression Count
-----------------------
\ **Description**\ 
 \ *How many impressions have been counted*\ 
\ **Help**\ 
 \ *Contains info on the actual impression count until now*\ 

Max Impression Count
--------------------
\ **Description**\ 
 \ *Maximum Impression Count until banner is deactivated*\ 
\ **Help**\ 
 \ *A banner has a maximum number of impressions after which it will get deactivated*\ 

Start Count Impression
----------------------
\ **Description**\ 
 \ *For rotation we need a start count*\ 
\ **Help**\ 
 \ *If we run banners in rotation we always show the one with the min of impressions, so if a new banner is added to impressions we don't want it to show up so often we set a startimpressions value. StartImpression+ActualImpression=CurrentImpression*\ 

Start Date
----------
\ **Description**\ 
 \ *First effective day (inclusive)*\ 
\ **Help**\ 
 \ *The Start Date indicates the first or starting date*\ 

End Date
--------
\ **Description**\ 
 \ *Last effective date (inclusive)*\ 
\ **Help**\ 
 \ *The End Date indicates the last date in this range.*\ 

Content HTML
------------
\ **Description**\ 
 \ *Contains the content itself*\ 
\ **Help**\ 
 \ *Contains the content itself as HTML code. Should normally only use basic tags, no real layouting*\ 

Logging
-------
\ **Description**\ 
 \ *Do we need to log the banner impressions and clicks? (needs much performance)*\ 
\ **Help**\ 
 \ *As of performance we should only log banners if really necessary, as this takes a lot of performance*\ 

Special AD Flag
---------------
\ **Description**\ 
 \ *Do we need to specially mention this ad?*\ 
\ **Help**\ 
 \ *If we have a block in content where announce content and also sponsored links we should mention the sponsored ones*\ 

Target URL
----------
\ **Description**\ 
 \ *URL for the Target*\ 
\ **Help**\ 
 \ *URL of the Target Site*\ 

Target Frame
------------
\ **Description**\ 
 \ *Which target should be used if user clicks?*\ 
\ **Help**\ 
 \ *Do we want the content to stay in same window, to open up a new one or to place it in a special frame?*\ 

Ad Cat Template
---------------
\ **Description**\ 
 \ *Advertisement Category link to Template*\ 

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

Advertisement Category
----------------------
\ **Description**\ 
 \ *Advertisement Category like Banner Homepage*\ 
\ **Help**\ 
 \ *The advertisement category defines a container for ad's like for example all banners used on the homepage in rotation are stored in a category "Banner Homepage" etc.*\ 

Template
--------
\ **Description**\ 
 \ *Template defines how content is displayed*\ 
\ **Help**\ 
 \ *A template describes how content should get displayed, it contains layout and maybe also scripts on how to handle the content*\ 

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
