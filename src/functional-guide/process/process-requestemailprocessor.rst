
.. _functional-guide/process/process-requestemailprocessor:

=======================
Request EMail Processor
=======================


Parameters
==========

EMail Configuration
-------------------

.. note::
    The field must have a value for the record to be saved to the database.

Request User
------------
\ **Description**\ 
 \ *User Name (ID) of the email owner*\ 
\ **Help**\ 
 \ *EMail user name for requests, alerts and escalation are sent from this email address as well as delivery information if the sales rep does not have an email account. Required, if your mail server requires authentification as well as for processing incoming mails.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Request User Password
---------------------
\ **Description**\ 
 \ *Password of the user name (ID) for mail processing*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Request Folder
--------------
\ **Description**\ 
 \ *EMail folder to process incoming emails; if empty INBOX is used*\ 
\ **Help**\ 
 \ *Email folder used to read emails to process as requests, If left empty the default mailbox (INBOX) will be used. Requires IMAP services.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Inbox Folder
------------

.. note::
    The field must have a value for the record to be saved to the database.

Error Folder
------------

.. note::
    The field must have a value for the record to be saved to the database.

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Request Type
------------
\ **Description**\ 
 \ *Type of request (e.g. Inquiry, Complaint, ..)*\ 
\ **Help**\ 
 \ *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*\ 

Priority
--------
\ **Description**\ 
 \ *Priority of a document*\ 
\ **Help**\ 
 \ *The Priority indicates the importance (high, medium, low) of this document*\ 

Confidentiality
---------------
\ **Description**\ 
 \ *Type of Confidentiality*\ 
