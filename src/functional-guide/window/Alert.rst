
.. _window-alert:

=====
Alert
=====

Adempiere Alert

Help
====
Adempiere Alerts allow you define system conditions you want to be alerted of

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Alert
-----
\ **Description**\ 
 \ *Adempiere Alert*\ 
\ **Help**\ 
 \ *Adempiere Alerts allow you define system conditions you want to be alerted of.*\ 

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

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

Alert Processor
---------------
\ **Description**\ 
 \ *Alert Processor/Server Parameter*\ 
\ **Help**\ 
 \ *Alert Processor/Server Parameter*\ 

Enforce Client Security
-----------------------
\ **Description**\ 
 \ *Send alerts to recipient only if the client security rules of the role allows*\ 

Enforce Role Security
---------------------
\ **Description**\ 
 \ *Send alerts to recipient only if the data security rules of the role allows*\ 

Alert Subject
-------------
\ **Description**\ 
 \ *Subject of the Alert*\ 
\ **Help**\ 
 \ *The subject of the email message sent for the alert*\ 

Alert Message
-------------
\ **Description**\ 
 \ *Message of the Alert*\ 
\ **Help**\ 
 \ *The message of the email sent for the alert*\ 

Alert Rule
----------
\ **Description**\ 
 \ *Definition of the alert element*\ 
\ **Help**\ 
 \ *The definition of the altert or action*\ 

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

Alert
-----
\ **Description**\ 
 \ *Adempiere Alert*\ 
\ **Help**\ 
 \ *Adempiere Alerts allow you define system conditions you want to be alerted of*\ 

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

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

Error Msg
---------

Pre Processing
--------------
\ **Description**\ 
 \ *Process SQL before executing the query*\ 
\ **Help**\ 
 \ *Could be Update/Delete/etc. statement*\ 

Sql SELECT
----------
\ **Description**\ 
 \ *SQL SELECT clause*\ 
\ **Help**\ 
 \ *The Select Clause indicates the SQL SELECT clause to use for selecting the record for a measure calculation. Do not include the SELECT itself.*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Sql FROM
--------
\ **Description**\ 
 \ *SQL FROM clause*\ 
\ **Help**\ 
 \ *The Select Clause indicates the SQL FROM clause to use for selecting the record for a measure calculation. It can have JOIN clauses. Do not include the FROM itself.*\ 

Sql WHERE
---------
\ **Description**\ 
 \ *Fully qualified SQL WHERE clause*\ 
\ **Help**\ 
 \ *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*\ 

Other SQL Clause
----------------
\ **Description**\ 
 \ *Other SQL Clause*\ 
\ **Help**\ 
 \ *Any other complete clause like GROUP BY, HAVING, ORDER BY, etc. after WHERE clause.*\ 

Post Processing
---------------
\ **Description**\ 
 \ *Process SQL after executing the query*\ 
\ **Help**\ 
 \ *Could be Update/Delete/etc. statement*\ 

Alert Recipient
---------------
\ **Description**\ 
 \ *Recipient of the Alert Notification*\ 
\ **Help**\ 
 \ *You can send the notifications to users or roles*\ 

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

Alert
-----
\ **Description**\ 
 \ *Adempiere Alert*\ 
\ **Help**\ 
 \ *Adempiere Alerts allow you define system conditions you want to be alerted of*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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
