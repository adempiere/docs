
.. _window-withholding1099:

==================
Withholding (1099)
==================

Maintain Withholding Certificates

Help
====
The Withholding Window defines the rule used for calculating withholding amounts.

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Withholding
-----------
\ **Description**\ 
 \ *Withholding Rules*\ 
\ **Help**\ 
 \ *The Withholding Rules Tab define the rules governing the withholding of amounts.*\ 

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

Paid to third party
-------------------
\ **Description**\ 
 \ *Amount paid to someone other than the Business Partner*\ 
\ **Help**\ 
 \ *The Paid to Third Party checkbox indicates that the amounts are paid to someone other than the Business Partner.*\ 

Beneficiary
-----------
\ **Description**\ 
 \ *Business Partner to whom payment is made*\ 
\ **Help**\ 
 \ *The Beneficiary indicates the Business Partner to whom payment will be made.  This field is only displayed if the Paid to Third Party checkbox is selected.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Tax withholding
---------------
\ **Description**\ 
 \ *This is a tax related withholding*\ 
\ **Help**\ 
 \ *The Tax Withholding checkbox indicates if this withholding is tax related.*\ 

Prorate tax
-----------
\ **Description**\ 
 \ *Tax is Prorated*\ 
\ **Help**\ 
 \ *The Prorate Tax checkbox indicates if this tax is prorated.*\ 

Percent withholding
-------------------
\ **Description**\ 
 \ *Withholding amount is a percentage of the invoice amount*\ 
\ **Help**\ 
 \ *The Percent Withholding checkbox indicates if the withholding amount is a percentage of the invoice amount.*\ 

Fix amount
----------
\ **Description**\ 
 \ *Fix amounted amount to be levied or paid*\ 
\ **Help**\ 
 \ *The Fixed Amount indicates a fixed amount to be levied or paid.*\ 

Percent
-------
\ **Description**\ 
 \ *Percentage*\ 
\ **Help**\ 
 \ *The Percent indicates the percentage used.*\ 

Min Amount
----------
\ **Description**\ 
 \ *Minimum Amount in invoice currency*\ 
\ **Help**\ 
 \ *The Minimum amount indicates the minimum amount as stated in the currency of the invoice.*\ 

Max Amount
----------
\ **Description**\ 
 \ *Maximum Amount in invoice currency*\ 
\ **Help**\ 
 \ *The Maximum Amount indicates the maximum amount in invoice currency.*\ 

Threshold min
-------------
\ **Description**\ 
 \ *Minimum gross amount for withholding calculation*\ 
\ **Help**\ 
 \ *The Threshold Minimum indicates the minimum gross amount to be used in the withholding calculation.*\ 

Threshold max
-------------
\ **Description**\ 
 \ *Maximum gross amount for withholding calculation  (0=no limit)*\ 
\ **Help**\ 
 \ *The Threshold maximum indicates the maximum gross amount to be used in the withholding calculation .  A value of 0 indicates there is no limit.*\ 

Accounting
----------
\ **Description**\ 
 \ *Withholding Accounting*\ 
\ **Help**\ 
 \ *The Withholding Accounting Tab defines the accounting parameters for Withholding.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Withholding
-----------
\ **Description**\ 
 \ *Withholding type defined*\ 
\ **Help**\ 
 \ *The Withholding indicates the type of withholding to be calculated.*\ 

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Withholding
-----------
\ **Description**\ 
 \ *Account for Withholdings*\ 
\ **Help**\ 
 \ *The Withholding Account indicates the account used to record withholdings.*\ 
