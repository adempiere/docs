
.. _window-replication:

===========
Replication
===========

Maintain Data Replication Targets

Help
====
Data Replication Target Details. Set up your system completely on the central system, before setting up the replication. Define the Replication target here and export the database and import it on the remote system.
Before(!) entering transactions, Start the Replication Run to set up the remote system.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Replication Target
------------------
\ **Description**\ 
 \ *Data Replication Target*\ 
\ **Help**\ 
 \ *Data Replication Target Details. Maintained on the central server. Make sure that the IP range is unique for every remote system - Otherwise you will loose data!!*\ 

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

Replication Strategy
--------------------
\ **Description**\ 
 \ *Data Replication Strategy*\ 
\ **Help**\ 
 \ *The Data Replication Strategy determines what and how tables are replicated*\ 

Host Address
------------
\ **Description**\ 
 \ *Host Address URL or DNS*\ 
\ **Help**\ 
 \ *The Host Address identifies the URL or DNS of the target host*\ 

Tunnel via HTTP
---------------
\ **Description**\ 
 \ *Connect to Server via HTTP Tunnel*\ 
\ **Help**\ 
 \ *If selected, the connection to the server is via a HTTP tunnel, otherwise it uses an RMI/JNP connection*\ 

Host port
---------
\ **Description**\ 
 \ *Host Communication Port*\ 
\ **Help**\ 
 \ *The Host Port identifies the port to communicate with the host.*\ 

Remote Client
-------------
\ **Description**\ 
 \ *Remote Client to be used to replicate / synchronize data with.*\ 
\ **Help**\ 
 \ *The remote client used for data replication.*\ 

Remote Organization
-------------------
\ **Description**\ 
 \ *Remote Organization to be used to replicate / synchronize data with.*\ 
\ **Help**\ 
 \ *The remote organization used for data replication. If not selected, all organizations are replicated/synchronized.*\ 

ID Range Start
--------------
\ **Description**\ 
 \ *Start of the ID Range used*\ 
\ **Help**\ 
 \ *The ID Range allows to restrict the range of the internally used IDs. The standard rages are 0-899,999 for the Application Dictionary 900,000-999,999 for Application Dictionary customizations/extensions and > 1,000,000 for client data. The standard system limit is 9,999,999,999 but can easily be extended.  The ID range is on a per table basis.
Please note that the ID range is NOT enforced.*\ 

ID Range End
------------
\ **Description**\ 
 \ *End if the ID Range used*\ 
\ **Help**\ 
 \ *The ID Range allows to restrict the range of the internally used IDs. Please note that the ID range is NOT enforced.*\ 

Prefix
------
\ **Description**\ 
 \ *Prefix before the sequence number*\ 
\ **Help**\ 
 \ *The Prefix indicates the characters to print in front of the document number.*\ 

Suffix
------
\ **Description**\ 
 \ *Suffix after the number*\ 
\ **Help**\ 
 \ *The Suffix indicates the characters to append to the document number.*\ 

Start Replication Run
---------------------
\ **Description**\ 
 \ *Start Replication with Remote Host*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Replication Run
---------------
\ **Description**\ 
 \ *Data Replication Run*\ 
\ **Help**\ 
 \ *Historic Info*\ 

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

Replication
-----------
\ **Description**\ 
 \ *Data Replication Target*\ 
\ **Help**\ 
 \ *Data Replication Target Details. Maintained on the central server.*\ 

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

Replicated
----------
\ **Description**\ 
 \ *The data is successfully replicated*\ 
\ **Help**\ 
 \ *The data replication was successful.*\ 

Run Log
-------
\ **Description**\ 
 \ *Data Replication Run Log*\ 
\ **Help**\ 
 \ *Detail Info*\ 

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

Replication Run
---------------
\ **Description**\ 
 \ *Data Replication Run*\ 
\ **Help**\ 
 \ *Data Replication Run information*\ 

Replication Table
-----------------
\ **Description**\ 
 \ *Data Replication Strategy Table Info*\ 
\ **Help**\ 
 \ *Determines how the table is replicated*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Replicated
----------
\ **Description**\ 
 \ *The data is successfully replicated*\ 
\ **Help**\ 
 \ *The data replication was successful.*\ 

Process Message
---------------
