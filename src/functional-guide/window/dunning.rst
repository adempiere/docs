
.. _functional-guide/window/dunning:

=======
Dunning
=======

Maintain Dunning Levels

Help
====
The Dunning Window defines the parameters that will be used when generating Dunning Letters.  Each customer can be associated with a Dunning Code.  

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Dunning
-------
\ **Description**\ 
 \ *Maintain Dunning Rules*\ 
\ **Help**\ 
 \ *The Dunning Tab defines the parameters for a dunning level.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Create levels sequentially
--------------------------
\ **Description**\ 
 \ *Create Dunning Letter by level sequentially*\ 
\ **Help**\ 
 \ *If selected, the dunning letters are created in the sequence of the dunning levels.  Otherwise, the dunning level is based on the days (over)due.*\ 

Level
-----
\ **Description**\ 
 \ *Maintain Dunning Level*\ 
\ **Help**\ 
 \ *The Dunning Level Tab defines the timing and frequency of the dunning notices.*\ 

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

Dunning
-------
\ **Description**\ 
 \ *Dunning Rules for overdue invoices*\ 
\ **Help**\ 
 \ *The Dunning indicates the rules and method of dunning for past due payments.*\ 

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

Show All Due
------------
\ **Description**\ 
 \ *Show/print all due invoices*\ 
\ **Help**\ 
 \ *The dunning letter with this level includes all due invoices.*\ 

Show Not Due
------------
\ **Description**\ 
 \ *Show/print all invoices which are not due (yet).*\ 
\ **Help**\ 
 \ *The dunning letter with this level includes all not due invoices.*\ 

Range
-----
\ **Description**\ 
 \ *The parameter is a range of values*\ 
\ **Help**\ 
 \ *The Range checkbox indicates that this parameter is a range of values.*\ 

Days after due date
-------------------
\ **Description**\ 
 \ *Days after due date to dun (if negative days until due)*\ 
\ **Help**\ 
 \ *The Days After Due Date indicates the number of days after the payment due date to initiate dunning. If the number is negative, it includes not the not due invoices.*\ 

Days between dunning
--------------------
\ **Description**\ 
 \ *Days between sending dunning notices*\ 
\ **Help**\ 
 \ *The Days Between Dunning indicates the number of days between sending dunning notices.*\ 

Days From
---------

Days To
-------

Include Payments
----------------
\ **Description**\ 
 \ *Include payments in the aging report*\ 

Charge fee
----------
\ **Description**\ 
 \ *Indicates if fees will be charged for overdue invoices*\ 
\ **Help**\ 
 \ *The Charge Fee checkbox indicates if the dunning letter will include fees for overdue invoices*\ 

Fee Amount
----------
\ **Description**\ 
 \ *Fee amount in invoice currency*\ 
\ **Help**\ 
 \ *The Fee Amount indicates the charge amount on a dunning letter for overdue invoices.  This field will only display if the charge fee checkbox has been selected.*\ 

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Dunning Print Format
--------------------
\ **Description**\ 
 \ *Print Format for printing Dunning Letters*\ 
\ **Help**\ 
 \ *You need to define a Print Format to print the document.*\ 

Credit Stop
-----------
\ **Description**\ 
 \ *Set the business partner to credit stop*\ 
\ **Help**\ 
 \ *If a dunning letter of this level is created, the business partner is set to Credit Stop (needs to be manually changed).*\ 

Set Payment Term
----------------
\ **Description**\ 
 \ *Set the payment term of the Business Partner*\ 
\ **Help**\ 
 \ *If a dunning letter of this level is created, the payment term of this business partner is overwritten.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Collection Status
-----------------
\ **Description**\ 
 \ *Invoice Collection Status*\ 
\ **Help**\ 
 \ *Status of the invoice collection process*\ 

Is Statement
------------
\ **Description**\ 
 \ *Dunning Level is a definition of a statement*\ 

Translation
-----------
\ **Description**\ 
 \ *Dunning Level Translation*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Dunning Level
-------------

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 
