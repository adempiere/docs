
.. _window-documenttype:

=============
Document Type
=============

Maintain Document Types

Help
====
The Document Type Window defines any document to be used in the system.  Each document type provides the basis for processing of each document and controls the printed name and document sequence used.  

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Document Type
-------------
\ **Description**\ 
 \ *Define a Document Type*\ 
\ **Help**\ 
 \ *The Document Definition Tab defines the processing parameters and controls for the document.  Note that shipments for automatic documents like POS/Warehouse Orders cannot have confirmations!*\ 

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

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

Document Note
-------------
\ **Description**\ 
 \ *Additional information for a Document*\ 
\ **Help**\ 
 \ *The Document Note is used for recording any additional information regarding this product.*\ 

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

GL Category
-----------
\ **Description**\ 
 \ *General Ledger Category*\ 
\ **Help**\ 
 \ *The General Ledger Category is an optional, user defined method of grouping journal lines.*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

Document BaseType
-----------------
\ **Description**\ 
 \ *Logical type of document*\ 
\ **Help**\ 
 \ *The Document Base Type identifies the base or starting point for a document.  Multiple document types may share a single document base type.*\ 

SO Sub Type
-----------
\ **Description**\ 
 \ *Sales Order Sub Type*\ 
\ **Help**\ 
 \ *The SO Sub Type indicates the type of sales order this document refers to.  This field only appears when the Document Base Type is Sales Order.  The selection made here will determine which documents will be generated when an order is processed and which documents must be generated manually or in batches.  
The following outlines this process.
SO Sub Type of \ **Standard Order**\  will generate just the \ **Order**\  document when the order is processed.  
The \ **Delivery Note**\ , \ **Invoice**\  and \ **Receipt**\  must be generated via other processes.  
SO Sub Type of \ **Warehouse Order**\  will generate the \ **Order**\  and \ **Delivery Note**\ . *  The \ **Invoice**\  and \ **Receipt**\  must be generated via other processes.
SO Sub Type of \ **Credit Order**\  will generate the \ **Order**\ , \ **Delivery Note**\  and \ **Invoice**\ . *  The \ **Receipt**\  must be generated via other processes.
SO Sub Type of \ **POS**\  (Point of Sale) will generate all document*\ 

Allocate Prepayments
--------------------

Document Type for ProForma
--------------------------
\ **Description**\ 
 \ *Document type used for pro forma invoices generated from this sales document*\ 
\ **Help**\ 
 \ *he Document Type for Invoice indicates the document type that will be used when an invoice is generated from this sales document.  This field will display only when the base document type is Sales Order and the Pro Forma Invoice checkbox is selected*\ 

Document Type for Invoice
-------------------------
\ **Description**\ 
 \ *Document type used for invoices generated from this sales document*\ 
\ **Help**\ 
 \ *The Document Type for Invoice indicates the document type that will be used when an invoice is generated from this sales document.  This field will display only when the base document type is Sales Order.*\ 

Document Type for Payment
-------------------------
\ **Description**\ 
 \ *Document type used for Payments generated from this Pay Selection document*\ 
\ **Help**\ 
 \ *The Document Type for payment indicates the document type that will be used when a payment is generated from this pay selection document.  This field will display only when the base document type is Pay Selection*\ 

Document Type for Shipment
--------------------------
\ **Description**\ 
 \ *Document type used for shipments generated from this sales document*\ 
\ **Help**\ 
 \ *he Document Type for Shipments indicates the document type that will be used when a shipment is generated from this sales document.  This field will display only when the base document type is Sales Order.*\ 

Document is Number Controlled
-----------------------------
\ **Description**\ 
 \ *The document has a document sequence*\ 
\ **Help**\ 
 \ *The Document Number Controlled checkbox indicates if this document type will have a sequence number.*\ 

Document Sequence
-----------------
\ **Description**\ 
 \ *Document sequence determines the numbering of documents*\ 
\ **Help**\ 
 \ *The Document Sequence indicates the sequencing rule to use for this document type.*\ 

Overwrite Sequence on Complete
------------------------------

Definite Sequence
-----------------

Copy Document No On Reversal
----------------------------
\ **Description**\ 
 \ *It Copy the Document No on Reversal Document instead of generate a new Sequence*\ 
\ **Help**\ 
 \ *Example of a Document #50000: when is reversed it generate a new sequence with next document no (#50001). If it flag is setted then the next sequence is not generate and the reversal document will be generated with #50000 wiht ^ as prefix: #50000^*\ 

