
.. _functional-guide/window/window-taxrateparent:

===============
Tax Rate Parent
===============

Maintain Taxes and their Rates

Help
====
The Tax Rate Window defines the different taxes used for each tax category.  For example Sales Tax must be defined for each State in which it applies.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Tax Parent
----------
\ **Description**\ 
 \ *Tax definition*\ 
\ **Help**\ 
 \ *The Tax Rate Window defines the different taxes used for each tax category.  For example Sales Tax must be defined for each State in which it applies.
If you have multiple taxes create a summary level tax with the approximate total tax rate and the actual tax rates pointing to the summary level tax as their parent. When entering the order or invoice lines the tax is estimated the correct tax is calculated when the document is processed.  The tax is always calculated from the line net amount. If one tax has a the tax basis the line net amount and another tax you need to adjust the percentage to result in the correct amount.
Valid From/To is determined by the parent tax.*\ 

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

Tax Category
------------
\ **Description**\ 
 \ *Tax Category*\ 
\ **Help**\ 
 \ *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

SO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on sales*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on sales, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

Requires Tax Certificate
------------------------
\ **Description**\ 
 \ *This tax rate requires the Business Partner to be tax exempt*\ 
\ **Help**\ 
 \ *The Requires Tax Certificate indicates that a tax certificate is required for a Business Partner to be tax exempt.*\ 

Document Level
--------------
\ **Description**\ 
 \ *Tax is calculated on document level (rather than line by line)*\ 
\ **Help**\ 
 \ *If the tax is calculated on document level, all lines with that tax rate are added before calculating the total tax for the document.
Otherwise the tax is calculated per line and then added.
Due to rounding, the tax amount can differ.*\ 

Sales Tax
---------
\ **Description**\ 
 \ *This is a sales tax (i.e. not a value added tax)*\ 
\ **Help**\ 
 \ *If selected AP tax is handled as expense, otherwise it is handled as a VAT credit.*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Parent Tax
----------
\ **Description**\ 
 \ *Parent Tax indicates a tax that is made up of multiple taxes*\ 
\ **Help**\ 
 \ *The Parent Tax indicates a tax that is a reference for multiple taxes.  This allows you to charge multiple taxes on a document by entering the Parent Tax*\ 

SO/PO Type
----------
\ **Description**\ 
 \ *Sales Tax applies to sales situations, Purchase Tax to purchase situations*\ 
\ **Help**\ 
 \ *Sales Tax: charged when selling - examples: Sales Tax, Output VAT (payable)
Purchase Tax: tax charged when purchasing - examples: Use Tax, Input VAT (receivable)*\ 

Rate
----
\ **Description**\ 
 \ *Rate or Tax or Exchange*\ 
\ **Help**\ 
 \ *The Rate indicates the percentage to be multiplied by the source to arrive at the tax or exchange amount.*\ 

Rule
----

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Tax Children
------------
\ **Description**\ 
 \ *Tax definition*\ 
\ **Help**\ 
 \ *The Tax Rate Window defines the different taxes used for each tax category.  For example Sales Tax must be defined for each State in which it applies.
If you have multiple taxes create a summary level tax with the approximate total tax rate and the actual tax rates pointing to the summary level tax as their parent. When entering the order or invoice lines the tax is estimated the correct tax is calculated when the document is processed.  The tax is always calculated from the line net amount. If one tax has a the tax basis the line net amount and another tax you need to adjust the percentage to result in the correct amount.
Valid From/To is determined by the parent tax.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Tax Category
------------
\ **Description**\ 
 \ *Tax Category*\ 
\ **Help**\ 
 \ *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*\ 

Valid from
----------
\ **Description**\ 
 \ *Valid from including this date (first day)*\ 
\ **Help**\ 
 \ *The Valid From date indicates the first day of a date range*\ 

SO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on sales*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on sales, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

Requires Tax Certificate
------------------------
\ **Description**\ 
 \ *This tax rate requires the Business Partner to be tax exempt*\ 
\ **Help**\ 
 \ *The Requires Tax Certificate indicates that a tax certificate is required for a Business Partner to be tax exempt.*\ 

Document Level
--------------
\ **Description**\ 
 \ *Tax is calculated on document level (rather than line by line)*\ 
