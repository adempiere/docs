
.. _functional-guide/process/process-c_dunningprint:

=====================
Print Dunning Letters
=====================

Print Dunning letters to paper or send PDF

Help
====
(Re)Print Dunning Letters or send them as PDF attachments to the Business Partner Contact with a valid EMail addres.


Parameters
==========

EMail PDF
---------
\ **Description**\ 
 \ *Email Document PDF files to Business Partner*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Mail Template
-------------
\ **Description**\ 
 \ *Text templates for mailings*\ 
\ **Help**\ 
 \ *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*\ 

Dunning Run
-----------
\ **Description**\ 
 \ *Dunning Run*\ 

Only If BP has Balance
----------------------
\ **Description**\ 
 \ *Include only if Business Partner has outstanding Balance*\ 

Print Unprocessed Entries Only
------------------------------
\ **Description**\ 
 \ *Print the unprocessed (unprinted) entries of the dunning run only.*\ 
\ **Help**\ 
 \ *Print the unprocessed (unprinted) entries of the dunning run only. This allows you to reprint only certain dunning entries.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
