
.. _functional-guide/window/webaccess:

==========
Web Access
==========

Maintain Web Access

Help
====
Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Web Access Profile
------------------
\ **Description**\ 
 \ *Maintain Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.
If the profile is exclude (default), the assignees can view all but the defined content. If the profile is not exclude (include), the assigned roles and business partner groups can only view the listed content.*\ 

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

Exclude
-------
\ **Description**\ 
 \ *Exclude access to the data - if not selected Include access to the data*\ 
\ **Help**\ 
 \ *If selected (excluded), the role cannot access the data specified.  If not selected (included), the role can ONLY access the data specified. Exclude items represent a negative list (i.e. you don't have access to the listed items). Include items represent a positive list (i.e. you only have access to the listed items).
* You would usually  not mix Exclude and Include. If you have one include rule in your list, you would only have access to that item anyway.*\ 

List Role
---------
\ **Description**\ 
 \ *Web Access for Role*\ 
\ **Help**\ 
 \ *Maintain the list of Roles with Access to this profile.*\ 

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

Web Access Profile
------------------
\ **Description**\ 
 \ *Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.*\ 

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

List BPartner Group
-------------------
\ **Description**\ 
 \ *Web Access for Business Partner Group*\ 
\ **Help**\ 
 \ *Maintain the list of Roles with Access to this profile.*\ 

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

Web Access Profile
------------------
\ **Description**\ 
 \ *Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Access Stage
------------
\ **Description**\ 
 \ *Web Access to Container Stage*\ 
\ **Help**\ 
 \ *Maintain the access to container stage*\ 

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Access Container
----------------
\ **Description**\ 
 \ *Web Access to Container*\ 
\ **Help**\ 
 \ *Maintain the access to container*\ 

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

Web Access Profile
------------------
\ **Description**\ 
 \ *Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.*\ 

Web Container
-------------
\ **Description**\ 
 \ *Web Container contains content like images, text etc.*\ 
\ **Help**\ 
 \ *A Container defines the abstract level around the content, it defines how the content gets displayed, indexed and stored.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Access News Channel
-------------------
\ **Description**\ 
 \ *Web Access to News Channel*\ 
\ **Help**\ 
 \ *Maintain the access to news channel*\ 

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

Web Access Profile
------------------
\ **Description**\ 
 \ *Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.*\ 

News Channel
------------
\ **Description**\ 
 \ *News channel for rss feed*\ 
\ **Help**\ 
 \ *A news channel defines the content base for the RSS feed*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Access Media
------------
\ **Description**\ 
 \ *Web Access to Media*\ 
\ **Help**\ 
 \ *Maintain the access to media*\ 

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

Web Access Profile
------------------
\ **Description**\ 
 \ *Web Access Profile*\ 
\ **Help**\ 
 \ *Define access to collaboration management content.  You can assign the profile to a internal role or for external access to business partner group.*\ 

Media Item
----------
\ **Description**\ 
 \ *Contains media content like images, flash movies etc.*\ 
\ **Help**\ 
 \ *This table contains all the media content like images, flash movies etc.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
