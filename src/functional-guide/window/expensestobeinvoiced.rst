
.. _functional-guide/window/expensestobeinvoiced:

=========================
Expenses (to be invoiced)
=========================

View expenses and charges not invoiced to customers

Help
====
Before invoicing to customers, check the expense lines to be invoiced

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Customer
--------
\ **Description**\ 
 \ *Business Partner (Customers) to be invoiced*\ 

.. note::
    If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

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

Name 2
------
\ **Description**\ 
 \ *Additional Name*\ 

Customer
--------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Customer*\ 
\ **Help**\ 
 \ *The Customer checkbox indicates if this Business Partner is a customer.  If it is select additional fields will display which further define this customer.*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Open Balance
------------
\ **Description**\ 
 \ *Total Open Balance Amount in primary Accounting Currency*\ 
\ **Help**\ 
 \ *The Total Open Balance Amount is the calculated open item amount for Customer and Vendor activity.  If the Balance is below zero, we owe the Business Partner.  The amount is used for Credit Management.
Invoices and Payment Allocations determine the Open Balance (i.e. not Orders or Payments).*\ 

Report Line
-----------
\ **Description**\ 
 \ *Time and Expense Report Line (not invoiced)*\ 
\ **Help**\ 
 \ *View and modify Time and Expense Report Lines.  It lists expense items for the business partner on the expense line where the expense lines have no orders yet. (Sales Orders are created).*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Expense Report
--------------
\ **Description**\ 
 \ *Time and Expense Report*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Expense Date
------------
\ **Description**\ 
 \ *Date of expense*\ 
\ **Help**\ 
 \ *Date of expense*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Time Report
-----------
\ **Description**\ 
 \ *Line is a time report only (no expense)*\ 
\ **Help**\ 
 \ *The line contains only time information*\ 

Invoiced
--------
\ **Description**\ 
 \ *Is this invoiced?*\ 
\ **Help**\ 
 \ *If selected, invoices are created*\ 

Sales Order Line
----------------
\ **Description**\ 
 \ *Sales Order Line*\ 
\ **Help**\ 
 \ *The Sales Order Line is a unique identifier for a line in an order.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *Invoiced Quantity*\ 
\ **Help**\ 
 \ *The Invoiced Quantity indicates the quantity of a product that have been invoiced.*\ 

Expense Amount
--------------
\ **Description**\ 
 \ *Amount for this expense*\ 
\ **Help**\ 
 \ *Expense amount in currency*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Invoice Price
-------------
\ **Description**\ 
 \ *Unit price to be invoiced or 0 for default price*\ 
\ **Help**\ 
 \ *Unit Price in the currency of the business partner!  If it is 0, the standard price of the sales price list of the business partner (customer) is used.*\ 

Converted Amount
----------------
\ **Description**\ 
 \ *Converted Amount*\ 
\ **Help**\ 
 \ *The Converted Amount is the result of multiplying the Source Amount by the Conversion Rate for this target currency.*\ 

Price Invoiced
--------------
\ **Description**\ 
 \ *The priced invoiced to the customer (in the currency of the customer's AR price list) - 0 for default price*\ 
\ **Help**\ 
 \ *The invoiced price is derived from the Invoice Price entered and can be overwritten.  If the price is 0, the default price on the customer's invoice is used.*\ 

Time Type
---------
\ **Description**\ 
 \ *Type of time recorded*\ 
\ **Help**\ 
 \ *Differentiate time types for reporting purposes (In parallel to Activities)*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for a document*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount for a document.*\ 

Line Amount
-----------
\ **Description**\ 
 \ *Line Extended Amount (Quantity * Actual Price) without Freight and Charges*\ 
\ **Help**\ 
 \ *Indicates the extended line amount based on the quantity and the actual price.  Any additional charges or freight are not included.  The Amount may or may not include tax.  If the price list is inclusive tax, the line amount is the same as the line total.*\ 

Line Total
----------
\ **Description**\ 
 \ *Total line amount incl. Tax*\ 
\ **Help**\ 
 \ *Total line amount*\ 

Note
----
\ **Description**\ 
 \ *Optional additional user defined information*\ 
\ **Help**\ 
 \ *The Note field allows for optional entry of user defined information regarding this record*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Project Task
------------
\ **Description**\ 
 \ *Actual Project Task in a Phase*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 