Print Format
------------
\ **Description**\ 
 \ *Data Print Format*\ 
\ **Help**\ 
 \ *The print format determines how data is rendered for print.*\ 

Document Copies
---------------
\ **Description**\ 
 \ *Number of copies to be printed*\ 
\ **Help**\ 
 \ *The Document Copies indicates the number of copies of each document that will be generated.*\ 

Print Document
--------------
\ **Description**\ 
 \ *Document to print*\ 

Overwrite Date on Complete
--------------------------

Is Reversed with original Accounting
------------------------------------
\ **Description**\ 
 \ *Is Reversed with original Accounting*\ 
\ **Help**\ 
 \ *Allows a reversal document to generate the accounting based on the original Accounting.*\ 

Pick/QA Confirmation
--------------------
\ **Description**\ 
 \ *Require Pick or QA Confirmation before processing*\ 
\ **Help**\ 
 \ *The processing of the Shipment (Receipt) requires Pick (QA) Confirmation. Note that shipments for automatic documents like POS/Warehouse Orders cannot have confirmations!*\ 

Ship/Receipt Confirmation
-------------------------
\ **Description**\ 
 \ *Require Ship or Receipt Confirmation before processing*\ 
\ **Help**\ 
 \ *The processing of the Shipment (Receipt) requires Ship (Receipt) Confirmation. Note that shipments for automatic documents like POS/Warehouse Orders cannot have confirmations!*\ 

Split when Difference
---------------------
\ **Description**\ 
 \ *Split document when there is a difference*\ 
\ **Help**\ 
 \ *If the confirmation contains differences, the original document is split allowing the original document (shipment) to be processed and updating Inventory - and the newly created document for handling the dispute at a later time. Until the confirmation is processed, the inventory is not updated.*\ 

Difference Document
-------------------
\ **Description**\ 
 \ *Document type for generating in dispute Shipments*\ 
\ **Help**\ 
 \ *If the confirmation contains differences, the original document is split allowing the original document (shipment) to be processed and updating Inventory - and the newly created document for handling the dispute at a later time. Until the confirmation is processed, the inventory is not updated.*\ 

Prepare Split Document
----------------------
\ **Description**\ 
 \ *Prepare generated split shipment/receipt document*\ 

In Transit
----------
\ **Description**\ 
 \ *Movement is in transit*\ 
\ **Help**\ 
 \ *Material Movement is in transit - shipped, but not received.
The transaction is completed, if confirmed.*\ 

Create Counter Document
-----------------------
\ **Description**\ 
 \ *Create Counter Document*\ 
\ **Help**\ 
 \ *If selected, create specified counter document.  If not selected, no counter document is created for the document type.*\ 

Default Counter Document
------------------------
\ **Description**\ 
 \ *The document type is the default counter document type*\ 
\ **Help**\ 
 \ *When using explicit documents for inter-org transaction (after linking a Business Partner to an Organization), you can determine what document type the counter document is based on the document type of the original transaction.  Example: when generating a Sales Order, use this Sales Order document type.
This default can be overwritten by defining explicit counter document relationships.*\ 

Pro forma Invoice
-----------------
\ **Description**\ 
 \ *Indicates if Pro Forma Invoices can be generated from this document*\ 
\ **Help**\ 
 \ *The Pro Forma Invoice checkbox indicates if pro forma invoices can be generated from this sales document. A pro forma invoice indicates the amount that will be due should an order be shipped.*\ 

Translation
-----------
\ **Description**\ 
 \ *Translation*\ 
\ **Help**\ 
 \ *The Translation Tab defines a Document Type in an alternate language.*\ 

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

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

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

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Print Text
----------
\ **Description**\ 
 \ *The label text to be printed on a document or correspondence.*\ 
\ **Help**\ 
 \ *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*\ 

Document Note
-------------
\ **Description**\ 
 \ *Additional information for a Document*\ 
\ **Help**\ 
 \ *The Document Note is used for recording any additional information regarding this product.*\ 

Document Action Access
----------------------

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

Role
----
\ **Description**\ 
 \ *Responsibility Role*\ 
\ **Help**\ 
 \ *The Role determines security and access a user who has this Role will have in the System.*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Reference List
--------------
\ **Description**\ 
 \ *Reference List based on Table*\ 
\ **Help**\ 
 \ *The Reference List field indicates a list of reference values from a database tables.  Reference lists populate drop down list boxes in data entry screens*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Charge Type by Doc Type
-----------------------

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

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Charge Type
-----------

Allow Positive
--------------

Allow Negative
--------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
