
.. _functional-guide/process/process-r_mailtextsend:

==============
Send Mail Text
==============

Send EMails to active subscribers of an Interest Area OR a Business Partner Group from a selected User

Help
====
Select the Interest Area to which subscribers you send the Mail Text from the User selected.  Additionally, you can send mails to the Contacts of a Business Partner Group.
The User to send emails from needs to have valid EMail information. If you don't select a user, the Mail is sent from the Client's Request Mail User.

Parameters
==========

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Interest Area
-------------
\ **Description**\ 
 \ *Interest Area or Topic*\ 
\ **Help**\ 
 \ *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

From User
---------
\ **Description**\ 
 \ *Send EMail from user*\ 
\ **Help**\ 
 \ *The email is sent from the user selected - otherwise it is sent from the request email address of the client*\ 
