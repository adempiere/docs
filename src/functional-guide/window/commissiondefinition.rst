
.. _functional-guide/window/commissiondefinition:

=====================
Commission Definition
=====================

Maintain Commissions and Royalties

Help
====
Define how and when you want the commissions to be calculated and to whom to pay it.
The Commissions Window allows you define how commissions and royalties will be paid. You can pay multiple commissions for the same order or invoice (e.g. to the person entering the transaction, to the person responsible for sale of the product (category) and or business partner (group).

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Commission
----------
\ **Description**\ 
 \ *Define Commission Rule*\ 
\ **Help**\ 
 \ *Define when to pay a commission to whom.  For each period, you start the calculation of the commission after the transaction for that period are completed or closed.*\ 

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

Commission Group
----------------

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Calculation Basis
-----------------
\ **Description**\ 
 \ *Basis for the calculation the commission*\ 
\ **Help**\ 
 \ *The Calculation Basis indicates the basis to be used for the commission calculation.*\ 

Frequency Type
--------------
\ **Description**\ 
 \ *Frequency of event*\ 
\ **Help**\ 
 \ *The frequency type is used for calculating the date of the next event.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Paid totally
------------
\ **Description**\ 
 \ *The document is totally paid*\ 
\ **Help**\ 
 \ *The document has been paid totally, i.e. there is nothing left to pay.*\ 

IsDaysDueFromPaymentTerm
------------------------

Allow RMA
---------
\ **Description**\ 
 \ *Allow to consider RMA*\ 
\ **Help**\ 
 \ *When active, RMAs are considered*\ 

List Details
------------
\ **Description**\ 
 \ *List document details*\ 
\ **Help**\ 
 \ *The List Details checkbox indicates that the details for each document line will be displayed.*\ 

Copy Lines
----------
\ **Description**\ 
 \ *Copy Commission Lines from other Commission*\ 

Date last run
-------------
\ **Description**\ 
 \ *Date the process was last run.*\ 
\ **Help**\ 
 \ *The Date Last Run indicates the last time that a process was run.*\ 

Commission Line
---------------
\ **Description**\ 
 \ *Define your commission calculation rule*\ 
\ **Help**\ 
 \ *Define the selection criteria for paying the commission. If you do not enter restricting parameters (e.g. for specific Business Partner (Groups) or Product (Categories), etc. all transactions for the period will be used to calculate the commission.

After converting from the transaction to the commission currency,
the formula for calculating the commission is:

(Converted Amount - Subtract Amount) * Amount Multiplier
+ (Actual Quantity - Subtract Quantity) * Quantity Multiplier

You can choose, that only positive amounts (Converted Amount - Subtract Amount) and positive quantities (Actual Quantity - Subtract Quantity) are used in the calculation.*\ 

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

Commission
----------
\ **Description**\ 
 \ *Commission*\ 
\ **Help**\ 
 \ *The Commission Rules or internal or external company agents, sales reps or vendors.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

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

Commission only specified Orders
--------------------------------
\ **Description**\ 
 \ *Commission only Orders or Invoices, where this Sales Rep is entered*\ 
\ **Help**\ 
 \ *Sales Reps are entered in Orders and Invoices. If selected, only Orders and Invoices for this Sales Reps are included in the calculation of the commission.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department.*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Product Class
-------------
\ **Description**\ 
 \ *Class of a Product*\ 
\ **Help**\ 
 \ *Identifies the Class which this product belongs to*\ 

Product Classification
----------------------
\ **Description**\ 
 \ *Classification of a Product*\ 
\ **Help**\ 
 \ *Identifies the classification which this product belongs to.*\ 

Product Group
-------------
\ **Description**\ 
 \ *Group of a Product*\ 
\ **Help**\ 
 \ *Identifies the Group which this product belongs to.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Payment Rule
------------
\ **Description**\ 
 \ *How you pay the invoice*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of invoice payment.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Channel
-------
\ **Description**\ 
 \ *Sales Channel*\ 
\ **Help**\ 
 \ *The Sales Channel identifies a channel (or method) of sales generation.*\ 

Collection Status
-----------------
\ **Description**\ 
 \ *Invoice Collection Status*\ 
\ **Help**\ 
 \ *Status of the invoice collection process*\ 

Dunning Level
-------------

Days From
---------

Days To
-------

Minimum Compliance (%)
----------------------
\ **Description**\ 
 \ *Minimum Compliance of Forecast*\ 

Maximum Compliance (%)
----------------------
\ **Description**\ 
 \ *Maximum Compliance of Forecast*\ 

Percentage From Price
---------------------
\ **Description**\ 
 \ *Percentage From Price is for calculate % of compliance from price instead quantity*\ 

Maximum Percentage
------------------
\ **Description**\ 
 \ *Maximum Percentage of the entire amount*\ 
\ **Help**\ 
 \ *Percentage of an amount (up to 100)*\ 

Is Percentage
-------------
\ **Description**\ 
 \ *Indicates that Quantity is expressed as Percentage (%)*\ 

Subtract Amount
---------------
\ **Description**\ 
 \ *Subtract Amount for generating commissions*\ 
\ **Help**\ 
 \ *The Subtract Amount indicates the amount to subtract from the total amount prior to multiplication.*\ 

Multiplier Amount
-----------------
\ **Description**\ 
 \ *Multiplier Amount for generating commissions*\ 
\ **Help**\ 
 \ *The Multiplier Amount indicates the amount to multiply the total amount generated by this commission run by.*\ 

Subtract Quantity
-----------------
\ **Description**\ 
 \ *Quantity to subtract when generating commissions*\ 
\ **Help**\ 
 \ *The Quantity Subtract identifies the quantity to be subtracted before multiplication*\ 

Multiplier Quantity
-------------------
\ **Description**\ 
 \ *Value to multiply quantities by for generating commissions.*\ 
\ **Help**\ 
 \ *The Multiplier Quantity field indicates the amount to multiply the quantities accumulated for this commission run.*\ 

Positive only
-------------
\ **Description**\ 
 \ *Do not generate negative commissions*\ 
\ **Help**\ 
 \ *The Positive Only check box indicates that if the result of the subtraction is negative, it is ignored.  This would mean that negative commissions would not be generated.*\ 

Sales Representative
--------------------

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

Commission
----------
\ **Description**\ 
 \ *Commission*\ 
\ **Help**\ 
 \ *The Commission Rules or internal or external company agents, sales reps or vendors.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 
