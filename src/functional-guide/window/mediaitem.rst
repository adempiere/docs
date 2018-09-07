
.. _functional-guide/window/mediaitem:

==========
Media Item
==========

Maintain Web Media

Help
====
Maintain Content Management Media

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Web Project
-----------
\ **Description**\ 
 \ *Select Media Project*\ 

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

Meta Author
-----------
\ **Description**\ 
 \ *Author of the content*\ 
\ **Help**\ 
 \ *Author of the content for the Containers Meta Data*\ 

Meta Content Type
-----------------
\ **Description**\ 
 \ *Defines the type of content i.e. "text/html; charset=UTF-8"*\ 
\ **Help**\ 
 \ *With this tag you can overwrite the type of content and how search engines will interpret it. You should keep in mind that this will not influence how the Server and Client interpret the content.*\ 

Meta Copyright
--------------
\ **Description**\ 
 \ *Contains Copyright information for the content*\ 
\ **Help**\ 
 \ *This Tag contains detailed information about the content's copyright situation, how holds it for which timeframe etc.*\ 

Meta Publisher
--------------
\ **Description**\ 
 \ *Meta Publisher defines the publisher of the content*\ 
\ **Help**\ 
 \ *As author and publisher must not be the same person this tag saves the responsible publisher for the content*\ 

Meta RobotsTag
--------------
\ **Description**\ 
 \ *RobotsTag defines how search robots should handle this content*\ 
\ **Help**\ 
 \ *The Meta Robots Tag define on how a search engines robot should handle this page and the following ones. It defines two keywords: (NO)INDEX which defines whether or not to index this content and (NO)FOLLOW which defines whether or not to follow links. The most common combination is INDEX,FOLLOW which will force a search robot to index the content and follow links and images.*\ 

Container Tree
--------------
\ **Description**\ 
 \ *Container Tree*\ 
\ **Help**\ 
 \ *Container Tree*\ 

Stage Tree
----------
\ **Description**\ 
 \ *Stage Tree*\ 
\ **Help**\ 
 \ *Stage Tree*\ 

Template Tree
-------------
\ **Description**\ 
 \ *Template Tree*\ 
\ **Help**\ 
 \ *Template Tree*\ 

Media Tree
----------
\ **Description**\ 
 \ *Media Tree*\ 
\ **Help**\ 
 \ *Media Tree*\ 

Media Item
----------
\ **Description**\ 
 \ *Maintain Media Item*\ 
\ **Help**\ 
 \ *Media items are deployed on the media servers. The media item can be an Image or an attachment. Attachments are ignored, if there is an image.  If there are more then one attachment, the first is used.*\ 

.. note::
    null
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

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Web Project
-----------
\ **Description**\ 
 \ *A web project is the main data container for Containers, URLs, Ads, Media etc.*\ 
\ **Help**\ 
 \ *A web project is the meta definition which will contain later on all data within the Web Content Management Project.*\ 

Media Type
----------
\ **Description**\ 
 \ *Defines the media type for the browser*\ 
\ **Help**\ 
 \ *The browser and the media server need info on the type of content*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

Deplayment
----------
\ **Description**\ 
 \ *Media Deployment*\ 
\ **Help**\ 
 \ *Deployment to Media Server*\ 

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

Media Item
----------
\ **Description**\ 
 \ *Contains media content like images, flash movies etc.*\ 
\ **Help**\ 
 \ *This table contains all the media content like images, flash movies etc.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Media Server
------------
\ **Description**\ 
 \ *Media Server list to which content should get transfered*\ 
\ **Help**\ 
 \ *Media Server list to which content should get transferred*\ 

Last Synchronized
-----------------
\ **Description**\ 
 \ *Date when last synchronized*\ 

Deployed
--------
\ **Description**\ 
 \ *Entity is deployed*\ 