\ **Help**\ 
 \ *If the tax is calculated on document level, all lines with that tax rate are added before calculating the total tax for the document.
Otherwise the tax is calculated per line and then added.
Due to rounding, the tax amount can differ.*\ 

Sales Tax
---------
\ **Description**\ 
 \ *This is a sales tax (i.e. not a value added tax)*\ 
\ **Help**\ 
 \ *If selected AP tax is handled as expense, otherwise it is handled as a VAT credit.*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Parent Tax
----------
\ **Description**\ 
 \ *Parent Tax indicates a tax that is made up of multiple taxes*\ 
\ **Help**\ 
 \ *The Parent Tax indicates a tax that is a reference for multiple taxes.  This allows you to charge multiple taxes on a document by entering the Parent Tax*\ 

SO/PO Type
----------
\ **Description**\ 
 \ *Sales Tax applies to sales situations, Purchase Tax to purchase situations*\ 
\ **Help**\ 
 \ *Sales Tax: charged when selling - examples: Sales Tax, Output VAT (payable)
Purchase Tax: tax charged when purchasing - examples: Use Tax, Input VAT (receivable)*\ 

Tax Indicator
-------------
\ **Description**\ 
 \ *Short form for Tax to be printed on documents*\ 
\ **Help**\ 
 \ *The Tax Indicator identifies the short name that will print on documents referencing this tax.*\ 

Rate
----
\ **Description**\ 
 \ *Rate or Tax or Exchange*\ 
\ **Help**\ 
 \ *The Rate indicates the percentage to be multiplied by the source to arrive at the tax or exchange amount.*\ 

Rule
----

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

To
--
\ **Description**\ 
 \ *Receiving Country*\ 
\ **Help**\ 
 \ *The To Country indicates the receiving country on a document*\ 

Region
------
\ **Description**\ 
 \ *Identifies a geographical Region*\ 
\ **Help**\ 
 \ *The Region identifies a unique Region for this Country.*\ 

To
--
\ **Description**\ 
 \ *Receiving Region*\ 
\ **Help**\ 
 \ *The To Region indicates the receiving region on a document*\ 

Tax ZIP
-------
\ **Description**\ 
 \ *Tax Postal/ZIP*\ 
\ **Help**\ 
 \ *For local tax you may have to define a list of (ranges of) postal codes or ZIPs*\ 

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

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

ZIP
---
\ **Description**\ 
 \ *Postal code*\ 
\ **Help**\ 
 \ *The Postal Code or ZIP identifies the postal code for this entity's address.*\ 

ZIP To
------
\ **Description**\ 
 \ *Postal code to*\ 
\ **Help**\ 
 \ *Consecutive range to*\ 

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

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

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

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Tax Indicator
-------------
\ **Description**\ 
 \ *Short form for Tax to be printed on documents*\ 
\ **Help**\ 
 \ *The Tax Indicator identifies the short name that will print on documents referencing this tax.*\ 

Accounting
----------
\ **Description**\ 
 \ *Accounting*\ 
\ **Help**\ 
 \ *The Accounting Tab defines the accounting parameters to be used for transactions referencing this Tax Rate.*\ 

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

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

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

Tax Due
-------
\ **Description**\ 
 \ *Account for Tax you have to pay*\ 
\ **Help**\ 
 \ *The Tax Due Account indicates the account used to record taxes that you are liable to pay.*\ 

Tax Liability
-------------
\ **Description**\ 
 \ *Account for Tax declaration liability*\ 
\ **Help**\ 
 \ *The Tax Liability Account indicates the account used to record your tax liability declaration.*\ 

Tax Credit
----------
\ **Description**\ 
 \ *Account for Tax you can reclaim*\ 
\ **Help**\ 
 \ *The Tax Credit Account indicates the account used to record taxes that can be reclaimed*\ 

Tax Receivables
---------------
\ **Description**\ 
 \ *Account for Tax credit after tax declaration*\ 
\ **Help**\ 
 \ *The Tax Receivables Account indicates the account used to record the tax credit amount after your tax declaration.*\ 

Tax Expense
-----------
\ **Description**\ 
 \ *Account for paid tax you cannot reclaim*\ 
\ **Help**\ 
 \ *The Tax Expense Account indicates the account used to record the taxes that have been paid that cannot be reclaimed.*\ 
