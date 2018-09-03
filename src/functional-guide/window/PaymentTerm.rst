
.. _window-paymentterm:

============
Payment Term
============

Maintain Payment Terms

Help
====
The Payment Terms Window defines the different payment terms that you offer your customers and that are offered to you by your vendors.  Each invoice must contain a Payment Term.  On the standard invoice, the Name and the Document Note of the Payment Term is printed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Payment Term
------------
\ **Description**\ 
 \ *Define Payment Terms*\ 
\ **Help**\ 
 \ *The Payment Term Tab defines the different payments terms that you offer to your Business Partners when paying invoices and also those terms which your Vendors offer you for payment of your invoices. On the standard invoice, the Name and the Document Note of the Payment Term is printed.*\ 

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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

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

Fixed due date
--------------
\ **Description**\ 
 \ *Payment is due on a fixed date*\ 
\ **Help**\ 
 \ *The Fixed Due Date checkbox indicates if invoices using this payment tern will be due on a fixed day of the month.*\ 

After Delivery
--------------
\ **Description**\ 
 \ *Due after delivery rather than after invoicing*\ 
\ **Help**\ 
 \ *The After Delivery checkbox indicates that payment is due after delivery as opposed to after invoicing.*\ 

Next Business Day
-----------------
\ **Description**\ 
 \ *Payment due on the next business day*\ 
\ **Help**\ 
 \ *The Next Business Day checkbox indicates that payment is due on the next business day after invoice or delivery.*\ 

Fix month day
-------------
\ **Description**\ 
 \ *Day of the month of the due date*\ 
\ **Help**\ 
 \ *The Fix Month Day indicates the day of the month that invoices are due.  This field only displays if the fixed due date checkbox is selected.*\ 

Fix month cutoff
----------------
\ **Description**\ 
 \ *Last day to include for next due date*\ 
\ **Help**\ 
 \ *The Fix Month Cutoff indicates the last day invoices can have to be included in the current due date.  This field only displays when the fixed due date checkbox has been selected.*\ 

Fix month offset
----------------
\ **Description**\ 
 \ *Number of months (0=same, 1=following)*\ 
\ **Help**\ 
 \ *The Fixed Month Offset indicates the number of months from the current month to indicate an invoice is due.  A 0 indicates the same month, a 1 the following month.  This field will only display if the fixed due date checkbox is selected.*\ 

Net Days
--------
\ **Description**\ 
 \ *Net Days in which payment is due*\ 
\ **Help**\ 
 \ *Indicates the number of days after invoice date that payment is due.*\ 

Net Day
-------
\ **Description**\ 
 \ *Day when payment is due net*\ 
\ **Help**\ 
 \ *When defined, overwrites the number of net days with the relative number of days to the the day defined.*\ 

Discount Days
-------------
\ **Description**\ 
 \ *Number of days from invoice date to be eligible for discount*\ 
\ **Help**\ 
 \ *The Discount Days indicates the number of days that payment must be received in to be eligible for the stated discount.*\ 

Discount %
----------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 

Discount Days 2
---------------
\ **Description**\ 
 \ *Number of days from invoice date to be eligible for discount*\ 
\ **Help**\ 
 \ *The Discount Days indicates the number of days that payment must be received in to be eligible for the stated discount.*\ 

Discount 2 %
------------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 

Grace Days
----------
\ **Description**\ 
 \ *Days after due date to send first dunning letter*\ 
\ **Help**\ 
 \ *The Grace Days indicates the number of days after the due date to send the first dunning letter.  This field displays only if the send dunning letters checkbox has been selected.*\ 

Document Note
-------------
\ **Description**\ 
 \ *Additional information for a Document*\ 
\ **Help**\ 
 \ *The Document Note is used for recording any additional information regarding this product.*\ 

Validate
--------
\ **Description**\ 
 \ *Validate Payment Terms and Schedule*\ 

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 

Translation
-----------

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

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

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

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

Schedule
--------
\ **Description**\ 
 \ *Payment Schedule*\ 

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

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

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

Percentage
----------
\ **Description**\ 
 \ *Percent of the entire amount*\ 
\ **Help**\ 
 \ *Percentage of an amount (up to 100)*\ 

Net Days
--------
\ **Description**\ 
 \ *Net Days in which payment is due*\ 
\ **Help**\ 
 \ *Indicates the number of days after invoice date that payment is due.*\ 

Discount Days
-------------
\ **Description**\ 
 \ *Number of days from invoice date to be eligible for discount*\ 
\ **Help**\ 
 \ *The Discount Days indicates the number of days that payment must be received in to be eligible for the stated discount.*\ 

Discount %
----------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 
