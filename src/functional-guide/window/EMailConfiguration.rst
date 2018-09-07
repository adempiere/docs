
.. _window-emailconfiguration:

===================
EMail Configuration
===================

EMail Configuration Server

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Server Configuration
--------------------
\ **Description**\ 
 \ *Server Configuration*\ 

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

Protocol
--------
\ **Description**\ 
 \ *Protocol*\ 

Mail Host
---------
\ **Description**\ 
 \ *Hostname of Mail Server for SMTP and IMAP*\ 
\ **Help**\ 
 \ *The host name of the Mail Server for this client with SMTP services to send mail, and IMAP to process incoming mail.*\ 

Port
----

SMTP Authentication
-------------------
\ **Description**\ 
 \ *Your mail server requires Authentication*\ 
\ **Help**\ 
 \ *Some email servers require authentication before sending emails.  If yes, users are required to define their email user name and password.  If authentication is required and no user name and password is required, delivery will fail.*\ 

Encryption Type
---------------
\ **Description**\ 
 \ *Encryption Type used for securing data content*\ 

Authentication Mechanism
------------------------

LDAP Domain
-----------
\ **Description**\ 
 \ *Directory service domain name - e.g. adempiere.org*\ 
\ **Help**\ 
 \ *If LDAP Host and Domain is specified, the user is authenticated via LDAP. The password in the User table is not used for connecting to Adempiere.*\ 

Connection Timeout
------------------
\ **Description**\ 
 \ *Is Timeout (In milliseconds) for establishing connection*\ 

Timeout
-------
\ **Description**\ 
 \ *Is Timeout (In milliseconds) for sending or receive data*\ 
