
.. _functional-guide/window/window-workflowprocessor:

==================
Workflow Processor
==================

Maintain Workflow Processor and Logs

Help
====
Workflow Processor Server Parameters

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Workflow Processor
------------------
\ **Description**\ 
 \ *Workflow Processor Server*\ 
\ **Help**\ 
 \ *Workflow Processor Server*\ 

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

Frequency Type
--------------
\ **Description**\ 
 \ *Frequency of event*\ 
\ **Help**\ 
 \ *The frequency type is used for calculating the date of the next event.*\ 

Frequency
---------
\ **Description**\ 
 \ *Frequency of events*\ 
\ **Help**\ 
 \ *The frequency is used in conjunction with the frequency type in determining an event. Example: If the Frequency Type is Week and the Frequency is 2 - it is every two weeks.*\ 

Inactivity Alert Days
---------------------
\ **Description**\ 
 \ *Send Alert when there is no activity after days (0= no alert)*\ 
\ **Help**\ 
 \ *An email alert is sent when the request shows no activity for the number of days defined.*\ 

Reminder Days
-------------
\ **Description**\ 
 \ *Days between sending Reminder Emails for a due or inactive Document*\ 
\ **Help**\ 
 \ *When a document is due for too long without activity, a reminder is sent. 0 means no reminders.
The Remind Days are the days when the next email reminder is sent.*\ 

Supervisor
----------
\ **Description**\ 
 \ *Supervisor for this user/organization - used for escalation and approval*\ 
\ **Help**\ 
 \ *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*\ 

Days to keep Log
----------------
\ **Description**\ 
 \ *Number of days to keep the log entries*\ 
\ **Help**\ 
 \ *Older Log entries may be deleted*\ 

Alert over Priority
-------------------
\ **Description**\ 
 \ *Send alert email when over priority*\ 
\ **Help**\ 
 \ *Send alert email when a suspended activity is over the  priority defined*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Date next run
-------------
\ **Description**\ 
 \ *Date the process will run next*\ 
\ **Help**\ 
 \ *The Date Next Run indicates the next time this process will run.*\ 

Log
---
\ **Description**\ 
 \ *Workflow Processor Log*\ 
\ **Help**\ 
 \ *Result of the execution of the Workflow Processor*\ 

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

Workflow Processor
------------------
\ **Description**\ 
 \ *Workflow Processor Server*\ 
\ **Help**\ 
 \ *Workflow Processor Server*\ 

Created
-------
\ **Description**\ 
 \ *Date this record was created*\ 
\ **Help**\ 
 \ *The Created field indicates the date that this record was created.*\ 

Summary
-------
\ **Description**\ 
 \ *Textual summary of this request*\ 
\ **Help**\ 
 \ *The Summary allows free form text entry of a recap of this request.*\ 

Error
-----
\ **Description**\ 
 \ *An Error occurred in the execution*\ 

Reference
---------
\ **Description**\ 
 \ *Reference for this record*\ 
\ **Help**\ 
 \ *The Reference displays the source document number.*\ 

Text Message
------------
\ **Description**\ 
 \ *Text Message*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 
