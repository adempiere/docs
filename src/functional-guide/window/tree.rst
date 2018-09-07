
.. _functional-guide/window/tree:

====
Tree
====

Maintain Tree definition

Help
====
The Tree Window defines the descriptors and images that will be used when a Tree is displayed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Tree
----
\ **Description**\ 
 \ *Tree*\ 
\ **Help**\ 
 \ *The Tree Tab defines a Tree which will be displayed.*\ 

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

Type | Area
-----------
\ **Description**\ 
 \ *Element this tree is built on (i.e Product, Business Partner)*\ 
\ **Help**\ 
 \ *The Tree Type / Area field determines the type of tree this is.  For example, you may define one tree for your Products and another tree for your Business Partners.*\ 

All Nodes
---------
\ **Description**\ 
 \ *All Nodes are included (Complete Tree)*\ 
\ **Help**\ 
 \ *If selected, all Nodes must be in the tree.*\ 

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Verify Tree
-----------
\ **Description**\ 
 \ *Verify completeness and correctness of Tree*\ 
